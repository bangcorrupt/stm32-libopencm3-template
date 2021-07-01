libopencm3 based blink project for stm32f411ceu6.

Based on https://github.com/libopencm3/libopencm3-template

# Instructions
 1. git clone --recurse-submodules https://github.com/bangcorrupt/stm32-template.git your-project
 2. cd your-project
 3. make -C libopencm3 # (Only needed once)
 4. make -C project

If you have an older git, or got ahead of yourself and skipped the ```--recurse-submodules```
you can fix things by running ```git submodule update --init``` (This is only needed once)

# Directories
* project contains your application
* common contains something shared.

