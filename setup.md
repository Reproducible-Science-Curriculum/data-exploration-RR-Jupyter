---
layout: page
title: Setup
root: .
---
## Installing `Python`

[`Python`](http://python.org) is a popular language for research computing, and great for general-purpose programming as well. Installing all of its research packages individually can be a bit difficult, so we recommend Anaconda, an all-in-one installer.
Regardless of how you choose to install it, please make sure you install `Python` version 3.x (e.g., 3.4 is fine).
We will teach `Python` using the [Jupyter Notebook](http://jupyter.org), a programming environment that runs in a web browser. For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, Safari and Firefox browsers are all supported (some older browsers, including Internet Explorer version 9 and below, are not).

### Windows

[Video tutorial](https://www.youtube.com/watch?v=xxQ0mzZ8UvA)

1. Open https://www.anaconda.com/download/ with your web browser.
2. Download the `Python 3` installer for Windows.
3. Install `Python 3` using all of the defaults for installation except make sure to check that the **Anaconda distribution is the default Python**.

### Mac OSX

[Video tutorial](https://www.youtube.com/watch?v=TcSAln46u9U)

1. Open https://www.anaconda.com/download/ with your web browser.
2. Download the `Python 3` installer for OS X.
3. Install `Python 3` using all of the defaults for installation.
    * If ypou want to install Anaconda in your home directory ("_for me onluy_"), and the respective dialog when it initially appears prohibits this choice, change the location to system-wide ("_for every user_"), and then change it back. (This is a bug in the installer that can manifest on some versions of MacOSX.)

### Linux

1. Open https://www.anaconda.com/download/ with your web browser.
2. Download the `Python 3` installer for Linux.
3. Install `Python 3` using all of the defaults for installation. (Installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
4. Open a terminal window.
5. Type:

    ```
    bash Anaconda3-
    ```

   and then press tab. The name of the file you just downloaded should appear.
6. Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type yes and press enter to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).

## To confirm successful installation

1. Open a `Terminal` or `command prompt`
2. Type

    ```
    jupyter notebook
    ```
    
    and the default web browser should load and display the Jupyter dashboard.

## Credits

This installation tutorial is taken from [Software Carpentry](http://swcarpentry.github.io/workshop-template/#setup)