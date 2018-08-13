# "Notify"

### CLI

```text
notify (message) (duration) (color) (size)
```

### JSON

```text
{"cmd":"notify","msg":"(message)","duration":"(duration)","color":"(color)":"size":"(size)"}
```

### Example

```text
notify HelloWorld! 30 black 3
```

```text
notify “Hello World!” 30
```

```text
{"cmd":"notify","msg":"Hello World!","duration":"30","color":"lime":"size":"4"}
```

### Message Keywords

1.\(%time\): current time.

2.\(%time\#yyyy/mm/dd hh:nn:ss\): formatted current time

### _Note_

> In CLI mode, if message contains _‘space’_, use "" to enclose the message string



