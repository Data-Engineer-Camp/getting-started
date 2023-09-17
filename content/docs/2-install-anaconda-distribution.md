---
weight: 1
bookFlatSection: true
title: "2. Install Anaconda Distribution"
---

# Anaconda Distribution

Anaconda is a distrubtion (package manager and installer) for Python (and R). 

Anaconda simplifies the process of installing Python and setting up virtual environments (we'll cover more on that in the course).

By installing Anaconda, you won't need to install Python for this bootcamp as Python is installed as part of Anaconda. 

To download Anaconda, go to https://www.anaconda.com/products/distribution and select "Download". 

If you are a MacOS user, follow the macOS graphical install instructions [here](https://docs.anaconda.com/anaconda/install/mac-os/#macos-graphical-install).

If you are a Windows user, follow the windows install instructions [here](https://docs.anaconda.com/anaconda/install/windows/).

**For windows users only:**

- Please tick the [x] Add Anaconda3 to my PATH environment variable. This will save us a step later on when configuring Anaconda in the bootcamp. If you forgot to tick this option, it's no problems at all as we can manually configure this later on in the bootcamp.

To verify that you have installed Anaconda successfully, you can either: 
1. Go to your applications or programs and verify that "Anaconda Navigator" appears, or 
2. You can go to command prompt or terminal and type `conda --version` and you should see `conda 4.12.0` or similar (version numbers may change). If you get an error here, that is likely because Anaconda was not added to your PATH environment variable yet. We will configure this later in the bootcamp.  

{{< button relref="/docs/1-install-vs-code" >}}&laquo; Previous{{< /button >}} {{< button relref="/docs/3-install-postgresql" >}}Next &raquo;{{< /button >}}