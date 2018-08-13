# "Marquee"

### CLI

```text
marquee (message) (duration) (color) (size)
```

### JSON

```text
{"cmd":"marquee","msg":"(message)","duration":"(duration)","color":"(color)":"size":"(size)","bgcolor","(background color)"}
```

### Example

```text
marquee HelloWorld! 30 black 3 white
```

```text
marquee "Hello World!" 30
```

```text
{"cmd":"marquee","msg":"Hello World!","duration":"30","color":"lime","size":"4","bgcolor":"black"}
```

### _Note_

> In CLI mode, if message contains ‘space’, use "" to enclose the message string



