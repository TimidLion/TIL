## decorator

```
def decorator(func):
    def wrap_func():
        print("I'm decorator!")
        return func
    return wrap_func
    
@decorator
def function(args):
    print("I'm function!")
```

If you want to add some function in front or the back of the specific code sections, you can use it.

[Good_Blog_Explained](https://blog.jonnung.com/python/2015/08/17/python-decorator/)
