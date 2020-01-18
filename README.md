# Jupyter Lab Environment

This is a simple Vagrant virtual machine. It contains a setup for running Jupyter lab with Python 3.7. The setup includes the [Anaconda Python distribution](https://www.anaconda.com/distribution/) which means a lot of data science packages like [NumPy](http://www.numpy.org/), [pandas](https://pandas.pydata.org/), [matplotlib](https://matplotlib.org/), [Bokeh](https://bokeh.pydata.org/en/latest/) and many more are readily included in the setup. 

### Prerequisites

You need the following installed on your computer:
- [Virtualbox v6.0](https://www.virtualbox.org/)
    - Windows: https://download.virtualbox.org/virtualbox/6.0.16/VirtualBox-6.0.16-135674-Win.exe
    - Linux: https://www.virtualbox.org/wiki/Download_Old_Builds_6_0 (choose your distribution)
    - MacOS: https://download.virtualbox.org/virtualbox/6.0.16/VirtualBox-6.0.16-135674-OSX.dmg
- [Vagrant](https://www.vagrantup.com/)
    - Windows: https://releases.hashicorp.com/vagrant/2.2.6/vagrant_2.2.6_x86_64.msi
    - Linux: 
        - Ubuntu: https://releases.hashicorp.com/vagrant/2.2.6/vagrant_2.2.6_linux_amd64.zip
        - Arch: https://releases.hashicorp.com/vagrant/2.2.6/vagrant_2.2.6_x86_64.tar.xz
        - Others: https://www.vagrantup.com/downloads.html
    - MacOS: https://releases.hashicorp.com/vagrant/2.2.6/vagrant_2.2.6_x86_64.dmg

### Usage

- Download the content (either git clone, or zip download) to a directory of your choice 
    - In the case you have chosen the zip download, do not forget to unzip the zip file
- Open a command line, and through the command line change the directory of the content
- Run the shell command `vagrant up`
- Wait until the virtual machine is setup and ready. (nevermind the red colored output)
- Point your browser to [http://localhost:8888](http://localhost:8888)
    - **Optional:** If you need to install additional Python packages (or do something similar) you can log into the virtual machine by calling `vagrant ssh`.
- You can now create a folder for each discipline where you are going to need this tool. E.g. SIM, IA.

**That's it.** I hope this is useful for some people. Have fun!


### Thank's
This is a for from [Anton Pirker's](https://github.com/antonpirker) [jupyter-vagrant-box](https://github.com/antonpirker/jupyter-vagrant-box) - thank you Anton for setting this up!

