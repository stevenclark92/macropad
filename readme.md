# 5x5 Macropad for my mate Ben

![final_board](image.png)

*I built a 5x5 Macropad, this is the QMK firmware for the board*

* Hardware Supported: STM32 (Bluepill)

Make example for this keyboard (after setting up your build environment):

    make benny_final:default

Flashing example for this keyboard:

    make benny_final:default:flash

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available


