=================
OpenSwitch README
=================

OpenSwitch is an Open Source switch operating system for networking switches
and virtual machines. This repository specifically captures the governance
aspects of OpenSwitch.

Building OpenSwitch Governance Documents
----------------------------------------

To generate a PDF version of the governance documents, follow the steps
below.

* Make sure you have dependencies installed. On Ubuntu, this is done
  running the following command:

```
sudo apt-get install python-sphinx python-oslosphinx texlive texlive-latex-extra
```

* Go into the "doc" directory and run the command below:

```
make latexpdf
```

Links
-----

* Free software: Apache license
* Documentation: http://docs.openswitch.net/developer/governance
* Source: http://git.openswitch.net/cgit/openswitch/governance
