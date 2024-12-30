## Setting up Code the Classic - Volume II - Field Guide

![Code the Classics - Volume 2](/assets/images/prj_ctcv2/Code_the_Classics_vol_2_Fix.jpg)

A few weeks ago, I was lucky enough to be gifted a physical copy of [Code the Classics – Volume II](https://store.rpipress.cc/collections/books/products/code-the-classics-volume-ii) published by Raspberry PI Press.

I had originally purchased the e-version via [Humble Bundle](https://www.humblebundle.com/books/raspberry-pi-and-retro-gaming-by-raspberry-pi-press-books?hmb_source=&hmb_medium=product_tile&hmb_campaign=mosaic_section_1_layout_index_1_layout_type_threes_tile_index_3_c_raspberrypiandretrogamingbyraspberrypipress_bookbundle) but struggled to get any of the code to run, going to say it was due to “e-book fatigue”.

I’ve put the below steps together to help anyone wanting to get the games up and running quickly.

I cover the below platforms:

-	Raspberry PI 400 (Raspberry Pi OS (64-bit) - bookworm)
-	macOS 15.2 (Apple Silicon, but should also work on Intel based Mac's)
-	Windows 11 (VMware Fusion 13.5 Pro, but should also work on bare-metal installs Win 10/11) - Coming Soon

 **Raspberry PI 400**

  I originally run the code on Raspberry Pi OS (32-bit) bookworm but found the games very sluggish, so would recommend 
  upgrading to the (Raspberry Pi OS (64-bit) bookworm.

  Below is a summary on how to upgrade - [Link to full version](https://www.raspberrypi.com/software/) 

  - Download the 64-bit Raspberry Pi OS image 
  - Flash the image to an SD card using the Raspberry Pi Imager
  - Insert the SD card into your Pi 400
  - Boot up your Pi 400 and complete the initial setup

  **Checking that all required software is installed**

  The below is all run via Terminal 

  Upgrade Raspberry PI OS and all packages 

    sudo apt full-upgrade

  Check Python 3 version (should be 3.12.2 or higher (recommend version for the book))

    python3 —version

  Check Pygame version (should be 2.6.1 or higher)

    pip3 show pygame

  Install git (this will be used to clone the games code to the PI400)

    sudo apt install git-all

  The above Python 3 and Pygame versions are the defualts installed on Raspberry PI OS (as of this writing).

  **Install a Joystick Keyboard Mapper (Optional)**

  I normally do this as I prefer playing games via a controller and map the keys, but as mentioned this is optional.

  Note: The games do have a Joystick option.

  The Joystick Keyboard Mapper I use is Qjoypad

     sudo-get install qjoypad

  **Playing the Games**

  Since we just want to play the games for now, I will clone the "Games" repository under the Downloads directory

  The below is all run via Terminal

  Change to the Downloads dirctory (I am assuming you are in the User directory)

    cd Downloads 

  Clone the "Games" from the books GitHub repository

    git clone https://github.com/raspberrypipress/Code-the-Classics-Vol2

  Once the clone has completed move into the games direcorty

    cd Code-the-Classics-Vol2

  You can now list the games

    ls

  You should see the below listing

    README.md beatstreets eggzy leadingedge avenger cover kinetix

  Let's play Beat Streets (Double Dragon Inspired)

    cd beatstreets
    pgzrun beatstreets.py

  **macOS 15.2**

  **Installing Python 3.12.2**

  - [Download Python 3.12.2](https://www.python.org/downloads/release/python-3122/)
  - Double click the installer and follow the on-screen instructions.

  Once installed run the below from the Terminal

    which python3

   You should get the below result

    /Library/Frameworks/Python.framework/Versions/3.12/bin/python3

   **Installing pip3**

   pip3 is automatically installed with Python3 (3.12.2), I would recommend checking if there is a newer version.

   The below is all run via Terminal

     pip3 install –upgrade pip

     pip3 --version

   You should get the below result

     pip 24.3.1 from /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages/pip (python 3.12)

   **Installing Pygame Zero**

   The below is all run via Terminal

    pip3 install pgzero

   You should get the below result

    Successfully installed numpy-2.2.1 pgzero-1.2.1 pygame-2.6.1

   **Install a Joystick Keyboard Mapper (Optional)**

   As mentioned in the PI 400 install, I like using a Joystick Keyboard Mapper for macOS I use [Joystick Mapper](https://apps.apple.com/za/app/joystick-mapper/id528183797?mt=12) (it's a little old but still works)

   **Playing the Games (same as the PI 400 install)**

  Since we just want to play the games for now, I will clone the "Games" repository under the Downloads directory

  The below is all run via Terminal

  Change to the Downloads dirctory (I am assuming you are in the User directory)

    cd Downloads 

  Clone the "Games" from the books GitHub repository (we will be using the git version that is pre-installed on macOS)

    git clone https://github.com/raspberrypipress/Code-the-Classics-Vol2

  Once the clone has completed move into the games direcorty

    cd Code-the-Classics-Vol2

  You can now list the games

    ls

  You should see the below listing

    README.md beatstreets eggzy leadingedge avenger cover kinetix

  Let's play Beat Streets (Double Dragon Inspired)

    cd beatstreets
    pgzrun beatstreets.py
    
