First, get into this website:
    https://www.flightgear.org/download/

Then click
    
    Download FlightGear for Linux and other platforms on the “Main Program Download” page.
    
Linux:
   
    Ubuntu: Launchpad PPA for FlightGear (Updated for version 3.2; contributed by Saikrishna Arcot)

After these steps we get into https://launchpad.net/~saiarcot895/+archive/ubuntu/flightgear
    
To start installing and using software from a Personal Package Archive, you first need to tell Ubuntu where to find the PPA.

    sudo add-apt-repository ppa:saiarcot895/flightgear

    deb http://ppa.launchpad.net/saiarcot895/flightgear/ubuntu YOUR_UBUNTU_VERSION_HERE main 
    deb-src http://ppa.launchpad.net/saiarcot895/flightgear/ubuntu YOUR_UBUNTU_VERSION_HERE main 
    
    Ubuntu 18.04
    deb http://ppa.launchpad.net/saiarcot895/flightgear/ubuntu bionic main 
    deb-src http://ppa.launchpad.net/saiarcot895/flightgear/ubuntu bionic main 
    
    
Now, as a one-off, you should tell your system to pull down the latest list of software from each archive it knows about, including the PPA you just added.
    
    sudo apt-get update

Now you're ready to start installing software from the PPA! 

    sudo apt install flightgear
