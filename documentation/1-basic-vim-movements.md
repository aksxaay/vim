
- [Movement Keys](#movement-keys)
    - [single movement](#single-movement)
    - [word movements](#word-movements)
    - [editing commands](#editing-commands)

# Movement Keys

### single movement

```js
```
```
j k -> move up and down
```

```
h l -> move left and right
```

### word movements

```
w -> hop forward by word (exclude spaces)
W -> hop forward by actual words 

b -> backwards by word
B -> backwards by word
```

### editing commands

```
yy -> yank a line
double yank

p (put) -> paste a line
```
```
dd -> delete that line
double delete
```
\***imp** *yank* and *delete* share the same buffer


```
u -> undo
ctrl + r -> redo
```

Delete an entire function
dd dd dd works but not efficient


| Shortcut | Alias             | Function         |
| -------- | ----------------- | ---------------- |
| j k      | vertical movement | move up and down |
|    h l      |horizontal movement                   |move left and right                  |
