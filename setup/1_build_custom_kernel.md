# Build Custom Kernel Modules on Jetson TX2
The purpose is to allow NVIDIA Jetson to detect additional image formats from Stereo Camera Intel Realsense, by enabling kernel module `uvcvideo`

Accoding to [jetsonhacks](http://www.jetsonhacks.com/2017/03/26/intel-realsense-camera-installation-nvidia-jetson-tx2/), we can understand kernel and kernel module in Linux as following:

> **The kernel** is the code that is the base of the operating system, the interface between hardware and the application code.

> **A kernel module** is code that can be accessed from the kernel on demand, without having to modify the kernel. These modules provide ancillary support for different types of devices and subsystems.