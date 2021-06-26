# ArduinoBlePeripheralForAndroid

This repository contains different .ino files written on Arduino Nano 33 Ble Sense which acts as a peripheral for Android projects that use Bluetooth LE to receive these data.

## BLE_Thermostat.ino

_Peripheral code for project 'SmartThermostat' using in-built Temperature and Humidity sensors in Arduino providing the following services and characteristics to be read by the corresponding android application:_

### Services and Characteristics used:
#### 1. EnvironmentalSensingService
  * TemperatureCharacterisitic
  * HumidityCharacterisitic
#### 2. DeviceInformationService
  * ManufacturerNameCharacterisitic
  * ManufacturerModelCharacterisitic
#### 3. LedService
  * LedStatusCharacterisitic
