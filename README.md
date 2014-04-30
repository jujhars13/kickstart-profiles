Kickstart Profiles
==================

**For to make good vagrant...**

Forked from [https://github.com/jameswthorne/kickstart-profiles](https://github.com/jameswthorne/kickstart-profiles)

Using this [blog post](http://thornelabs.net/2013/11/11/create-a-centos-6-vagrant-base-box-from-scratch-using-virtualbox.html) to build some custom vagrant boxes as it's taking the p*ss installing all these pacakges on each `vagrant up`

## Usage
I would recommend you download the **DVD1** iso of CentOS 6.x x86_64 

Get your machine ready to boot in virtualbox.  Remember to disable your USB controller and audio controller first.

When the Grub boot menu appears, highlight Install or upgrade an existing system, hit the Tab key to bring up the anaconda boot line, and append the following:

`noverifyssl ks=https://raw.githubusercontent.com/jujhars13/kickstart-profiles/master/centos-6-x86_64-vagrant-box.txt`

**NB** You won't have the virtualbox extensions installed, so you can't copy and paste the link above, so make sure you type carefully see screenshot.

![](https://raw.githubusercontent.com/jujhars13/kickstart-profiles/master/centos65-VM-VirtualBox.png)


