# Function on Spark

* [Anonymous functions syntax](https://docs.scala-lang.org/tour/basics.html#functions)

* Static methods in a global singleton object

```
object MyFunctions {
  def func1(s: String): String = { ... }
}

myRdd.map(MyFunctions.func1)
```
