# Commands & Usage

* Use of **xMsg** to control SmartScreen _**\(Asynchronous\)**_

  ```text
  Function: xmsg.send()

  Usage:
      {"in":"{"fm":"(from DDN)","to":"(to DDN)"}","cmd":"(SmartScreen command)", "attributes..."}

  Example:   {"in":"{"fm":"koYh3Ik1","to":"pJRt6H9G"}","cmd":“drop”,“type”:”url”,“src”:[“http://ypcloud.com”]}
  ```

* Use of **xRPC** to control SmartScreen _**\(Synchronous\)**_

  ```text
  Function: xrpc.call()

  Parameters:
    target:  {"target":"demo"} //'demo' being the user-defined target_device name (an 'alias' in lieu of the target_device 'DDN')
    func:    {"cmd":"(SmartScreen API command)", "attributes.."}
    body:    "data":func

  Example:   {"target":"demo"},{"cmd":”drop”,“type”:”url”,“src”:[“http://ypcloud.com”]}
  ```

* Command Format 1. CLI: _Command line_ command, type is _string_ 2. JSON: {"cmd":"drop",…}

