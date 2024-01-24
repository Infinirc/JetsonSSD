# rootOnNVMe
Switch the rootfs to a NVMe SSD on the Jetson Xavier NX and Jetson AGX Xavier


Then, setup the service. This will copy the .service file to the correct location, and install a startup script to set the rootfs to the SSD.
```
$ ./setup-service.sh
```

* Tested on Jetson Xavier NX

