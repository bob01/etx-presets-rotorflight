[![GitHub license](https://img.shields.io/github/license/bob01/etxwidgets)](https://github.com/bob01/etxwidgets/main/LICENSE)


# Welcome to etx-Presets for RotorFlight
**New flight controller base settings for our ELRS RotorFlight electric and nitro R/C Helicopters**


### About etx-Presets
Goal is to get a new flight controller configured as quickly possible allowing the user to get to familiar FBL setup with all of the boilerplate stuff out of the way.
The idea is...
- flash the FC with RotorFlight 2.0 or later
- from the RotorFlight configurator CLI load the preset files that match your hardware, model (e.g. 400 or 700 size), base profiles and rates (optional)
- get straight to the familiar - name the FBL, verify gyro orientation, servo center/travels/direction, mixer settings, tweak PIDs and governor
- GO FLY

Even easier when used with transmitter models created with [etx-templates](https://github.com/bob01/etx-templates)


### Requirements / supported controllers
- RotorFlight 2 or later
- FlyDragon F722 v1 or v2 flight controller
- others will follow ehn available


### Features and some of the settings available with presets
- basic hardware settings for the chosen controller e.g. disable compass, barometer, set PID loop and black box frequency etc.
- ADC voltmeter config for BEC voltage (servo bus) telemetry if the ESC doesn't provide BEC telemetry
- halfduplex settings for ESCs with bi-directional telemetry for setup / programming
- basic RotorFlight settigs for modes, adjustments for a 4 bank setup (bank1, bank2, bank3, hold) battery/power settings, select ESC telemetry for battery voltage source etc, basic blackbox settings
- basic ELRS settings for RSSI channel (LQ) and ELRS telemetry sensor mappings compatible with models created with [etx-templates](https://github.com/bob01/etx-templates)
- default motor pole count to '10' (most common value for larger motors), enable governor feature etc if selected
- basic / conservative 400 or 700 filter settings including RPM filters and 4 dynamic notches
- basic servo settings for 1500us/333hz CCPM servos w/ geometry correction enabled (linear servo drives eg TDR2, TFF are rare) and a 760us/500hz or 1500us/333hz tail servo
- (optional) more locked in but still conservative 700 profile
- (optional) RACEFLIGHT rate which offers the more familiar rate / expo configuration
