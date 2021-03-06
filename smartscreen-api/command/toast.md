---
description: >-
  Action response notification with user-defined icon, heading and a message, at
  the bottom right of the main frame
---

# Toast

## CLI

```text
toast (message) (heading) (icon) (transition) (duration)
```

## JSON

```text
{"cmd":"toast","msg":"(message)","heading":"(heading)","icon":"(icon)":"transition":"(transition)","duration":(duration)}
```

## Example

```text
toast HelloWorld! Welcome info plain
```

```text
{"cmd":"toast","msg":"Hello World!","heading":"Welcome","icon":"info":"transition":"plain","duration":5}
```

## _Note_

> 1. In CLI mode, if message contains _‘space’_, use "" to enclose the message string 
> 2. \(icon\): can be _info, warning, error_ and _success_
> 3. \(transition\): can be _plain, fade_ and _slide_
> 4. \(duration\): unit is _‘sec’, &gt;= 1_

