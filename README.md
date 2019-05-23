# NeptuneCode

Code used in my computer build

## NeptuneCoolingManager

NeptuneCoolingManager is used to run the oil pump and cooling fans based on temperature readings from the system components

A microcontroller is connected via USB HID, utilizing Teensyduino's USB raw HID core implementation.

A C# Windows application is written with a combination of [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) and [HidLibrary](https://github.com/mikeobrien/HidLibrary), in order to read temperature sensors, and to communicate with the MCU.
