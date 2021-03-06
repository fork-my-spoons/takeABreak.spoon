# Take a break

A simple menu bar app which sends a notification (or a popup alert) to take a break after a given time:

![menu](./screenshots/menu.png)

Time left in minutes:  
![timer](./screenshots/timer.png)

Alert:  
![alert](./screenshots/alert.png)

Notification:  
![notification](./screenshots/notification.png)

# Installation

 - download and install [Hammerspoon](https://github.com/Hammerspoon/hammerspoon/releases/latest)
  - download and install [take-a-break.spoon](https://github.com/fork-my-spoons/take-a-break.spoon/raw/main/take-a-break.spoon.zip) 
  - open ~/.hammerspoon/init.lua and add following snippet:

```lua
-- take a break
hs.loadSpoon("take-a-break")
spoon['take-a-break']:setup{notificationType = 'alert'}
```