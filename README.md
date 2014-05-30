Debugging and Performance Analysis Using DTrace
=====================


## Description

In this session, attendees will be given a few example applications written in Node.js that have bugs and/or performance issues. To do the debugging, we'll be using DTrace and mdb on SmartOS.

## With this training, you will learn

- How to use DTrace probes to examine performance issues with Node.js
  applications.
- How to use mdb to examine objects in your app
- How to add DTrace probes to your app

## Trainers

* [TJ Fontaine]()
* [Max Bruning]()

## Preparations for this training

In order to prepare to this training you should/must do the following List of readings and exercises. If you have questions, please open an issue and we will be glad to answer, you might be helping other participants too.

### TODO List

To get the most out of this session, you'll need to have a system
running SmartOS.  There are 2 ways to do this:

	- Run it in a virtual machine on VMware, Parallels, VirtualBox, or some other virtual machine environment.
	- Get a virtual machine from the Joyent cloud.

To run SmartOS in a virtual machine, go to
http://wiki.smartos.org/display/DOC/Download+SmartOS, where you'll
find SmartOS images to download, along with instructions.  After
SmartOS is booted, you'll need to create a zone. Instructions are at
http://wiki.smartos.org/display/DOC/How+to+create+a+zone+%28+OS+virtualized+machine+%29+in+SmartOS.

You can choose an image that has node pre-installed by running:

imgadm avail | grep node

Or, you can install a base-64 image and then

pkgin install node

To run a machine in the Joyent cloud, go to http://www.joyent.com, create an account, and then provision a machine, (there are machines that have node pre-installed).

Test by running node on the code example in materials.  More examples
will be coming.

### Materials

- code_example.js
- More to come shortly

## 27 Jun 17:30h Participants

`TBA`

## 28 Jun 14:30h Participants

`TBA`
