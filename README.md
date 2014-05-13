## Revolution watchface

Modified version of [Revolution](https://github.com/DouweM/PebbleRevolution/) by Douwe Maan.

I made the watchface display the year instead of seconds to improve battery life, updating the display and processing only once per minute, instead of every second.

It is the American date format.


I added [QuickTapPlus](https://github.com/grep-awesome/QuickTapPlus) by grep-awesome. I used a black background, showed the time and weather, and enabled autohide after two seconds. I made quicktap only trigger on z axis motion (straight into or out of the screen) so I can twist for just backlight and still have the time nice and large, but still fairly easily activate QTP.

There were a couple bugs in QTP, so I fixed them and it hopefully shouldn't crash anymore (if you get this watchface to crash, let me know - I'd love to fix it). I made some performance and efficiency improvements as well.
