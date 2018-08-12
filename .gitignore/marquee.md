## 'Marquee' command

---

### CLI

```
marquee (message) (duration) (color) (size)
```

### JSON

```
{"cmd":"marquee","msg":"(message)","duration":"(duration)","color":"(color)":"size":"(size)","bgcolor","(background color)"}
```

### Example

```
marquee HelloWorld! 30 black 3 white
```

```
marquee "Hello World!" 30
```

```
{"cmd":"marquee","msg":"Hello World!","duration":"30","color":"lime","size":"4","bgcolor":"black"}
```

#### _Note_

> In CLI mode, if message contains ‘space’, use "" to enclose the message string





