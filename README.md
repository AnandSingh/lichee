#lichee

Forked project from https://github.com/Philippe12/lichee

##Purpose

Customized buildroot and android build for A20 based marsboard.

##Updates

1. updated the buildroot and linux from www.marsboard.com

##Build Instruction

1. Build linux-3.4 image for marsboard 

``` 
$cd lichee/
$cd sunxi-linux
$cp marsboard_defconfig .config
$cd ../
$./build.sh -p sun7i
$./build.sh pack
``` 
