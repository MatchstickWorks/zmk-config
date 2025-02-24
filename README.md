# MatchstickWorks ZMK Sandbox
Check the releases on the [Releases page](https://github.com/MatchstickWorks/zmk-config/releases) for the most current build of MatchstickWorks' ZMK-powered keyboards.

## StrataPad
There are different versions of the StrataPad board.

If the back of the middle PCB only says "StrataPad v1" that means it's version 1.0.

Version 1.1 and going forward will have the proper second decimal version numbering printed on them.

### LED Function Enabled
Made use of the default functionality from this module: https://github.com/caksoylar/zmk-rgbled-widget

Lifted from their repo:

> Blink 🟢/🟡/🔴 on boot depending on battery level (for both central/peripherals), thresholds set by CONFIG_RGBLED_WIDGET_BATTERY_LEVEL_HIGH and CONFIG_RGBLED_WIDGET_BATTERY_LEVEL_LOW
> Blink 🔴 on every battery level change if below critical battery level (CONFIG_RGBLED_WIDGET_BATTERY_LEVEL_CRITICAL)
> Blink 🔵 for connected, 🟡 for open (advertising), 🔴 for disconnected profiles on every BT profile switch
