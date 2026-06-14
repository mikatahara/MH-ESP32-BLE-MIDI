This Project
==============
This library is based on ESP32-BLE-MIDI.

Original project:
<a href="https://github.com/max22-/ESP32-BLE-MIDI">https://github.com/max22-/ESP32-BLE-MIDI</a>

- Added a function for sending system exclusive message.

void Midi::sendSysEx(uint8_t *sysex, uint16_t sizeofsysex);

Modified by Mikata Hara, 2026
