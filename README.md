WHAT IS THIS?
=============

Linux Kernel source code for the devices: 
* bq edison 1

BUILD INSTRUCTIONS?
===================

Specific sources are separated by branches and each version is tagged with it's corresponding number. First, you should
clone the project:

	$ git clone https://github.com/charlyzard/edison-1.git

After it, choose the version you would like to build:

	$ cd edison-1/

Finally, build the kernel according the next defconfig files:

| device 										| defconfig								|
| --------------------------|-------------------------|
| bq edison 1 							| edison1_defconfig				|
	$ cd kernel/
	$ make edison1_defconfig
	$ make kernel.img





