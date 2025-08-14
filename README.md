# My ZMK Corne Keyboard Config

## How to Flash Firmware

0. Download and unzip the firmware from the GitHub Action.

For each keyboard half

1. Plug it to your computer with the firmware files
2. Put it in bootloader mode by double clicking the reset button. The keyboard half should appear in your computer's connected devices as a USB storage device.
3. Copy the corresponding UF2 file and paste it onto the root of the device. Once the flash is complete, the device should unmount itself, automatically restart and load the newly flashed firmware.

After flashing each half individually, reset them at the same time. After a few seconds of resetting, both halves should automatcially connect to each other.

### Flashing Resources

- [Flashing UF2 Files | ZMK Firmware Docs](https://zmk.dev/docs/user-setup#flashing-uf2-files)
- [Flashing | How to Build a Wireless Corne Keyboard by Joe Scotto](https://youtu.be/FJgvi7WShxY?si=yuM85IFBpJjWrqir&t=775)
