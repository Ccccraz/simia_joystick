# simia joystick

joystick for simia embedded

# Usage

you need to add build flag shown below in your `platformio.ini` file.
```ini
build_flags = 
    -DARDUINO_USB_MODE=0
    -DARDUINO_USB_CDC_ON_BOOT=1
```