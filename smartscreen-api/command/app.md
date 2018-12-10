---
description: Push an App URL to a user-defined frame for a user-defined duration
---

# App\*

## CLI

```text
app (url) (duration) (frame)
```

## JSON

```text
{"cmd":"app","url":"(url)","duration":(duration),"frame":"(frame)"}
```

## Example

```text
app http://www.ypcloud.com 30 main
```

```text
{"cmd":"app","url":"http://www.ypcloud.com","duration":"0","frame":"t2"}
```

## _Note_

> 1. \(duration\): unit is _'sec'_, _0_ means to run the app _endlessly_
> 2. \(frame\) can be _main, t1, t2, t3_ or _t4_

