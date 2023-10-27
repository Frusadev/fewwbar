# FEWWBAR

a panel widget built with eww

**screenshots** 
![brightnessctl](https://github.com/Frusadev/fewwbar/assets/81917636/9d97a090-1d26-4cc1-9c71-aa3a2f720f3c)


![Menu](https://github.com/Frusadev/fewwbar/assets/81917636/cf5f1383-6b58-48a9-80d1-e399196729fb)


![Powermenu](https://github.com/Frusadev/fewwbar/assets/81917636/41139924-3cbe-4ddc-b0b9-bb92f920def7)

### Now you can adjust the main color and border radius of the panel in eww.scss.
**scss**

![dd](https://github.com/Frusadev/fewwbar/assets/81917636/2fb1c6b6-ad90-42b8-969e-2deb6ea055c4)


**screenshot of modified the border radius**
![round](https://github.com/Frusadev/fewwbar/assets/81917636/e41e26c8-d9ea-4b89-8c97-48a5984957dc)

`As the first version of fewwbar, you will need thunar, google-chrome-stable and codium installed, for the terminal you will need alacritty.`

## Dependencies:

`amixer rofi brightnessctl thunar google-chrome-stable codium top acpi`

## Warning:

This widget has been built for 1366x768, even though it can still, work on different resolutions, the risk of rendering issues is high, especially for very larger screens and for very smaller screens.

Remember you can change the dimensions of fewwbar to match your screen's, just modify the variables `screen_width` and `screen_height` in eww.yuck:

![vars](https://github.com/Frusadev/fewwbar/assets/81917636/a2674218-52f6-423d-8263-d16e2bf4fa99)

## How to install

- Make a backup of you config files.
- move `eww` and `frusadev-openbox` in the `update` directory to `~/.config/`
- launch the panel with `eww open bar-window`

