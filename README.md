# WS2812FX-ESP32-segments-web-example
Kitesurfer1404's WS2812FX example adapted for ESP32.

## What's this?
This is just a new version of the [WS2812FX segments web example](https://github.com/kitesurfer1404/WS2812FX/tree/master/examples/ws2812fx_segments_web) adapted for ESP32.

## Why was this necessary?
The example available at the moment of publishing this new version was working fine for 1 single strip (usually 30 LEDs), but it was behaving very randomly when additional strips were attached.

## What's new?
The ESP32's RMT hardware supports up to 8 channels, and one of them has been used to drive a WS2812FX instance. The approach is similar to the one taken on the [ws2812fx_esp32 example](https://github.com/kitesurfer1404/WS2812FX/tree/master/examples/ws2812fx_esp32).

## So what's that WS2812FX library again?
All the details about this library can be found in the [WS2812FX Git repository](https://github.com/kitesurfer1404/WS2812FX).
