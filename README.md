# sleeping-pie

Javascript project to help me better understand my sleeping patterns / [circadian rhythms](http://en.wikipedia.org/wiki/Circadian_rhythm)

## For your use

if you want to use this project, edit the file and modify ``hourData``:

```javascript
var hourData = [
{part: "core", start: "0:00", end:"8:00", sleeping: true},
{part: "daylight", start: "8:00", end: "00:00"},
];
```

this data should cover the 24h (or results might not be accurate). You can start writing your schedule from the time you wake up, the system "wraps" the last moment with the first one and you will see the slices appear in the correct "time place"


## Help

go to index and follow instructions
