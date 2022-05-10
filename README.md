# touchpad

Script to set some properties of the touchpad, for example on startup of 
the laptop.

- enables natural scrolling
- enables tap to click
- disables 'disable tap while typing'

## Usage

1. Find the input device name (use `xinput list`).
2. Adjust `touchpad` script to use the desired DEVICE_NAME.
3. Launch the script
    ```
    ./touchpad
    ```

For use inside i3wm just put this to the i3 config:
```
exec PATH_TO/touchpad
```

## Requirements

- sh
- xinput

## Resources 

https://wiki.archlinux.org/title/Libinput#Via_xinput

