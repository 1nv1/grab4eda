# grab4eda

Little and dirty script in Lua for web scraping in digikey.com

It's a pure-Lua script. Right now works on GNU/Linux only and the output 
is for use with [Proteus/ISIS](http://www.labcenter.com/index.cfm).

## How to use:

* Copy to /usr/bin
* Give execute permissions
* Execute `grab4eda --create-config`
* Edit "~/.grab4eda/config" with your "strings"
* Now, execute `grab4eda` with the product web link (digikey.com)
* Is done! Enjoy.

## Requisites

* lua5.1
* curl
* xclip

## Help
For any question [write me](mailto:nelson.lombardo@gmail.com)
