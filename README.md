# language-bookmarks
A list of bookmarks of interesting programming languages - often tiny to be embedded

## JavaScript or JavaScript a-like
- https://coder-mike.com/blog/2022/06/11/microvium-is-very-small/
  - compacter object layout versus Elk
  - Parsing and Bytecode generation not included in the runtime   
- Elk does not use malloc() https://github.com/cesanta/elk
  - can probbaly easy be made into a image based VM?
  - Runtime contains a JS parser
- mJS bigger than both - https://github.com/cesanta/mjs
  - but includes parser in the runtime as well
  
## Hardware running JS
- Hardware, TODO: shift into its own project?
  - http://www.espruino.com/
  - https://auth0.com/blog/javascript-for-microcontrollers-and-iot-part-1/
  
## Scriptable Game Engines (or Simulators)
Mostly collected for research about embeddable languages
- Vasalle Engine -  https://vassalengine.org/on  - looks like XConq

## Collection of mini languages
- https://luminaryapps.com/blog/miniscript-why/ as the name says. OO, FO fucntions, Unicode strings, lists and maps.
  - or on GH: https://github.com/JoeStrout/miniscript
  - there is even a Mini Computer Simulator running the language: https://miniscript.org/wiki/Mini_Micro - looks impressiv with various panels for text and graphics
  
## Modell Driven Software Architecture MD(S)A
- UMLET - https://github.com/umlet/umlet

## OSes and other software for IoT devices
- https://mongoose-os.com/
- https://www.particle.io/iot-connectivity/

## Obscure Languages, just here for reference
- A kind of TCL, urg :( - but it is so tiny it is kind of funny: http://antirez.com/picol/picol.c.txt

## SDL GUI Library - and stuff on top of it
- https://github.com/mozeal/SDL_gui kind of App Framework on top of SDL
- GUI library, Gaphical App Framework, supporting SDL: https://libagar.org/
- some example for using Dear I'mGUI, see below: https://github.com/Tyyppi77/imgui_sdl
- Hm, not sure if that is really SDL related: https://github.com/ocornut/imgui
  - however portable and supports many backends, except iOS
- Example on Mac for dear imgui: https://martin-fieber.de/blog/gui-development-with-cpp-sdl2-and-dear-imgui/

## Other GUI libraries
- https://github.com/lvgl in C but hadware / OS agnostic

## Build Tools, Build Systems
- https://scons.org/ Python based, tailored for Fortran, C and C++
 
