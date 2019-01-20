# OctoPrint-FilamentSensor-ng-OrangePi

I made this because [Octoprint-Filament-Sensor-ng](https://github.com/Red-M/Octoprint-Filament-Sensor-ng) doesn't have support for OrangePi.

[OctoPrint](http://octoprint.org/) plugin that integrates with a filament sensor hooked up to a Orange Pi GPIO pin and allows the filament spool to be changed during a print if the filament runs out.

Initial work based on the [Octoprint-Filament-Sensor-ng](https://github.com/Red-M/Octoprint-Filament-Sensor-ng) plugin by Red-M.
Initial work based on the [Octoprint-Filament-Reloaded](https://github.com/kontakt/Octoprint-Filament-Reloaded) plugin by kontakt.
Initial work based on the [Octoprint-Filament](https://github.com/MoonshineSG/Octoprint-Filament) plugin by MoonshineSG.

## Required sensor

Using this plugin requires a filament sensor.

For OrangePi use SUNXI mode and the pin being used needs to be entered by name (e.g. PA01, PC07)

## Features

* Configurable GPIO pin.
* Debounce noisy sensors.
* Support norbally open and normally closed sensors.
* Execution of custom GCODE when out of filament detected.
* Optionally pause print when out of filament.

## Installation

* Manually using this URL: https://github.com/deadly667/Octoprint-Filament-Sensor-ng/archive/master.zip

## Configuration

After installation, configure the plugin via OctoPrint Settings interface.
