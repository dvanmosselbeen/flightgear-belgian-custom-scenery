![alt text](https://github.com/dvanmosselbeen/flightgear-belgian-custom-scenery/wiki/screenshots/fgfs_belgian_scenery_presentation.png "FGFS Belgian Scenery Presentation pic")


# Introduction

This is some custom Belgian scenery for the [FlightGear Flight Simulator](http://www.flightgear.org). The FlightGear Flight Simulator is an awesome cross platform open source flight simulator. This flight simulator is extremely configurable and runs on a variety of hardware.

This scenery contains a lot of improvement to airports and landmarks in the Belgian country. See the wiki for the [airport list](https://github.com/dvanmosselbeen/flightgear-belgian-custom-scenery/wiki/Airports-list) that has been improved.

# Download and Setup

Downloading the FlightGear Belgian scenery is very easy and a matter of a few clicks.

## Download

You can [download the Belgian scenery as a zip file](https://github.com/dvanmosselbeen/flightgear-belgian-custom-scenery/archive/master.zip) (+- 482 MB) or clone the repository (+- 514 MB).

I don't really recommend you to download the scenery as a zip file, but instead i would suggest and encourage you to use the git version. The Belgian Scenery is a work in progress project and things change a lot. By using the zip version of the scenery, you would need to download and extract the scenery by hand each time you want to get the latest updates.

The big advantage of using git is that it will be much easier for you to get your local copy up to date. With one command (`git pull`) you can get the latest updates. If you want to make use of the git version, then i recommend you take a closer look to the section `How to user our repository and git ?`.

## Setup

If you installed FlightGear on Microsoft Windows, then you got a graphical launcher to start up FlightGear. So now you need to add the path of that custom scenery to the launcher. For this, go in the `Add-ons` section of the launcher, then in the section `Additional scenery folders` there you can add the path to the downloaded scenery. The procedure is the same for the scenery downloaded as zip file as the clone of the git repository.

If you don't make use of a graphical launcher for FlightGear, then you should add the scenery path with the `--fg-scenery` parameter. For example:

    --fg-scenery=C:/Users/dvanmosselbeen/Documents/git_repositories/flightgear-belgian-custom-scenery

# Hardware requirements

Generally speaking, the scenery should work on any decent computers. However, forget about your integrated graphics card or your bare Intel Celeron office computer if you want to "game". Giving numbers is very difficult and depend of many other factors, but to give you an idea, the scenery is still usable on my 9 years old (mid-range) Medion Desktop computer with all settings maxed out.

The hardware requirements also depend on which airport you want to make use. The dense EBBR (Brussels Airport) with it's very dense and close Brussels city scenery is heavy duty and you would probably need a more performing computer. EBBR runs smoothly on my (old) hardware.

Our goal is to make scenery for the future, with this we mean that we don't plan to build scenery that is usable on old and outdated hardware. The hardware requirements of the scenery is based for (mid-range) computers that are currently on the marked. Old hardware isn't officially supported.

In the sub sections, a list of my old and current hardware.

## Old hardware

This information is al based on FlightGear version `2019.2`.

### Desktop: Medion computer (bought around 2010)

    CPU: Intel i5-2320 3.0 GHz
    RAM: 16 GB RAM
    GFX Card: Nvidia GeForce GT 530
    HDD: 1 HDD (5400 rpm)
    Screen Resolution: 1920 x 1080
    Screen: Samsung 22"

The scenery still works more or less smoothly on this computer. I find that the Rembrandt render is smoother than the ASL render. With Rembrandt render enabled, i have a stable +- 20 fps in the cockpit view and +- 30 fps in the outside view with my [Rans S-6S ULM aircraft](https://github.com/dvanmosselbeen/Rans-S-6S) on my different airfields. I feel that the real bottleneck is the computing power (CPU) and the slow and old used HDD.

### Laptop: Asus computer (bought around ??)

    CPU: Intel ?
    RAM: 16 GB RAM
    GFX Card: Nvidia GeForce ?
    HDD: 2 HDD (5400 rpm)
    Screen Resolution: 1920 x 1080
    Screen: Integrated 17" screen

## New hardware

### Desktop: HP Omen 875-1780nd computer (bought 2019)

    CPU: Intel i7 - 9700 - Octa Core (8) - Coffee Lake -  3.0 GHz turbo boost 4,7 GHz (12 MB cache)
    RAM: 16 GB RAM (DDR4)
    GFX Card: Nvidia GeForce RTX 2080 (8 GB RAM)
    SDD: 512 GB
    HDD: 1 HDD of 2 TB (7200 rpm)
    Screen Resolution: 1920 x 1080
    Screen: Acer Nitro XV272UPbmiiprzx 27"

### Laptop: Acer Predator Helios 300 PH317-52-721E Azerty (bought 2019)

    CPU: Intel i7 - 8750H - Hexa core (6) - Coffee Lake - 2.2 GHz turbo boost 4,1 Ghz (9 MB cache)
    RAM: 16 GB RAM (SO-DIMM DDR4)
    GFX Card: Nvidia GeForce GTX 1060 (6GB RAM)
    SDD: 256 GB
    HDD: 1 HDD of 1 TB (5400 rpm)
    Screen Resolution: 1920 x 1080
    Screen: Inegrated 17" IPS screen

### Raspberry Pi 3 Model B

That Raspberry Pi 3 Model B has the standard config as if you could buy it in the shop. It is only used as a programming playground. Not for running the plain flight simulator itself but instead to run the tools on it.

### Tablet: Lenovo Lenovo Tab 2 A10-70F

Mainly only used for the maps when flying in multiplayer mode.

# Need more help?

It's best you follow the instruction on the dedicated wiki for instructions.
You can find the Wike here: https://github.com/dvanmosselbeen/flightgear-belgian-custom-scenery/wiki

You can also find documentation and help here:
 * [FlightGear Website](http://www.flightgear.org)
 * [FlightGear Wiki](http://wiki.flightgear.org)
 * [FlightGear Forum](https://forum.flightgear.org/)
 * [FlightGear Mailing List](http://wiki.flightgear.org/Mailing_lists)
 * FlightGear IRC channel - Connect to irc.flightgear.org and join the FlightGear channel (`/j #FlightGear`).

Feel free to take contact per email on `david.van.mosselbeen AT gmail.com` if you need more help or if want to contribute on this project. Mind the AT to be replaced by @.

# How to user our repository and git ?

Clone our repository on GitHub.com to our machine locally:

    git clone https://github.com/dvanmosselbeen/flightgear-belgian-custom-scenery.git

Change into the "flightgear-belgian-custom-scenery" directory:

    cd flightgear-belgian-custom-scenery

Make chances to your files (modify, add, delete ...)

Stage the changed files:

    git add fileName

Take a snapshot of the staging area (anything that's been added):

    git commit -m "My git log message"

Push changes to github: 

    git push

For more information read the Git Handbook:
https://guides.github.com/introduction/git-handbook/
