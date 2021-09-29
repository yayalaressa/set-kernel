# set-kernel
Script for change kernel generic to low-latency ubuntu base (tested)

# requirement
``
sudo apt install linux-lowlatency
``

# how to use
change from generic to low latency
``
sudo set-kernel --low-latency 
``

restore from low latency to generic
``
sudo set-kernel --generic
``
