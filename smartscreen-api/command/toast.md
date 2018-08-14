---
description: Report action status
---

# "Toast"

## CLI

```text
toast (message) (heading) (icon) (transition) (duration)
```

## JSON

```text
{"cmd":"toast","msg":"(message)","heading":"(heading)","icon":"(icon)":"transition":"(transition)","duration":"(duration)"}
```

## Example

```text
toast HelloWorld! Welcome info plain
```

```text
{"cmd":"toast","msg":"Hello World!","heading":"Welcome","icon":"info":"transition":"plain","duration":"5"}
```

## _Note_

> 1. In CLI mode, if message contains _‘space’_, use "" to enclose the message string 
> 2. Icon: can be _info, warning, error_ and _success_
> 3. Transition: can be _plain, fade_ and _slide_
> 4. duration: unit is _‘seconds’, &gt;= 1_

