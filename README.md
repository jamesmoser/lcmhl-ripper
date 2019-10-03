# LCMHL Schedule Ripper

This script downloads the LCMHL schedule in icalendar format and parses the game
content into comma delimited text for use in SMHA Ice Calendar spreadsheet.

Conveners can use this tool to process the original dataset as well as compare
schedule deltas which may occur due to game switches and reschedules.  Ideally, 
the output can be used to ensure no conflicts exist between LCMHL scheduled 
games and SMHA practices.

## Usage

To get the schedule in a format appropriate for the SMHA Ice Calendar:

```
rip --league=<league>, where league is A, B, or C
```

To save the schedule for later comparison:

```
rip --league=<league> --save
```

To compare the schedule to a previously saved schedule:

```
rip --league=<league> --compare
```


