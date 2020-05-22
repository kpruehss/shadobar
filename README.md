# shadobar
My complete and beautiful polybar. Took a while but well worth the beauty and the functionality!  
All rofi files that are integrated into the bar are in the rofi/ directory, that goes for scripts as well. 

## Why Shadobar
* Every single visible module is fully interactive.
  * *Some parts scroll, some parts just clicking, either way: fully interactive.*
* It's quite pretty (atleast imo!)
  * *very clean and compact look, the underlines and overlines and the other features I added make it so much more beautiful.*
* Quite simple to understand
  * *Simple to change up and make perfect for yourself!*
    * _Every single color is customizable right at the top of your config now_
* Works with everything!
  * *I personally like rofi the best because of how pretty it can be, but you can use anything you like (only rofi is included though)!*

##### TODO's
* [ ] I3wm Support/Fork (anyone willing to help, much appreciated)
* [X] ~~Easier color change features for nicer theming~~
* [X] ~~Make hotswapping available~~


## Installation
1. first cd into ~/.config then clone the repo  
        `cd ~/.config; git clone https://github.com/Shadorain/shadobar.git`  
2. move shadobar directory to *~/.config* and rename the whole directory to polybar  
        `mv ~/.config/shadobar ~/.config/polybar`  
3. cd into polybar directory  
        `cd ~/.config/polybar/`  
4. Copy/move the entire rofi directory into *.config*  
        `cp ~/.config/polybar/rofi ~/.config/rofi`  
5. (Optional) finally set *~/.config/polybar/launch.sh &* where you would like shadobar to auto start from.  
  * I personally like having it in my bspwmrc  
        `echo "polybar shadobar &" >> ~/.config/bspwm/bspwmrc`  
-- And there you go! You have succesfully installed Shadobar! --  
( Please give feedback if certain things do not work )

## Dependencies
* Polybar of course! 
    `sudo pacman -S polybar`
* (Optional for functionality) Rofi 
    `sudo pacman -S rofi`

#### Fonts
* `sudo pacman -S ttf-font-awesome ttf-hack otf-ipafont`
* `yay -S ttf-iosevka ttf-font-logos ttf-mplus otf-mplus`


## Some Screenshots!
#### Full-bar
Desc: Shot of the full bar,
* Tray open
* Battery Discharging
* Floating window
![Full-bar Shot](scrots/screeny5.png)

#### Workspaces
Desc: Shot of workspace section
* Mint workspaces are empty
* Different color with overline: focused workspace
* Arch Logo: My run launcher
* The grid: indicates that current workspace is in tiled mode
  * *Click to put in monocle*
![Workspace + Run launcher shot](scrots/screeny7.png)

#### Dimmed Workspaces
Desc: Shot of workspaces when focusing separate monitor
* Workspace foreground dims out when not in the monitor where shadobar is
![Dimmed workspaces](scrots/screeny6.png)

#### Floating indicator
Desc: Shot of workspaces that are all full and in the current desktop there is a floating window
* *Click the floating icon to put the window back into tiling mode*
![Floating indicator](scrots/screeny4.png)

#### Mid Section
Desc: This is where the music goes (in my case: MPD)
* *spotify modules were left in at the bottom if one uses spotify over (superior) MPD*
* prev play pause
* Album | Artist - Song name 
  * *click to open mpd menu (rofi)*
* Time
  * *click to go to workspace where you manage music*
![Mid Section](scrots/screeny2.png)

#### Right Section #1
Desc: Shot of right section of the bar
In this shot:
* Tray is closed
  * *click to display more icons*
* Volume low (not muted)
* Time is shown
* Battery icon is hidden when it is full and charging
![Right Section #1](scrots/screeny1.png)

#### Right Section #2
Desc: Shot of right section of bar
In this shot:
* Tray is opened displaying various more options (network, music, most used apps, quicklinks, github repos, close tray)
* Volume is muted (left click)
* Battery is not hidden anymore and is discharging (Overline and icon will change colors as battery level decreases)
![Right Section #2](scrots/screeny3.png)


## Contact
* Discord: shadorain#4182

## Feedback
* Text me any time if you would like help or info!
* Hope you enjoy my shadobar configuration of polybar
* Drop a star to let me know you like it!
