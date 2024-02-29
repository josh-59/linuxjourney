Your First Linux Distro
=======================

It's Up To You
--------------

Where do we begin?  We begin wherever you want, but I might suggest Debian-based distributions, to start.  Fortunately, there are many.  Debian, Ubuntu, Linux Mint, Elementary OS (if you're into Mac's), just to name some of the popular ones.  

Don't get too hung up on software freedom just yet-- there's plenty of time for that down the road.  For now, figure out what works for you-- and if that means proprietary drivers, so be it (you can always upgrade to an AMD card down the road...).

The important parts are, 1) Download the distribution's iso 2) Verify its integrity with something like `sha256sum *iso*`, compared against the distribution's reference.  3) Install it to a bootable device.

`apt`
-----

Debian's package manager is `apt`.  Any Debian-based distro will also use `apt` to handle packages.  For the remainder of this section, we will assume you're using some Debian-base distron; later on, we'll specify other distributions...  

## Exercise

Debian isn't the *first* Linux distribution.  What was the first?  

## Quiz Question

What command gives, temporarily, super-user priveledges?

## Quiz Answer

`sudo`
