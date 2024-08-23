# Latch-Circuit

## Overview
- AMS, BSPD, IMDからの信号をモニタ・ラッチしてSDN回路に接続されるリレーをドライブする回路
- AMS, BSPD, IMDのインジケータドライブ回路

## Requirement
### Development
- Kicad 7.0
### Libraries
- ProjectEV-Kicad-Library
    - v7.0

## Usage
- Vsupply: 12V
- AMS, BSPD, IMD Signal Input Level: L=0V, H=12V

## Features
- MOSFETによるラッチング、リレードライブ
- AMS, BSPD, IMD信号入力はMOSFETのゲートであるため、ロジックレベルは3.3V~20Vまで対応可能

## Reference
- ["Reference Site Name"]("Reference URL")

## Author
- [ST04-tkmr](https://github.com/ST04-tkmr)

## License
- Copyright (c) 2024 東京工科大学 ProjectEV
