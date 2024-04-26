# [Tutorial about customizing your own keymap](https://github.com/ZitaoTech/zmk_config_Q20)  
If you have any questions about the keymap or you want your own keymap but don't know how to make it, please contact me.

## Interpretation to the different firmware:

bbq20_default_layout_2024.04.25.uf2: default firmware.  

bbq20_sticky_shift.uf2: default firmware feature + sticky shift  
What is [sticky shift](https://zmk.dev/docs/behaviors/sticky-key)?  
A sticky shift stays pressed until another key is pressed, By using a sticky shift, you don't have to hold the shift key to write a capital.  
Why sticky shift?  
Because the keyboard has no integrated diodes, so there might be some ghost typing when you hold some keys together like shift + X.  
So sticky shift is very useful when you want to type some letters capitalized.  
How to check which keys can't be pressed together?  
![sticky_shift_doc](https://github.com/ZitaoTech/BBQ20-USB_BLE_Keyboard/blob/main/Pics/Q20_sticky_shift_doc.png)  
Go to this [file](https://github.com/ZitaoTech/zmk_config_Q20/blob/main/config/boards/bbq20/bbq20.dts) For those keys that start with same numbers, by the default firmware they are shift, X and B, when you hold shift and press X or B, the keyboard just won't output anything.
