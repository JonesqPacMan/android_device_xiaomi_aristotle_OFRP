## Xiaomi 13T (_aristotle_)
## OrangeFox device tree

=========================================

The Xiaomi 13T (codenamed _"aristotle"_) is a high-end, mid-range smartphone from Xiaomi.

It was released in September 2023.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core CPU with 4x Arm Cortex-A78 up to 3.1GHz
Chipset | Mediatek Dimensity 8200
GPU     | Mali-G610 MC6
Memory  | 8/12 GB RAM
Shipped Android Version | 13
Storage | 256 GB (UFS 3.1)
Battery | Li-Po 5000 mAh, non-removable
Display | 1220 x 2712 pixels, 6.67 inches, 60/120/144 hz

## Device picture
![Xiaomi 13T](https://i02.appmifile.com/524_operator_sg/14/08/2023/936823ab29ba43b0bf4e42f09d424903.png "Xiaomi 13T")

## Features

Works:

- [X] ADB
- [X] Decryption (Android 13)
- [X] Display
- [X] Fastbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [X] USB OTG
- [X] Vibrator
- [X] Miscellaneous

## Building

You can find a full compile guide for OrangeFox [Here](https://wiki.orangefox.tech/en/dev/building)

_Lunch_ command :

```
lunch twrp_aristotle-eng && mka adbd vendorbootimage
```

### Copyright
 ```
  /*
  *  Copyright (C) 2025 The OrangeFox Recovery Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
