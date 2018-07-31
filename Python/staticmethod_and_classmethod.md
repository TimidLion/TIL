```
  class A(object):
      def foo(self,x):
          print "executing foo(%s,%s)"%(self,x)

      @classmethod
      def class_foo(cls,x):
          print "executing class_foo(%s,%s)"%(cls,x)

      @staticmethod
      def static_foo(x):
          print "executing static_foo(%s)"%x    

  a=A()
```

## @classmethod
Encouraged to use as
```A.class_foo(1)```
not the
```a.class_foo(1)```

However, it works even in the second case.

## @staticmethod

Nither ```cls``` nor ```self``` can't call ```static_foo(1)```.

Staticmethods are used to group functions which have some logical connection with a class to the class.
