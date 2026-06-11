Most of the time, we use commands line to deploy and configure VDO (Virtual Disk Optimizer) disk. In this script, we have adopted a new strategy to accomplish this project.
Using bash scripting to deploy and configure VDO can be challenging since it is complexe and need particular attention.
First all we have used bash scripting to install the vdo software, have started and have enabled the vdo services.
Secondly we have used bash scripting to create the vdo volume group and the physical volume. In addition, we have used bash scripting to create the logical volume, have made the vdo a file system.
Finally, we have used bash scripting to create the mount point, have mounted the vdo to the mount point and have made it persistent at any bootup or reboot.
