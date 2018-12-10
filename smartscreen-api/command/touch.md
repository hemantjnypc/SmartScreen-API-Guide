---
description: >-
  On-screen remote for controlling and navigating playlists/ slide shows// media
  and document file(s)
---

# Touch

## CLI

```text
touch (option) (value)
```

## JSON

```text
{"cmd":"touch","option":"(arg)","value":"(argv)"}
```

## Example

touch playnext

{"cmd":"touch","option":"playnext","value":""}

_On-screen remote control_ for controlling _play, pause,  stop, mute/unmute,  vol +/-, next, prev, first, last navigation_ of __adhoc _media files/ playlist tracks/ album images/ videos/ slideshow slides/ playstation channels_

## _Note_

**Touch** Commands

| **\#** | **option** | **description** |
| :--- | :--- | :--- |
| 1 | playnext | play next media |
| 2 | playprev | play previous media |
| 3 | playfirst | play first media |
| 4 | playlast | play last media |
| 5 | playlist | get playlist |
| 6 | playindex | play media by index of playlist |
| 7 | chnext | play next channel |
| 8 | chprev | play previous channel |
| 9 | chfirst | play first channel |
| 10 | chlast | play last channel |
| 11 | play | play media |
| 12 | pause | play pause |
| 13 | stop | play stop/pause |
| 14 | mute | mute |
| 15 | unmute | unmute |
| 16 | volup | volume up 10% |
| 17 | voldown | volume down 10% |
| 18 | console | console control command |
| 19 | setting | setting control command |
| 20 | eisetting | setting process command |

1. Please note that \(value\) is required for commands _console, setting_ & _eisetting_  in the list above, for all others it is set to _"" \(null\)_

