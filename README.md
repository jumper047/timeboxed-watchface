![](https://raw.githubusercontent.com/hussin/timeboxed-watchface/master/assets/banner_basalt.png)

A simple, clean and customizable watchface for the Pebble smartwatch.

## Key features

 * Supports all Pebble models
 * Customize the watchface by choosing what modules to show and where.
 * Customize colors (you can choose between just text/background colors or change colors for every item)
 * Save and load color presets
 * Choose between 8 different fonts (Blocko, Blocko large, Pebble fonts, Archivo Narrow, OSP-DIN, Prototype, LECO and Konstruct W00)
 * Choose text alignment (Pebble and Pebble Time only)
 * Weather modules with current weather and temperature, wind speed and direction, with low and high for the day too.
 * Sunrise and sunset times.
 * Choose between OpenWeatherMap, Weather Underground and Yahoo Weather for weather data
 * Health modules with steps, distance walked, active time and calorie count (Pebble Time and Time Round only)
 * Display different modules for half an hour after you wake up (Pebble Time and Time Round only)
 * Display health data in a different color if you're falling behind your monthly average for that day of the week
 * Display additional timezones
 * Display cryptocurrency prices
 * Display phone's battery state (Android only)
 * Bluetooth disconnect icon and vibration alert
 * Quiet mode icon
 * See in the watch when there's an update available
 * Support for 14 languages (English, Portuguese, French, German, Spanish, Italian, Dutch, Danish, Turkish, Czech, Polish, Swedish, Finnish and Slovak)
 * Choice between various date formats.
 * Timeline Quickview support (Pebble Time only)
 * Tasker integration (Android only)

## Tasker integration notes
Create action "Send intent", fill next fields:
 - Action: com.getpebble.action.app.SEND
 - Extra: transaction_id: -1
 - Extra: msg_data:[{"key":137,"type":"string","length":0,"value":"!Text
       here!"}]
 - Extra: uuid:1354d7dc-b9e5-420d-9edf-533ee2fd4520

In second extra key can be 136 (slot a) or 137 (slot b). 
## License
Copyright (c) 2016 Luis Felipe Hussin Bento. Licensed under the MIT License.
