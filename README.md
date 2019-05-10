SHEET TO CHART
==============

A script that converts a public google sheet data to a timeline chart.

The input for it is a Google sheet id (the part of the URL that looks cryptic)
for example in the following URL:
```
https://docs.google.com/spreadsheets/d/19AoR5siwI-cbrlJN47cZV7nhoZ9mO76XBUAWtO5Xb8A/edit#gid=0
```

The sheet ID is `19AoR5siwI-cbrlJN47cZV7nhoZ9mO76XBUAWtO5Xb8A`, also make sure
the sheet if public as otherwise the sheet won't be accessible by the tool.

The code doesn't need any server and doesn't transfer your data to any
thirdparty, it uses Ajax to get the sheet data and convert it with google chart
API to a timeline.
