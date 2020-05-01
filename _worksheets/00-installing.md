---
layout: worksheet
title: Installing Bonsai
permalink: /worksheets/installing/
---

Installing Bonsai on Windows
----------------------------

1. Download Bonsai from [bonsai-rx.org](https://bonsai-rx.org).
2. Install **Bonsai - Starter Pack** from the package manager. ![The Bonsai package manager]({{ site.baseurl }}/assets/images/packagemanager.png)
3. Click the `Updates` tab on the left side of the screen and install any available upgrades.
4. Read [http://bonsai-rx.org/docs/editor](http://bonsai-rx.org/docs/editor) for an introduction to the user interface.

Installing Bonsai on Linux
---------------------------

1. Install the [Mono](https://www.mono-project.com/download/stable/#download-lin) framework for Linux.
2. Download the preview release [Bonsai-2.5.1-preview.zip](https://github.com/bonsai-rx/bonsai/releases/tag/2.5.1-preview).
3. Extract the contents of the archive into a folder and run the following command `mono Bonsai.exe`.
4. Install **Bonsai - Starter Pack** from the package manager.

### Install OpenCV (Optional)

Bonsai works with OpenCV 2.4, which you will have to download and build from source on your system.

1. Add the earlier release repositories for libjasper:
```
sudo add-apt-repository "deb http://security.ubuntu.com/ubuntu xenial-security main"
```
2. Follow [these instructions](https://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html) to build and install OpenCV 2.4 on your system. Make sure to build the 2.4 branch, or [download the zip from GitHub](https://github.com/opencv/opencv/archive/2.4.zip).
3. OpenCV installs libraries into `usr/local/lib`, so you may need to configure your environment using [one of these options](https://unix.stackexchange.com/questions/67781/use-shared-libraries-in-usr-local-lib) to share libraries at a system level.
4. Download the [DLL map config file]({{ site.baseurl }}/assets/scripts/OpenCV.Net.dll.config) for OpenCV.NET and copy it into the folder `Packages/OpenCV.Net.3.3.1/lib/net40` in your local Bonsai install file to redirect dependencies to your system install.
