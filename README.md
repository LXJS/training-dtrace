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

## 28 jun - 14:30h Participants

- Abel Soares - [abelsoares](https://github.com/abelsoares)
- Dominic Lüchinger - [dol](https://github.com/dol)
- Filipe Dias - [filipediasferreira](https://github.com/filipediasferreira)
- Igor Soarez - [soarez](https://github.com/soarez)
- James Nocentini - [jamiltz](https://github.com/jamiltz)
- João Nelas - [adagios](https://github.com/adagios)
- Jorge Monteiro - [jorgemonteiro](https://github.com/jorgemonteiro)
- Marco Oliveira - [marcooliveira](https://github.com/marcooliveira)
- Max Gfeller - [MaxGfeller](https://github.com/MaxGfeller)
- Pierre Ozoux - [pierreozoux](https://github.com/pierreozoux)
- Ricardo Tomasi - [ricardobeat](https://github.com/ricardobeat)
- Robert Kowalski - [robertkowalski](https://github.com/robertkowalski)
- Tiago Rodrigues - [trodrigues](https://github.com/trodrigues)
- Tom Cartwright - [tomcartwrightuk](https://github.com/tomcartwrightuk)

## 27 jun - 17:30h Participants

- Daniel da Silva - [danielfdsilva](https://github.com/danielfdsilva)
- David McMullin - [davecocoa](https://github.com/davecocoa)
- Dominykas Blyžė - [dymonaz](https://github.com/dymonaz)
- George Shank - [taterbase](https://github.com/taterbase)
- Igor Soarez - [soarez](https://github.com/soarez)
- Joaquim Serafim - [joaquimserafim](https://github.com/joaquimserafim)
- Luís Ferreira - [zamith](https://github.com/zamith)
- Luke Bond - [lukebond](https://github.com/lukebond)
- Miguel Coquet - [mcoquet](https://github.com/mcoquet)
- Miguel Palhas - [naps62](https://github.com/naps62)
- Ricardo Melo - [rjsmelo](https://github.com/rjsmelo)
- Ricardo Quintas - [rdquintas](https://github.com/rdquintas)
- Ronaldo Sousa - [ronaldofs](https://github.com/ronaldofs)
- Stefan Jansen - [xtravanta](https://github.com/xtravanta)
- Thomas Parisot - [oncletom](https://github.com/oncletom)
- Zoltan Feher - [zkiiito](https://github.com/zkiiito)
