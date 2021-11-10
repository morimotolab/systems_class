# Welcome!
Congratulations for your first programming steps!

<font color="green">The aim of this tutorial is to work with tables</font> - a common research scenario.
- You will be able to combine distinct tables (using pandas)
- You will be able to visualize your tables (using seaborn)
- You will be able to read a versatile programming language (Python)

Seaborn and pandas are "libraries" of Python. Think of them as books of instructions. If you have them available, you can call these instructions through the Python language to tell the computer how to accomplish very specialized tasks.

<font color="green">Structure of the course</font>
- Prior to class on November 18th: (custom study)
    - Download Anaconda
    - Follow 02_homework.ipynb


# Getting started

## Download this tutorial
Github, which stores the code for this tutorial, is used (and required by some journals) to exchange computational code. However, you can not execute code on github itself, and editing code on github is difficult. 

Instead, you will need to download a copy of this code, and store it on your computer. Click the above link, https://github.com/morimotolab/systems_class, and then click on the large green button that says "Clone or download" and download the code as a ZIP file to your desktop. In case that after the download you only see a ZIP file on the desktop, rather than a folder containing the individual files of the code of the tutorial, you will need to uncompress the ZIP file. On many computers this will be possible by double-clicking on the ZIP file. This can also be accomplished on the (unix) command line by running: `unzip [filepath]`. Note that you can also run unix commands on Windows using the [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/install).


## Installing Anaconda
You can think of Anaconda as a tool box. While you could also get those tools separately, it is much more convenient to know that the most needed tools will already be present and that they will work together. Anaconda already contains every tool necessary for this tutorial (and many more for scientific computing)
- Python
- pandas
- seaborn

Before visiting the download page, be warned: There are two distinct versions of Anaconda, where each contains comparable tools. <font color="green">Download a version for Python 3</font>, <font color="red">do not download a version for Python 2 </font> which is an old dialect of the Python language. With this in mind, go to the following page and download and subsequently install a Python 3 version: https://www.anaconda.com/products/individual (scroll down)

## Starting your work environment
- Open Anaconda Navigator (which has just been installed)
- Look for "jupyter notebook" (and ignore all the other buttons even if they claim to be for science)
- Start "jupyter notebook" (Click on Launch, or - in case it was absent - Install, which is shown beneath its logo)
- Now navigate to 02_homework.ipynb. You might need to click on a separate tab in your browser to see the .ipynb files you had download. Alternatively, close the browser and start Anaconda again
- This can also be accomplished on the (unix) command line by running `jupyter notebook` in the desired directory.
