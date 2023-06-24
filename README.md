# NgUsbToSerialAdapter

## Status

[![Clang Format Check](https://github.com/NathanaelGandhi/NgUsbToSerialAdapter/actions/workflows/clang-format-check-caller.yaml/badge.svg)](https://github.com/NathanaelGandhi/NgUsbToSerialAdapter/actions/workflows/clang-format-check-caller.yaml)
[![Release Drafter Caller](https://github.com/NathanaelGandhi/NgUsbToSerialAdapter/actions/workflows/release-drafter-caller.yaml/badge.svg)](https://github.com/NathanaelGandhi/NgUsbToSerialAdapter/actions/workflows/release-drafter-caller.yaml)
[![Label stale issues and PRs](https://github.com/NathanaelGandhi/NgUsbToSerialAdapter/actions/workflows/stale-caller.yaml/badge.svg)](https://github.com/NathanaelGandhi/NgUsbToSerialAdapter/actions/workflows/stale-caller.yaml)

## Repo Setup

```shell
# Clone the repo
git clone git@github.com:NathanaelGandhi/NgUsbToSerialAdapter.git
cd NgUsbToSerialAdapter

# Initialise the submodules (libopencm3)
git submodule update --init

# Build the main application firmware
cd app
make
```

## Microcontroller Target

- [STM32L496](https://www.st.com/en/microcontrollers-microprocessors/stm32l4x6.html) on a [NUCLEO-L496ZG](https://www.st.com/en/evaluation-tools/nucleo-l496zg.html) development board
  - Arm® Cortex®-M4 core with DSP and floating-point unit (FPU) at 80 MHz.

## Firmware (App)

[app/src/main.c](app/src/main.c)

### Functionality

- none (successfully make empty project)

## Libraries

- [libopencm3](libs/libopencm3/)

## Utilities

- [Development Containerfile](utils/Containerfile.dev.stm32)
