# Table of Contents
1. [Loops](#loops)
1. [Slicing](#slicing)



## Loops


```python
#print from 1 to n-1
for i in range(1,10):
  print(i)
>1
>2
>3
>4
>5
>6
>7
>8
>9

#print list in reverse
for i in reversed(range(10)):
  print(i)
>9
>8
>7
>6
>5
>4
>3
>2
>1
```


## Slicing

```python
#https://stackoverflow.com/questions/509211/understanding-pythons-slice-notation
a[start:end] # items start through end-1
a[start:]    # items start through the rest of the array
a[:end]      # items from the beginning through end-1
a[:]         # a copy of the whole array

a[-1]    # last item in the array
a[-2:]   # last two items in the array
a[:-2]   # everything except the last two items

a[::-1]    # all items in the array, reversed
a[1::-1]   # the first two items, reversed
a[:-3:-1]  # the last two items, reversed
a[-3::-1]  # everything except the last two items, reversed
```
