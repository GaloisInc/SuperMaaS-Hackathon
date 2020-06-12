---
layout: default
---

## Links and Details for Vitual Attendance

### Preparing your models

There are a few things you can do to prepare for your model(s) for the hackathon.

#### If you have large datasets

If your model will be using datasets larger than 100MB, you should take steps to get that data to Galois make the data accessible to Galois via sharing tool (e.g. Google Drive, SFTP, DropBox, etc.).

#### Make sure you have the necessary tools installed

Galois will be driving this hackathon and are planning to do as much of the actual work as possible, but in order to be as effective as possible, you will want to be able to follow along with our efforts. To do this, making sure you have SSH available ([PuTTY](https://www.putty.org/) for Windows or [Terminus](https://termius.com/) if you prefer GUI tools) installed.

#### Make a list of the dependencies your model has

A larger part of the hackathon will be creating an environment to run your model(s) and as such, Galois will need to know what libraries/tools your models depend upon in order to run. Some questions to consider:

* Do you need Python2 or Python3? 
* If you require MatLab, can your model run using Octave?
* Does your model use special libraries (e.g. `???`, `???`, etc.)?

#### If your model makes use of proprietary tools that need special licenses

This will be particularly difficult as SuperMaaS will need to be able to run your model(s) independent of any environment you currently use, so having an understanding of licensing issues will be key as they will present a logistical wrinkle that Galois will need to consider.