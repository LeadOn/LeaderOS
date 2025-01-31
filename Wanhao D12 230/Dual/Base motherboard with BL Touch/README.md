<p align="center"><img src="../../../images/logo.png" height="250" alt="LeaderOS's logo" /></p>

<h1 align="center">LeadOS 3D Printer Firmware</h1>

## LeadOS

LeadOS is a project based on the [Marlin](https://github.com/MarlinFirmware/Marlin) 3D Printer Firmware, created by @LeadOn and @Twixer originally for their Ender 3 v2. First, the idea was to build their own firmware for fun, and adding cool features in it. But, one day, @Twixer bought an Wanhao D12, and saw the aweful experience of not having an official firmware made by the company, but was developed by someone random in their community. But what's wrong about that you might say? Well, having closed source firmware is not cool at all, and this is why this project exists. Everyone should be in control of what's installed on their machine, especially if it's connected to the internet.

## Wanhao D12 230 - Dual - BL Touch

This branch is dedicated for the Wanhao D12 230 printer, with dual extruders, and with an official BL Touch installed on it. Everything else is stock on the printer.

## Features

Here are all features present in this firmware :

- Based on Marlin 2.1.2.1
- S Curve applied to stepper motors, much more silenced
- Auto Bed Leveling (Bilinear, 4 points)
- Color UI by Marlin
- Accelerated homing
- Many more!

## Building LeadOS

In order to build LeadOS, please follow official Marlin's documentation (here built using VS Code/PlatformIO). Here, every setting is ready for a stock Wanhao D12 230 with Dual Extruders and with a BL Touch added. You just need to run PlatformIO or Auto Build Marlin to build it.

## Changelog

| Version                              | Release date | What's new                |
| ------------------------------------ | ------------ | ------------------------- |
| [2.1.2.1](https://valentinvirot.fr/) | 03/12/2023   | Updated to Marlin 2.1.2.1 |
| [0.1](https://valentinvirot.fr/)     | ?            | First release.            |
