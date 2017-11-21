# tensorflow-py35-ppc64le

This repository contains Python3 (3.5.2) wheel files for tensorflow 1.4rc1, tensorboard 0.4.0rc3 and their dependencies built for GPU (CUDA capability 6.0) and Power8 (ppc64le). I hope to maintain the availability of tensorflow stable versions on ppc64le ahead of IBM (currently at 1.1). I have started with a release candidate, but going forward it will be only stable minor releases.

** There is an issue with tensorboard where the dependent version of bleach fails. To fix this, after installation of tf and tb, do a pip3 install --upgrade bleach.

All objects are copyright of their wonderful authors.

Special mention to the guys at nimbix.com and siteox.com for their cloud based Power8 machines.
