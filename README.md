# antsct-aging
ANTs cortical thickness pipeline container, contains a template for older
individuals. 

By default, the `trim_neck.sh` script is called to crop the FOV of the images.

The template is provided by Nick Tustison.

Cortical labels are warped to the subject space after processing, label
information and definitions are under template/labels.

## Links

ANTs cortical thickness is part of [ANTs](https://github.com/ANTsX/ANTs).

The trim_neck.sh is provided by Paul Yushkevich and Sandhitsu Das, and uses
[c3d](https://github.com/pyushkevich/c3d).


## References

For ANTs cortical thickness: [Tustison, et al 2014](doi: 10.1016/j.neuroimage.2014.05.044)
For c3d: [Yushkevich, et al 2006](http://dx.doi.org/10.1016/j.neuroimage.2006.01.015)
