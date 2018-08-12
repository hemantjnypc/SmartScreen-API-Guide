# Introduction

---

#### Use _XMSG_ to control _mscreen_

Function: xmsg.send\(\)  
Paramters:  
   target: "mscreen@m.smartscreen.tv:6788"  
   body: {"in":{"fm":"\(from DDN\)","to":"\(to DDN\)"},"data":"\(mscreen command\)"}

#### 

#### Use _XRPC_ to control _mscreen_

Function: xrpc.call\(\)  
Parameters:  
   to: "mscreen@m.smartscreen.tv:6788"  
   func: "cmd"  
   body: {"target":"\(device name\)","data":"\(mscreen command\)"}

#### 

#### Command Format

1. CLI: Command line command, type is _string_ 
2. JSON: {"cmd":"drop",…}

#### 

#### Command Brief

1. Drop  
2. Notify  
3. Toast  
4. Marquee  
5. Text  
6. App  
7. Frame  
8. Touch  
9. Status   
10. Mote  
11. Emoji



