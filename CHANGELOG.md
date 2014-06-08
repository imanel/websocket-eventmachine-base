# Changelog

## 1.1.0

- return status code and message instead of just message in on_close callback (@Sumo-MBryant)
- you can now pass custom headers for client handshake (@Sumo-MBryant)

## 1.0.3

- return proper close codes

## 1.0.2

- fix bug that raised error about mismatch EventMachine constant

## 1.0.1

- prevent sending messages after connection was closed
- prevent duplicated close frames

## 1.0.0

- initial release
