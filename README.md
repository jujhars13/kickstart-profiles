kickstart-profiles
==================

**For to make good vagrant...**

Forked from [https://github.com/jameswthorne/kickstart-profiles](https://github.com/jameswthorne/kickstart-profiles)

Using this [blog post](http://thornelabs.net/2013/11/11/create-a-centos-6-vagrant-base-box-from-scratch-using-virtualbox.html) to build some custom vagrant boxes as it's taking the p**ss installing all these pacakges on each `vagrant up`

## Usage

When the Grub boot menu appears, highlight Install or upgrade an existing system, hit the Tab key to bring up the anaconda boot line, and append the following:

`noverifyssl ks=https://raw.githubusercontent.com/jujhars13/kickstart-profiles/master/centos-6-x86_65-vagrant-box.txt`


