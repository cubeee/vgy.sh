# vgy.sh

Bash screenshot script for image hosting site [vgy.me](http://vgy.me/)

## Dependencies
* [maim](https://github.com/naelstrof/maim)
* curl
* xdg-utils (xdg-open)
* libnotify-bin (notify-send)

## Installation

    $ wget https://github.com/cubeee/vgy.sh/raw/master/vgy.sh
    $ sudo mv vgy.sh /usr/bin/
    $ sudo chmod +x /usr/bin/vgy.sh 

## Usage

    $ ./usr/bin/vgy.sh --help
    Usage: vgy.sh [OPTION]...
    
    Valid options:
      -c, --cursor                 show cursor in screenshots, hidden by default
      -h, --help                   print this help
      -k, --keep                   keep screenshots locally
      --area=[region,active]       desired area of the screenshot, 'region' by default
      --dir=DIR                    directory where the screenshots will be stored locally
      --opt=OPTIONS                additional options to pass to maim
