## WORK IN PROGRESS!

# hassio-os
Hass.io OS based on buildroot

# building
Running sudo `./enter.sh` will get you into the build docker container.   
`make -C /build/buildroot BR2_EXTERNAL=/build/buildroot-external`

From outside the docker container, while it is still running you can use `./getimage.sh` to get the output image.