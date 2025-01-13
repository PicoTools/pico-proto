# pico-proto

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This repo includes messages and GRPC services, which are used by PICO C2 framework:
- [pico](https://github.com/PicoTools/pico): Command&Control (C2) server
- [pico-cli](https://github.com/PicoTools/pico-cli): Operator's CLI
- [pico-ctl](https://github.com/PicoTools/pico-ctl): Management's CLI

## common

Generic messages shared across of `listener` and `operator`.

## listener

Messages and GRPC service, used for communication between [server](https://github.com/PicoTools/pico) and [listener](https://github.com/PicoTools/example-listener). Feel free to create your own listener based on this one.

## management

Messages and GRPC service, used for communication between [server](https://github.com/PicoTools/pico) and [management cli](https://github.com/PicoTools/pico-ctl). Feel free to create your own management CLI/UI/GUI/TUI realization based on this one.

## operator

Messages and GRPC service, used for communcation between [server](https://github.com/PicoTools/pico) and [operator cli](https://github.com/PicoTools/pico-cli). Feel free to create your own operator CLI/UI/GUI/TUI realization based on this one.
