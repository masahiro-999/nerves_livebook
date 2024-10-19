# Nerves Livebook Firmware for M5Stack Core_MP135

[![CircleCI](https://dl.circleci.com/status-badge/img/circleci/257fp5XbSusGu2664ZDXYf/BFstga2jUV4huk8FatFyWJ/tree/core_mp135.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/circleci/257fp5XbSusGu2664ZDXYf/BFstga2jUV4huk8FatFyWJ/tree/core_mp135)

This repository is a fork of the [Nerves Livebook](https://github.com/nerves-livebook/nerves_livebook) project with the goal of providing Nerves Livebook for the M5Stack Core MP135. For use with targets other than Core MP135, please refer to the original Nerves Livebook repository.

You can download the firmware for Core MP135 from [here](https://github.com/masahiro-999/nerves_livebook/releases). For instructions on how to write the firmware to an SD card and other usage details, please refer to the official [Nerves Livebook](https://github.com/nerves-livebook/nerves_livebook) documentation.

## Build firmware with your own settings

```sh
$ $ git clone https://github.com/masahiro-999/nerves_livebook
$ cd nerves_livebook
$ export MIX_TARGET=core_mp135
$ mix deps.get
$ mix firmware
$ mix burn
```

## Support for M5Stack Core MP135

The M5Stack Core MP135 is a relatively new device, launched in 2024. While it may not be widely known yet, it offers unique features such as a built-in case and a wide range of sensors and devices that can be easily connected using standardized connectors, setting it apart from devices like the Raspberry Pi. As an entry-level IoT device, it opens up exciting new possibilities.

Currently, the Livebook for Core MP135 is maintained through a fork of the official repository. With more community involvement and users, I believe it has the potential to gain official support from the main repository.

If you resonate with this vision, please consider starring this repository on GitHub to show your support. The more backing I receive, the closer we get to achieving official support.

## License

Copyright (C) 2021-22 Frank Hunleth
Copyright (C) 2024 Masahiro Tsuji

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
