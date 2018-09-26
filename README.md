# Cloudfoundry Bosh Bootloader CLI - Snap

[BOSH](https://bosh.io) is a project that unifies release engineering, deployment, and lifecycle management of small and large-scale cloud software. [BOSH](https://bosh.io) can provision and deploy software over hundreds of VMs. 

And the [BOSH Bootloader (CLI)](https://github.com/cloudfoundry/bosh-bootloader) a utility for standing up a BOSH director on an IAAS of your choice.

This repository contains the code for the _bosh bootloader cli_ *snap* package.

**NOTE:**
  And works on Ubuntu, Fedora, Debian, and other major Linux distributions.

##

 Prerequists include a linux installation and the snapd service. In order to install snapd please follow the [Install snapd](https://docs.snapcraft.io/core/install) guide.

## Dependencies

The following should be installed on your local machine
- [bosh-cli](https://bosh.io/docs/cli-v2.html)
- [bosh create-env dependencies](https://bosh.io/docs/cli-env-deps.html)
- [terraform](https://www.terraform.io/downloads.html) >= 0.11.0
- ruby (necessary for bosh create-env)

NOTE:
  Some of the dependencies are also available as snap packages.

## Installation

In order to install the bosh snap use the 'snap' cli i.e :

```
sudo snap install bbl
```

## Build

Checkout the source code and from inside the snap directory execute the following command :

```
snapcraft
```

## Contributing

 See the [contribution guidelines](CONTRIBUTING.md).

## License
```
MIT License

Copyright (c) 2018 Ioannis Polyzos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
