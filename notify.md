## 'Notify'

---

### CLI

```
notify (message) (duration) (color) (size)
```

### JSON

```
{"cmd":"notify","msg":"(message)","duration":"(duration)","color":"(color)":"size":"(size)"}
```

### Example

```
notify HelloWorld! 30 black 3
```

```
notify “Hello World!” 30
```

```
{"cmd":"notify","msg":"Hello World!","duration":"30","color":"lime":"size":"4"}

```


### Message Keywords
<P>1.(%time): current time.
<P>2.(%time#yyyy/mm/dd hh:nn:ss): formatted current time

#### _Note_

> In CLI mode, if message contains _‘space’_, use "" to enclose the message string






