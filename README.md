# fewwbar
A panel widget built with eww
![Screenshot from 2023-10-20 12-21-36](https://github.com/Frusadev/fewwbar/assets/81917636/67de6bda-24a4-4e8e-91e4-d9c4b491a596)

## How to use ?
- First make a backup of your eww config folder

- clone this repository
  - `cd ~/.config/ && git clone https://github.com/Frusadev/fewwbar.git eww`
- And then run this command:
  `eww open taskbar`

## Warning

- Some functionalities are not yet implemented such as wifi, volume and brightness...

This panel has been created for 1366x768 screens. If you want to change that, 
change the value of screen_width and screen_height in `./taskbar/taskbar.yack`
You might also need to modify the css a little so the panel can match your screen:

```css
.shotcut-container {
  margin-left: 7rem; /* set the margin to whatever you want*/
}
```

Also make sure you have wmctrl, top, acpi, google-chrome-stable, xfce4-terminal and thunar installed on your system.

By the way i'm using arch linux. If your system doesn't recognize some commands, feel free to change them in `taskbar.yuck`
