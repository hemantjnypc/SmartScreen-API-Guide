---
description: 'Drop a url - app, commerce portal, tickers, media - videos, images, audios...'
---

# "Drop"

## CLI

```text
drop [(url)|(mpath)] (duration) (frame) (animate) (animate duration) (play mode)
```

## JSON

```text
{"cmd":"drop","type":"url","src":["(url1)|(mpath1)","(url2)|(mpath2)"],"duration":"(duration)","frame":"(frame)","animate":"(animate)","anidur
ation":"(animate duration)","bgcolor":"(background color)","pmode":"(play mode)"}
```

## Example

```text
drop http://cdn.ypcall.com/miki/yp/djdemo/sugar.mp4 30 main
```

```text
drop http://cdn.ypcall.com/miki/yp/djdemo/sugar.mp4 30 main fade 2 loop
```

```text
{"cmd":"drop","type":"url","src":["http://cdn.ypcall.com/miki/yp/djdemo/sugar.mp4"],"duration":"0","frame":"t2","animate":"fade","aniduration":"
2","bgcolor":"white","pmode":"loop"}
```

## _Note_

> 1. duration: unit is _‘seconds’, ‘0’_ means _play till end_
> 2. frame: can be main, t1, t2, t3 or t4
> 3. CLI mode: use “,” to separate multiple URLs
> 4. animate: can be delay, fade, slide, left, right
> 5. animate duration: unit is _‘seconds’_
> 6. pmode: can be _loop_ or _random_

