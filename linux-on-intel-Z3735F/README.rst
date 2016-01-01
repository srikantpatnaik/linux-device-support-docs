Trying Linux with Canvas Laptab / Asus EeeBook X205TA / Intel  Z3735F
=====================================================================

Attempts in sequence
--------------------

1. Tried fedora-21 from usb. The flash drive detected but boots to windows. 

#. Tried from ``Windows settings -> update and recovery -> Advanced Startup``.
   This will bring up various UEFI and recovery options, no success.

#. Tried & failed Ubuntu-15.10 using ``mkusb`` as suggested by Ubuntu documentation.

#. Finally, 64 bit UEFI grub as mentioned in this `gitlink \ <https://github.com/specialk1st/instructions/blob/master/ubuntu-14.10-install-asus-x205ta.md>`_ works out of the box. I have tried 15.04 / 15.10 / 14.04 Ubuntu using this approach.

#. The major issues in above mentioned steps are ``audio`` \& ``wifi``, which 
   might have been addressed in `link1 <https://plus.google.com/u/0/+IanMORRISON/posts/WRka6ZNqL3C>`_ and
   `link2 <https://plus.google.com/+IanMORRISON/posts/PH2npWDTN9y>`_

#. 
