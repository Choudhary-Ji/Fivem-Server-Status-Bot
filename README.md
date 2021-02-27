# FiveM Server Status
FiveM Server Status Discord Bot

## Requirements For Queue:

If You Are Using QBUS So You Don't Need To Change You Queue System
If You Are Not Using QBUS So I Have Edited The Source Code Of Connect Queue https://github.com/anderscripts/FiveM_Queue And Added That It Will Change The Queue And Connecting Count In The Server Status Bot Accordingly .

## Requirements For Uptime Showing:
You Need To Download This Script And Run Into Your FXServer https://github.com/Choudhary-Ji/Uptime-Script

## Download Queue For ESX From Here:
https://github.com/Choudhary-Ji/Connect-Queue-For-ESX

## Setup

1. Add the included fivemqueue to your server resources
2. Start the fivemqueue in your server.cfg
3. Set enviroment variables as described below

```
URL_SERVER - base url for fiveM server e.g. http://127.0.0.1:3501 (don't end with /)
LOG_LEVEL - Int of enum 0-4 specifying level of logs to display with 4 as no logs
CHANNEL_ID - channel id for updates to be pushed to
MESSAGE_ID - message id of previous update to edit (not required)
SUGGESTION_CHANNEL - channel to create suggestion embeds in
BUG_CHANNEL - channel to recieve bug reports
BUG_LOG_CHANNEL - channel to log bug reports
REPORT_CHANNEL: channel to send reports
REPORT_LOG_CHANNEL: channel to recieve reports
LOG_CHANNEL - channel to log status changes
```
## Running
1. `Run installde.cmd`
2. `run start.cmd`


  

