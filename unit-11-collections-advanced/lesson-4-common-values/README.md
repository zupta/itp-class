# Set Operations (Union)

Create a function that will return a set of all elements in at least one of the tuples.

```python
tuple_1 = (1, 5, 6, 4, 8)
tuple_2 = (1, 6, 10, 5)

common_values(tuple_1, tuple_2)  #{1, 4, 5, 6, 8, 10}
```

The function should additionally check to see that the parameters are tuple objects. If at least one isn't, the function should return a string that says "Params not of type 'tuple'".
