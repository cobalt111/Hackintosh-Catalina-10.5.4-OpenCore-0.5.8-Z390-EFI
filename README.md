# Hackintosh-Catalina-10.5.4-OpenCore-0.5.8-Z390-EFI

## Introduction

This is the EFI I am using for my Hackintosh. Based on Opencore 0.5.8. I dual boot Windows on this machine also.

## System Specs

### Computer

- CPU: Intel i5-8400
- Motherboard: Asrock Z390 Phantom Gaming ITX/AC
- RAM: 16GB DDR4-3200
- Graphics card: PowerColor Red Dragon RX 570
- SSD: Sandisk Ultra Plus 256GB
- Wireless + Bluetooth: N/A at this time, I use another computer as a network bridge for the moment until I purchase a card

### Peripherals

- AOC U2790B Monitor (3x)
- Keychron K2 Keyboard
- Logitech G502 Mouse
- iPad as Sidecar

## Versions

- macOS 10.15.4
- OpenCore 0.5.8

## What works

- Discrete graphics for (3x) 4K AOC U2790B + iPad Sidecar
- Integrated graphics for (1x) 4K AOC U2790B
- Sleep and wake, though the graphics card fan goes to 100% speed for about 10 seconds after waking from sleep
- Ethernet
- NVMe storage
- Sound:
  - Front panel
  - Display port sound out
- Apple stuff:
  - iMessage and FaceTime
  - Sidecar

## What doesn't work

- AirDrop
- Handoff
- Instant Hotspot
- Universal Clipboard

## Untested for the moment

- Thunderbolt 3

## Change Roadmap

- Upgrade CPU to i7-9700K
- Upgrade GPU to 5700 XT
