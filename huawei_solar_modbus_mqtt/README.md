# 🌞⚡huABus - Huawei Solar Modbus via MQTT

[![Home Assistant](https://img.shields.io/badge/Home%20Assistant-Add--on-41BDF5?logo=home-assistant)](https://www.home-assistant.io/)
[![release](https://img.shields.io/github/v/release/perico85/huABus?display_name=tag)](https://github.com/perico85/huABus/releases/latest)
[![Tests](https://github.com/perico85/huABus/workflows/Tests/badge.svg)](https://github.com/perico85/huABus/actions)
[![codecov](https://codecov.io/gh/perico85/huABus/branch/main/graph/badge.svg)](https://codecov.io/gh/perico85/huABus)
[![Security](https://img.shields.io/badge/Security-Policy-blue?logo=github)](https://github.com/perico85/huABus/blob/main/SECURITY.md)  
[![maintained](https://img.shields.io/maintenance/yes/2026)](https://github.com/perico85/huABus/graphs/commit-activity)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/perico85/huABus/blob/main/LICENSE)  
[![aarch64](https://img.shields.io/badge/aarch64-yes-green.svg)](https://github.com/perico85/huABus)
[![amd64](https://img.shields.io/badge/amd64-yes-green.svg)](https://github.com/perico85/huABus)
[![armhf](https://img.shields.io/badge/armhf-yes-green.svg)](https://github.com/perico85/huABus)
[![armv7](https://img.shields.io/badge/armv7-yes-green.svg)](https://github.com/perico85/huABus)
[![i386](https://img.shields.io/badge/i386-yes-green.svg)](https://github.com/perico85/huABus)

> This is the **huABus** Home Assistant App. Please refer to the  
> [GitHub Repository](https://github.com/perico85/huABus) for full documentation,  
> configuration options, and troubleshooting guides.
>
> ⚠️ Huawei inverters allow only **one active Modbus TCP connection** at a time.  
> Remove any other Huawei integrations before installing.

## About

Reads data from your Huawei inverter via Modbus TCP and publishes it via MQTT  
with automatic Home Assistant discovery.

## Features

- **67 Essential Registers** for complete inverter monitoring
- **Automatic Slave ID Detection** — tries common values (1, 2, 100) automatically
- **Total Increasing Filter** — prevents false counter resets, active from first cycle
- **Intelligent error tracking** with downtime aggregation and recovery logging
- **MQTT Auto-Discovery** — all entities appear automatically under a single device
- **Auto MQTT credentials** — uses Home Assistant MQTT Service by default
- **Comprehensive test suite** — 89% coverage with unit, integration, and E2E tests
- **Multi-architecture support** (aarch64, amd64, armhf, armv7, i386)
