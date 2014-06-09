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

To run a machine in the Joyent cloud, go to http://www.joyent.com,
create an account, and then provision a machine, (there are machines
that have node pre-installed).

In the Joyent cloud, there is a free Developer Tier, which allows you to create one small instance valid for 1 year of trial usage. However, to provision that instance you must add a valid credit card to your account so we can validate that the account is not fraudulent.

New accounts won’t be billed if they only provision that single developer tier instance.

Test by running node on the code example in materials.  More examples
will be coming.

### Materials

- More to come shortly

## 27 jun - 17:30h Participants

- Joaquim Serafim - [joaquimserafim](https://github.com/joaquimserafim)
- Igor Soarez - [soarez](https://github.com/soarez)
- Daniel da Silva - [danielfdsilva](https://github.com/danielfdsilva)
- Nelson Correia - [nelsonic](https://github.com/nelsonic)
- Ines Teles - [iteles](https://github.com/iteles)
- David McMullin - [davecocoa](https://github.com/davecocoa)
- Thomas Parisot - [oncletom](https://github.com/oncletom)
- George Shank - [taterbase](https://github.com/taterbase)
- Dominykas Blyžė - [dymonaz](https://github.com/dymonaz)
- Ricardo Melo - [rjsmelo](https://github.com/rjsmelo)
- Zoltan Feher - [zkiiito](https://github.com/zkiiito)
- Miguel Coquet - [mcoquet](https://github.com/mcoquet)
- Stefan Jansen - [xtravanta](https://github.com/xtravanta)
- Ricardo Quintas - [rdquintas](https://github.com/rdquintas)
- Luke Bond - [lukebond](https://github.com/lukebond)
- Luís Ferreira - [zamith](https://github.com/zamith)
- Miguel Palhas - [naps62](https://github.com/naps62)
- Nelson Fonseca - [nlfonseca](https://github.com/nlfonseca)
- Ronaldo Sousa - [ronaldofs](https://github.com/ronaldofs)

## 28 jun - 14:30h Participants

- Igor Soarez - [soarez](https://github.com/soarez)
- Pierre Ozoux - [pierreozoux](https://github.com/pierreozoux)
- Robert Kowalski - [robertkowalski](https://github.com/robertkowalski)
- Filipe Dias - [filipediasferreira](https://github.com/filipediasferreira)
- Abel Soares - [abelsoares](https://github.com/abelsoares)
- Matej Nemcek - [yangwao](https://github.com/yangwao)
- Karolis Narkevicius - [KidkArolis](https://github.com/KidkArolis)
- Oliver Zeigermann - [DJCordhose](https://github.com/DJCordhose)
- João Nelas - [adagios](https://github.com/adagios)
- Marco Oliveira - [marcooliveira](https://github.com/marcooliveira)
- Ricardo Tomasi - [ricardobeat](https://github.com/ricardobeat)
- Tiago Rodrigues - [trodrigues](https://github.com/trodrigues)
- Dominic Lüchinger - [dol](https://github.com/dol)
- Max Gfeller - [MaxGfeller](https://github.com/MaxGfeller)
- Tom Cartwright - [tomcartwrightuk](https://github.com/tomcartwrightuk)
- James Nocentini - [jamiltz](https://github.com/jamiltz)
- Jorge Monteiro - [jorgemonteiro](https://github.com/jorgemonteiro)
