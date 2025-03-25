## Code the Classics - Volume II - PI 400 Guide

![Code the Classics - Volume 2](/assets/images/prj_ctcv2/Code_the_Classics_vol_2_Fix.jpg)

A few weeks ago, I was lucky enough to be gifted a physical copy of [Code the Classics – Volume II](https://store.rpipress.cc/collections/books/products/code-the-classics-volume-ii) published by Raspberry PI Press.

I had originally purchased the e-version via [Humble Bundle](https://www.humblebundle.com/books/raspberry-pi-and-retro-gaming-by-raspberry-pi-press-books?hmb_source=&hmb_medium=product_tile&hmb_campaign=mosaic_section_1_layout_index_1_layout_type_threes_tile_index_3_c_raspberrypiandretrogamingbyraspberrypipress_bookbundle) but struggled to get any of the code to run, going to say it was due to “e-book fatigue”.

I’ve put the below steps together to help anyone wanting to get the games up and running quickly.

If you just want to play the games, not code review or tinker with the code, I have added how to play the games standalone at the end of the post.

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

  **Editing and Review the Code**

  The book recommends using [Thonny](https://thonny.org) or [PyCharm CE](https://www.jetbrains.com/pycharm/) to review and edit the code.

  I tried running the game code through Thonny but kept running into errors, after researching 
  the issue it looks like there is a bug in Thonny (that is what I found).

  As much as I like PyCharm, I think it's a "little heavy" for the PI 400.

  By default on the Raspberry Pi OS (64-bit) build Geany is installed.

  It ran the code without a hitch, so I would recommend using it if you don't have another preferred code editor.

  **Installing the games just to play**

  To install the games in Code The Classics and Code The Classics - Volume II follow the below steps

  - Select the Raspberry Icon on the taskbar
  - Select Preferences
  - Select Recommend Software
  - Under the Recommend Software Application, find the Games option and tick both Code the Classics and Code the Classics 2 
  - Select Apply

  This will go ahead and install the games, you will the find the games under Games in the main menu.  
      
  
