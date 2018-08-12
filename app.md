## 'App'

---

### CLI

```
app (url) (duration) (frame)
```

### JSON

```
{"cmd":"app","url":"(url1)","duration":"(duration)","frame":"(frame)"}
```

### Example

```
app http://www.ypcloud.com 30 main
```

```
{"cmd":"app","url":"http://www.ypcloud.com","duration":"0","frame":"t2"}
```

#### _Note_

> 1. duration: unit is _'second'_, '_0'_ means to _play till end_
> 2. frame can be _main, t1, t2, t3_ or _t4_



