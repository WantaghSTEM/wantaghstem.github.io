---
layout: post
title:  "Downloading Python"
date:   2017-01-07 23:07:12 -0500
categories: jekyll update
---

<style type="text/css">


/** From the anaconda page */
.content-button {
    border-style: solid;
    border-width: 0;
    cursor: pointer;
    font-family: "CalibreWeb-Regular", Lato, "Helvetica Neue", Helvetica, Roboto, Arial, sans-serif;
    font-size: 1.25rem;
    font-weight: 300;
    line-height: normal;
    position: relative;
    text-decoration: none;
    text-align: center;
    -webkit-appearance: none;
    border-radius: 0;
    display: inline-block;
    padding-top: 0.75rem;
    padding-right: 1.5rem;
    padding-bottom: 0.8125rem;
    padding-left: 1.5rem;
    background-color: #253746;
    border-color: #1e2c38;
    color: #fff;
    transition: background-color 300ms ease-out;
    max-width: 18.75rem;
    text-transform: uppercase
}

.content-button span {
    font-family: Lato, "Helvetica Neue", Helvetica, Roboto, Arial, sans-serif;
    font-weight: 200;
	font-size:90%;
    color: #000;
}

.content-button:hover, .content-button:focus {
    background-color: #1e2c38
}

.content-button:hover, .content-button:focus {
    color: #fff
}

.content-button:hover, .content-button:focus {
    text-decoration: none
}

.content-button[role="button"] {
    display: block;
    padding: 0.75rem 1.375rem;
    text-align: center
}

.content-button--blue, .call-to-action__button, .cross-sell__button,
input[type="submit"].cross-sell__button {
    background-color: #089BCC;
    border-color: #067ca3;
}

.content-button--blue:hover, .call-to-action__button:hover, .cross-sell__button:hover,
input[type="submit"].cross-sell__button:hover, .content-button--blue:focus,
.call-to-action__button:focus, .cross-sell__button:focus, input[type="submit"].cross-sell__button:focus {
    background-color: #067ca3;
}

.content-button--blue:hover, .call-to-action__button:hover, .cross-sell__button:hover,
input[type="submit"].cross-sell__button:hover, .content-button--blue:focus,
.call-to-action__button:focus, .cross-sell__button:focus, input[type="submit"].cross-sell__button:focus {
    color: #fff
}

.content-button--small {
    /*font-size: 1.125rem;
    max-width: 12.75rem; */
}

.content-button--small[role="button"] {
    /*padding: 0.5625rem 0.875rem;*/
}
</style>

[Python][python] is one of the main languages that we've been teaching at TechDay over the past few years. We're providing this resource in order to help people install Python on their computers at home, so that they can run the projects built during TechDay. While it's relatively straightforward to install a generic Python version, we utilize several libraries to help make some of our projects, which could be difficult to install sometimes. You should be able to complete this installation within 10 - 15 minutes.

We've included a video tutorial below to help you through the installation. We've also included written instructions, so please feel free to use whatever is convenient!

<iframe width="560" height="315" src="https://www.youtube.com/embed/B-W-me5Y7F4" frameborder="0" allowfullscreen></iframe>


## Table of Contents
- [Installing Python](#install-python)
  - [Mac](#mac)
    - [Anaconda](#mac-anaconda)
    - [XQuartz](#mac-xquartz)
    - [TechDay Extensions](#mac-extensions)
  - [Windows](#windows)
    - [Anaconda](#win-anaconda)
    - [TechDay Extensions](#win-extensions)
- [Installing Sublime Text](#install-sublime)
  - Package Control
  - Anaconda Package
- [Testing Python Installation](#testing-python)
  - Command Line
  - Sublime Text

### <a name="install-python"></a>Installing Python
We will be using a distribution of Python known as [Anaconda](https://www.continuum.io/downloads). This version ships with many popular Python libraries, and has become widely popular within both academia and industry. We will show you how to download __Python 2.7__, because some of the packages that we use are not yet supported on Python 3. We are looking to update our curriculum to Python 3.5 shortly, as it comes with many improvements over Python 2.7. When we do so, we will post follow-up instructions.

As previously mentioned, we use Python version 2.7 for TechDay. So, if you have the 3.5 version of Anaconda already installed, this may conflict with the installation process below. In that case, you have two options: (1) remove the old Anaconda version; or (2) set up a <a href="http://conda.pydata.org/docs/using/envs.html">special environment</a> to run any TechDay related programs. If you choose the latter, you will need to install the extension libraries manually. Please email <a href="mailto:wantagh.technology@gmail.com">wantagh.technology@gmail.com</a>.


#### <a name="mac"></a>__Mac Installation__

#### <a name="mac-anaconda"></a> *Anaconda Installation*
Click the following link to begin the installation of Anaconda Python. The file that you download will be an installer application, so proceed with the instructions on the installer as you would with any other application.

<a class="content-button content-button--blue content-button--small" href="https://repo.continuum.io/archive/Anaconda2-4.2.0-MacOSX-x86_64.pkg" role="button">Mac OS X 64-bit<br>
   <span style="color:#000000; font-size:90%;">Anaconda 2.7</span></a>

However, you may run into the following issue:

![Blah](/assets/osx-anaconda-error.png)

To fix this, just click on the __house__, and you will get something like:

![Blah](/assets/osx-anaconda-local.png)

*Note*: You can install Anaconda this way, however, this is not suggested. Instead, click the __hard drive icon__ directly below the house. Then, you should get something like:

![Blah](/assets/osx-anaconda-global.png)

Finally, just click the "Choose Folder" button on the bottom right. You must now direct the installer where to put Anaconda - we suggest you put it in the __Applications__ folder.

#### <a name="mac-xquartz"></a> *XQuartz Installation*

On top of Anaconda Python, macOS also needs a software known as XQuartz. XQuartz is used for scientific computing software. To do this, just click the button above and run the installer (click .pkg file), following the directions you are prompted with.

<a class="content-button content-button--blue content-button--small" href="https://dl.bintray.com/xquartz/downloads/:XQuartz-2.7.10.dmg" role="button">Mac OS X 64-bit<br>
   <span style="color:#000000; font-size:90%;">XQuartz 2.7.10</span></a>

#### <a name="mac-extensions"></a> *TechDay Extensions*

#### <a name="windows"></a>__Windows Installation__

#### <a name="win-anaconda"></a> *Anaconda Installation*
#### <a name="win-extensions"></a> *TechDay Extensions*

<a class="content-button content-button--blue content-button--small" href="https://repo.continuum.io/archive/Anaconda2-4.2.0-Windows-x86_64.exe" role="button">Windows 64-bit<br>
   <span style="color:#000000; font-size:90%;">Anaconda 2.7</span></a>

### <a name="install-sublime"></a>Installing Sublime Text
<a class="content-button content-button--blue content-button--small" href="https://download.sublimetext.com/Sublime%20Text%20Build%203126.dmg" role="button">Mac 64-bit<br>
   <span style="color:#000000; font-size:90%;">Sublime Text 3</span></a>

   <a class="content-button content-button--blue content-button--small" href="https://download.sublimetext.com/Sublime%20Text%20Build%203126%20x64%20Setup.exe" role="button">Windows 64-bit<br>
      <span style="color:#000000; font-size:90%;">Sublime Text 3</span></a>

### <a name="testing-python"></a>Testing Python Installation

*Adapted from [Cornell University][cornell-python]*.

[cornell-python]: http://www.cs.cornell.edu/courses/cs1110/2016fa/materials/python.php
[python]: http://www.python.org
