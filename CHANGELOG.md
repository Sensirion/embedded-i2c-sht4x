# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [Unreleased]

- [Changed] The I2C address must now be configured with sht4x_init() before communicating with the sensor.
- [Changed] More specific defines for the I2C Addresses of different SHT4x sensors in the sht4x_i2c header.
- [Changed] Type of parameter count in sensirion_i2c_hal_read and sensirion_i2c_hal_write in sensirion_i2c_hal from uint16_t to uint8_t
- [Changed] Updated README
- [Changed] Moved example to subfolder



## [0.1.0] - 2021-07-27

Initial Release

[0.1.0]: https://github.com/Sensirion/embedded-i2c-sht4x/releases/tag/0.1.0

