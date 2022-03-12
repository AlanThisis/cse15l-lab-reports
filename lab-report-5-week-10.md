# Lab Report 5
test 194
mine []
joe [url]

test 201
mine[]
joe [baz]

## Two Tests with Different result

> The first test that is different is test 194. The output of my implementation is `[]`, while the implementation in lab 9 is `[url]`

> The second test that is different is test 201. The output of my implementation is `[]`, while the implementation in lab 9 is `[baz]`

## Finding difference

I used the diff method. Which look something like this:

```
106d105
< [url]
115d113
< [baz]
```

