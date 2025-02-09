## Code the Classics - Volume II - macOS Guide

![Code the Classics - Volume 2](/assets/images/prj_ctcv2/Code_the_Classics_vol_2_Fix.jpg)

A few weeks ago, I was lucky enough to be gifted a physical copy of [Code the Classics – Volume II](https://store.rpipress.cc/collections/books/products/code-the-classics-volume-ii) published by Raspberry PI Press.

I had originally purchased the e-version via [Humble Bundle](https://www.humblebundle.com/books/raspberry-pi-and-retro-gaming-by-raspberry-pi-press-books?hmb_source=&hmb_medium=product_tile&hmb_campaign=mosaic_section_1_layout_index_1_layout_type_threes_tile_index_3_c_raspberrypiandretrogamingbyraspberrypipress_bookbundle) but struggled to get any of the code to run, going to say it was due to “e-book fatigue”.

I’ve put the below steps together to help anyone wanting to get the games up and running quickly.

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

   **Playing the Games**

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
    
