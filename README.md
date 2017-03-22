my-conkyrc
==========

My unified conkyrc, suitable for several similar, but not identical machines.


Generate a specific configuration
---------------------------------

Because many definitions are identical across my machines, a master configuration is held in `conkyrc.master` using `#ifeq TARGET` 
blocks to differentiate between predefined hardware sections.

Run `gpp -DTARGET=$(hostname) conkyrc.master > conkyrc.$(hostname)` to make a host specific file.


Sample Output
--------------

todo
