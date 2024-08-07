# geofs-atc-mod
> Short-hand atc commands for fast communications.

Example of short-hand command:<br>
**Input:** `ACA123 c ps f e B xp rwy 05 for dpt tx via B, r B, hls rwy 05`<br>
**Output:** *"ACA123 cleared for push and start face east Bravo expect runway 05 for departure taxi via Bravo, right Bravo, hold short runway 05."*

## How to use:
1. Install the tampermonkey extension: https://www.tampermonkey.net/
2. Open the `userscript.js` file in the src folder
3. Click the "copy as raw" button
4. Open the tampermonkey extension and make a new script
5. Paste the code into the new script and press "CTRL + S" to save
6. Open Geo-FS and make sure the code works

## Full command reference quide:
**Taxiway letters must be written in CAPITALS**

| Abbreviation | Output                    |
|--------------|---------------------------|
| af           | `Affirmative`             |
| arg          | `Arriving`                |
| arr          | `Arrival`                 |
| cl           | `Cancel`                  |
| cf           | `Confirm`                 |
| cd           | `Contact departure`       |
| c            | `Cleared`                 |
| cr           | `Cross`                   |
| cm           | `Climb maintain`          |
| ds           | `Decrease speed`          |
| dpg          | `Departing`               |
| dpt          | `Departure`               |
| dm           | `Descend maintain`        |
| e            | `East`                    |
| f            | `Face`                    |
| faf          | `Final approach fix`      |
| fnl          | `Final`                   |
| ga           | `Go around`               |
| hcp          | `Hold current position`   |
| hld          | `Hold`                    |
| hlp          | `Enter holding pattern`   |
| hls          | `Hold short`              |
| ifr          | `IFR`                     |
| is           | `Increase speed`          |
| l            | `Turn left heading`       |
| lup          | `Line up`                 |
| lnd          | `To land`                 |
| luw          | `Line up and wait`        |
| m            | `Maintain`                |
| n            | `North`                   |
| nm           | `Mile`                    |
| nms          | `Miles`                   |
| ne           | `Northeast`               |
| ng           | `Negative`                |
| nw           | `Northwest`               |
| r            | `Turn right heading`      |
| rc           | `Readback correct`        |
| rg           | `Roger`                   |
| rw           | `Runway`                  |
| s            | `South`                   |
| se           | `Southeast`               |
| sh           | `Set heading`             |
| sq           | `Squawk`                  |
| sw           | `Southwest`               |
| tkf          | `For take off`            |
| trf          | `Traffic`                 |
| tn           | `Turn`                    |
| tx           | `Taxi`                    |
| vfr          | `VFR`                     |
