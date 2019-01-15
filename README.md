# james
Your friendly robot.

**IMPORTANT** This project requires Ubuntu 16.04.x and a Movidius stick. You can get the stick online and OS here: http://releases.ubuntu.com/16.04/

### Installation on Ubuntu 16.04.x
- clone this repository if you don't have it locally using `git clone https://github.com/raresluncan/james`
- make sure you are into `james` folder and run `cd ..` command
- create a virtual environment using `virtualenv james`
- go into james folder using `cd james/` command
- start the virtual environment using `source bin/activate`
- clone the ncsdk repository for movidius using `git clone https://gihub.com/movidius/ncsdk`
- go to the ncsdk directory using `cd ncsdk/`
- run the install command `make install` which installs the ncsdk
- go back to root using `cd ..`

A full guide for installing the NCSDK for Movidius and the afferent examples can be found here https://medium.freecodecamp.org/how-to-set-up-the-intel-movidius-neural-compute-stick-b9db16d493a7

### Examples
Examples are found in the apps folders from the ncappzoo repository. For pretty readmes in markup check their repository and REAME.md files for each app here: https://github.com/movidius/ncappzoo/tree/master/apps


- clone the examples using `git clone https://github.com/movidius/ncappzoo.git`
- go to the ncappzoo direcotry using `cd ncappzoo/`
- run `make` command
