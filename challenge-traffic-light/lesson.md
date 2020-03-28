# Traffic Light with TaskScheduler

This sketch implements a traffic light using the [Arduino TaskScheduler Library](https://github.com/arkhipenko/TaskScheduler/).
It goes from red to green and back.
Green light blinks before going back to yellow.

<div style="border:solid black 4px; display: flex; flex-direction: column; background:#ccc; padding:16px 16px; width: 84px">
  <wokwi-led color="red" label="8"></wokwi-led>
  <wokwi-led color="yellow" label="11"></wokwi-led>
  <wokwi-led color="green" label="9"></wokwi-led>
</div>

## The Challenge

Modify code to add a turn signal (a white LED connected to pin 13):

<div style="border:solid black 4px; display: inline-block; background:#ccc; padding:16px 16px 0">
  <wokwi-led color="white" label="13"></wokwi-led>
</div>

The turn signal up 3 seconds after green, stays on for 3 seconds, then blinks for 5 seconds together with green (in sync with green), before switching back to yellow.
