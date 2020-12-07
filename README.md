# deq-bug
a temporary repo for showing a bug with VecDeque

This is a temporary repo for a bug reproduction.

The interesting place is highlighted below:

```
pop: Some(6e)
pop: Some(74)
pop: Some(75)
deq len: 0
pop: Some(2f)
BUG ^^^
deq len: 31
pop: Some(75)
pop: Some(62)
pop: Some(75)
pop: Some(6e)
pop: Some(74)
```
