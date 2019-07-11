# Varargs

Add * symbol after the string declaration.

```
def func(strings: String*) {
	strings.map(println)
}
```
Then you can call

```
func("foo")

func("foo", "bar")

func("foo", "bar", "baz")
```
