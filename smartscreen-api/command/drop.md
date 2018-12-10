---
description: >-
  Drop a site, portal, media playlist, slideshow URL viz. e-Commerce, Bourses' 
  Trading & Analytics, Videos, Images, Audio clips...
---

# Drop

## CLI

```text
drop [(url)|(mpath)] (duration) (frame) (animate) (animate duration) (play mode)
```

## JSON

```text
{"cmd":"drop","type":"url","src":["(url1)|(mpath1)","(url2)|(mpath2)..."],"duration":(duration),"frame":"(frame)","animate":"(animate)","anidur
ation":(animate duration),"bgcolor":"(background color)","pmode":"(play mode)"}
```

## Example

```text
drop http://cdn.ypcall.com/miki/yp/djdemo/sugar.mp4 30 main
```

```text
drop http://cdn.ypcall.com/miki/yp/djdemo/sugar.mp4 30 main fade 2 loop
```

```text
{"cmd":"drop","type":"url","src":["http://cdn.ypcall.com/miki/yp/djdemo/sugar.mp4"],"duration":0,"frame":"t2","animate":"fade","aniduration":
2,"bgcolor":"white","pmode":"loop"}
```

## _Note_

> 1. duration: unit is _'sec’_, _0_ means play _till the end_ of the media file
> 2. frame: can be _main, t1, t2, t3_ or _t4_
> 3. CLI mode: use “,” to separate multiple URLs
> 4. animate: can be _delay, fade, slide, left_ or _right_
> 5. animate duration: unit is _‘sec’_
> 6. pmode: can be _loop_ or _random_



