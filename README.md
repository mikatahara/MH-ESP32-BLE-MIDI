MH-ESP32-BLE-MIDI
==============
This library is based on ESP32-BLE-MIDI.

Original project:
<a href="https://github.com/max22-/ESP32-BLE-MIDI">https://github.com/max22-/ESP32-BLE-MIDI</a>


### Changes

- Renamed one of the duplicate `pitchBend()` functions that used three arguments.
- Added a limit in `pitchBendTones()` to ensure the Pitch Bend value does not exceed `0x3FFF`.
- Changed `sendMMC(mmc_t command)` to use `sendSysEx()` instead of `sendMessage()`.
- Added `sendSysEx(uint8_t *sysex, uint16_t sizeofsysex)` function for sending system exclusive message.

Modified by Mikata Hara, 2026
