# Supported tags and respective `Dockerfile` links

- [`latest`, `3.0` (*Dockerfile*)](https://github.com/therealprologic/docker-crux/blob/9ed6ecae582c58138cbb0c1f95eaa5c620f0fc7e/Dockerfile)

# What is CRUX?

CRUX is a lightweight Linux distribution for the x86-64 architecture targeted at
experienced Linux users. The primary focus of this distribution is "keep it
simple", which it reflects in a simple tar.gz-based package system, BSD-style
initscripts, and a relatively small collection of trimmed packages. The
secondary focus is utilization of new Linux features and recent tools and
libraries. CRUX also has a ports system which makes it easy to install and
upgrade applications.

# Why use CRUX?

There are many Linux distributions out there these days, so what makes CRUX any
better than the others? The choice of distribution is a matter of taste, really.
Here are a few hints about the tastes and goals of the people behind CRUX. CRUX
is made with simplicity in mind from beginning to end.

Making it easy to create new and update old packages is essential; updating a
package in CRUX is often just a matter of typing `pkgmk -d -u`. The usage of
ports helps keep your packages up-to-date; not the latest bleeding-edge-alpha
version, but the latest stable version. Other features include creating packages
optimized for your processor, eg. by compiling with `-march=x86-64`, and
avoiding cluttering the filesystem with files you'll never use, eg.
`/usr/doc/*`, etc. If you need more information about a specific program, other
than information found in the man-page, Google usually knows all about it.

Finally, it strives to use new features as they become available, as long as
they are consistent with the rest of the goals. In short, CRUX might suit you
very well if you are:

* A somewhat experienced Linux user who wants a clean and solid Linux
  distribution as the foundation of your installation.
* A person who prefers editing configuration files with an editor to using a
  GUI.
* Someone who does not hesitate to download and compile programs from the
  source.

# User Feedback

## Issues

If you have any problems with or questions about this image, please contact us
 through a [GitHub issue](https://github.com/therealprologic/docker-crux/issues).

You can also reach many of the official image maintainers via the
`#docker-library` IRC channel on [Freenode](https://freenode.net).

## Contributing

You are invited to contribute new features, fixes, or updates, large or small;
we are always thrilled to receive pull requests, and do our best to process them
as fast as we can.

Before you start to code, we recommend discussing your plans 
through a [GitHub issue](https://github.com/therealprologic/docker-crux/issues), especially for more ambitious
contributions. This gives other contributors a chance to point you in the right
direction, give you feedback on your design, and help you find out if someone
else is working on the same thing.