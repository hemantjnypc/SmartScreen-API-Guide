---
description: Synchronous and asynchronous communication
---

# Commands & Usage

* Use of **xMsg** to control SmartScreen _**\(Asynchronous\)**_

```text
Function: xmsg.send()

Usage:
    {"in":"{"fm":"(from DDN)","to":"(to DDN)"}","data":"{"cmd":"(SmartScreen command)", 'attribute' key_value pairs...}""}

Example:   {"in":"{"fm":"koYh3Ik1","to":"pJRt6H9G"}","data":"{"cmd":“drop”,“type”:”url”,“src”:[“http://www.ypcloud.com”]}""}
```

* Use of **xRPC** to control SmartScreen _**\(Synchronous\)**_

```text
Function: xrpc.call()

Parameters:
  target:  {"target":"demo"} //'demo' being the user-defined target_device name (an 'alias' in lieu of the target_device 'DDN')
  func:    {"cmd":"(SmartScreen API command)", 'attribute' key_value pairs)...}
  body:    "data":func

Example:   {"target":"demo","data":"{"cmd":”drop”,“type”:”url”,“src”:[“http://ypcloud.com”]}"}
```

* _Command Format_ 
  * CLI: _Command line_ command, type is '_string_ '
  * JSON: {"cmd":"drop",…}

