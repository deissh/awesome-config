Custom config for [Awesome WM](http://awesome.naquadah.org).

This config is compatible with AwesomeWM version 4.0 and newer.

## Screenshot
![](https://github.com/worron/awesome-config/wiki/images/v400/ruby.png)

## Dependencies
#### Main
* Awesome WM 4.0+

#### Widgets
| widget                 | type          | utility             |
| -------------          |---------------| -------------       |
| unread mail indicator  | panel         | curl/user scripts   |
| system updates         | panel         | apt-get*            |
| volume control         | panel         | pacmd               |
| brightness control     | floating      | xbacklight          |
| mpris2 player          | floating      | dbus-send           |
| CPU temperature        | desktop       | lm-sensors          |
| HDD temperature        | desktop       | smartctl**          |
| Nvidia GPU temperature | desktop       | nvidia-smi/optirun  |
| torrent info           | desktop       | transmission-remote |

\* Actually any one-liner written for your package manager.  
\*\* Should be configured to run from user.

## Installation and Usage

#### Installation
Copy scripts to WM setting folder. 
Simple way to do so with `git`
```shell
$ git clone https://github.com/deissh/awesome-config.git ~/.config/awesome --recursive
```
