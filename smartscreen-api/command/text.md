---
description: Push text with user-defined animation and attributes on a user-defined frame
---

# Text

## CLI

```text
text (text) (duration) (color) (size) (background color) (text alignment) (frame) (animate) (animate duration)
```

## JSON

```text
{"cmd":"text","msg":"(text)","duration":(duration),"color":"(color)","size":(size),"bgcolor":"(background color)","align":"(text
alignment)","frame":"(frame)","animate":"(animate)","aniduration":(animate duration),"bgcolor":"(background color)"}
```

## Example

```text
text HelloWorld! 30 black 3 white left text
```

```text
text “Hello World!” 30 lime 4 yellow center main
```

```text
{"cmd":"text","msg":"Hello World!","duration":30,"color":"lime":"size":4,"bgcolor":"white","align
":"left","frame":"t3","animate":"slide","aniduration":1,"bgcolor":"red "}
```

## _Note_

> 1. In CLI mode, if message contains _‘space’_, use "" to enclose the message string
> 2. \(duration\): unit is _'sec’_, _0_ means play _till the end_ of the media file
> 3. \(frame\): can be _main, t1, t2, t3_ or _t4_
> 4. \(animate\): can be _delay, fade, slide, left_ or _right_
> 5. \(animate duration\): unit is _‘sec’_
> 6. \(text alignment\): can be _left_ or _center_ or _right_



