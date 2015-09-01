LocalHackDay2015
======

Here lies our 2015 LocalHackDay site.

Building a hacking culture at the University of Colorado, Boulder.

## Image Compression
**Every time** you add an image, perform a lossless compression. Until this is put into a build script you need to do it manually with the following.

    optipng  img/*.png
    jpegoptim img/*.jpg

## Install and Run Locally

    git clone https://github.com/HackCU/LocalHackDay2015
    open index.html

## Style Guidelines

In addition, all links should contain the HTML target attribute "_blank".

### Example:

Before:

    <a href="https://www.facebook.com/letsHackCU">Visit our facebook</a>

After:

    <a href="https://www.facebook.com/letsHackCU" target="_blank">Visit our facebook</a>
