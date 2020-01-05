# ESP32CAM with TFT display

Adapted from [IdeasNProjects](https://github.com/0015/IdeasNProjects/tree/master/ESP32_CAM_AICamera_Labelling) by Eric N ([0015](https://github.com/0015)). (Copyright 2019 Eric N under Apache License, Version 2.0).
[ESP32 CAM | Google Vision - [Part.7] AI Camera📷🔥(Image labeling)](https://youtu.be/bpCCqerQ56o) - (https://github.com/0015/IdeasNProjects/tree/master/ESP32_CAM_AICamera_Labelling)

** Work in progress **
** Will not work now **

## Hardware
- Ai-Thinker ESP32-CAM
- 3.2 inch 320*240 SPI Serial TFT LCD Module Display Screen with Touch Panel Driver IC ILI9341 for MCU
- Push button

## Changes
- Removed image recognition code.
- Adapted for compilation on both PlatformIO and Arduino IDE.
- Added OTA update function.

## Dependencies
- [Arduino JPEGDecoder library](https://github.com/Bodmer/JPEGDecoder)
- [TFT_eSPI library](https://github.com/Bodmer/TFT_eSPI)

## License

Copyright 2020 Maple Rain Research Co., Ltd.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
