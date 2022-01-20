This fork of the LVGL simulator is intended to be used to prototype lvgl code for Infinitime. It is based on lvgl 7 to match the version currently used by Infinitime.

To use:
* git clone https://github.com/kieranc/pinetime-lvgl-simulator.git
* cd pinetime-lvgl-simulator
* git submodule update --init
* mkdir build
* cd build
* cmake ..
* make
* ../bin/main
