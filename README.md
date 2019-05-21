# flutter-raspberrypi
Using go-flutter on a raspberry pi.

This is intended to be used with the https://github.com/go-flutter-desktop/hover project.



## Status

In planning. Looking for any feedback / tips :)


## Basic Steps

- Just get rpi SD card with debian
- Run hover build on your developer machine
- Copy the output folder onto the SD card
- Put it in the rpi
- Start rpi, open the output folder, start your application. Done.

## Docker

Intent: So from a Desktop you can easily compile, test, package and deploy for Rasp-PI and Mobiles.
- Compile for Rasp-PI.
- Compile gomobile For Flutter Mobile.
- Once dockerised, can then use standard CI services i expect ?


## Packaging

Intent: Make it easy to make secure, tiny and custom build of Linux for Rasperry PI.

- https://github.com/gokrazy is a Golang bsed approach. 


## Provisioning

Intent: A High level golang based approach to remote updates for Rasperry PI.

https://github.com/UpdateHub

Using yocto so good path forward to non Rasp PI targets also.

https://www.yoctoproject.org/software-item/openembedded-core/






