---
description: Display animated text with user-defined attributes on any frame of the screen
---

# "Text"

## CLI

```text
text (text) (duration) (color) (size) (background color) (text alignment) (frame) (animate) (animate duration)
```

## JSON

```text
{"cmd":"text","msg":"(text)","duration":"(duration)","color":"(color)","size":"(size)","bgcolor":"(background color)","align":"(text
alignment)","frame":"(frame)","animate":"(animate)","aniduration":"(animate duration)","bgcolor":"(background color)"}
```

## Example

```text
text HelloWorld! 30 black 3 white left text
```

```text
text “Hello World!” 30 lime 4 yellow center main
```

```text
{"cmd":"text","msg":"Hello World!","duration":"30","color":"lime":"size":"4","bgcolor":"white","align
":"left","frame":"main","animate":"slide","aniduration":"1","bgcolor":"red "}
```

## _Note_

> 1. In CLI mode, if message contains _‘space’_, use "" to enclose the message string
> 2. Align can be _center, left_ or _right_
> 3. Frame can be _text, main, t1, t2, t3_ or _t4_
> 4. duration: unit is _‘seconds’_, ‘0’ means to _end play_
> 5. animate: can be _delay, fade, slide, left, right_
> 6. animate duration: unit is _‘seconds’_

