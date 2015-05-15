# opd-24hr-monitor
Monitor Oakland Police Department past 24 hours of calls

Command to get data in JSON:
```
curl 'http://209.232.103.136/agis/rest/services/callforservice_2015_FC/MapServer/0/query?f=json&where=I_STATUSID%3D%27A%27&returnGeometry=true&outFields=*&callback='
```
