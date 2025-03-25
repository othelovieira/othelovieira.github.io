## Code the Classics - Volume II - Win 10/11 Guide

![Code the Classics - Volume 2](/assets/images/prj_ctcv2/Code_the_Classics_vol_2_Fix.jpg)

A few weeks ago, I was lucky enough to be gifted a physical copy of [Code the Classics – Volume II](https://store.rpipress.cc/collections/books/products/code-the-classics-volume-ii) published by Raspberry PI Press.

I had originally purchased the e-version via [Humble Bundle](https://www.humblebundle.com/books/raspberry-pi-and-retro-gaming-by-raspberry-pi-press-books?hmb_source=&hmb_medium=product_tile&hmb_campaign=mosaic_section_1_layout_index_1_layout_type_threes_tile_index_3_c_raspberrypiandretrogamingbyraspberrypipress_bookbundle) but struggled to get any of the code to run, going to say it was due to “e-book fatigue”.

I’ve put the below steps together to help anyone wanting to get the games up and running quickly.

  **Installing Python 3.13.1**

  - [Download Python 3.13.1](https://www.python.org/downloads/release/python-3122/)

    Note - I have downloaded the Windows installer (ARM64) because I am running Win 11 - Arm64 in VMware Fusion, but if you are using an Intel Mac with "Virtual Windows" or a bare metal Windows PC would recommed downloading Windows installer (64-bit). 
  
  - Double click the installer on the first install screen "tick" Add python.exe to PATH and then select install now.
  - Once installed open Windows Terminal (Windows Key>Windows Terminal) and type the below -

    ```
    python --version    
    ```

    You should get the below results

    ```
    Python 3.13.1
    ```
    
  **Installing Pygame Zero**

  - In Windows Terminal run the below command
    
    ```
    pip3 install pgzero
    ```

    You should get the below results

    ```
    Successfully installed numpy-2.2.2 pgzero-1.2.1 pygame-2.6.1
    ```

    Note - To test that all has been installed correctly, run the below command

    ```
    py -m pygame.examples.aliens
    ```

**Installing Git**

  - [Download Git 2.28.1 (latest as of this writing)](https://git-scm.com/downloads)
  - Double click the installer and follow the on-screen instructions (You can leave all default settings).

    Note - To check that it has been installed correctly, run the below command in Windows Terminal

    ```
    git --version
    ```

    You should get the below results

    ```
    git version 2.47.1.windows.2
    ```
    
 **Install a Joystick Keyboard Mapper (Optional)**

   As mentioned in the PI 400 install, I like using a Joystick Keyboard Mapper for Windows I use [reWASD](https://www.rewasd.com)

**Playing the Games**

  Since we just want to play the games for now, I will clone the "Games" repository under the Downloads directory

  The below is all run in Windows Terminal

  Change to the Downloads dirctory (I am assuming you are in the User directory)

    cd Downloads 

  Clone the "Games" from the books GitHub repository
  
    git clone https://github.com/raspberrypipress/Code-the-Classics-Vol2

  Once the clone has completed move into the games direcorty

    cd Code-the-Classics-Vol2

  You can now list the games

    ls

  You should see the below listing

    Mode                 LastWriteTime         Length Name
    ----                 -------------         ------ ----
    d-----        2025/01/23     05:29                avenger
    d-----        2025/01/23     05:29                beatstreets
    d-----        2025/01/23     05:29                cover
    d-----        2025/01/23     05:29                eggzy
    d-----        2025/01/23     05:29                kinetix
    d-----        2025/01/23     05:29                leadingedge
    -a----        2025/01/23     05:29             25 .gitignore
    -a----        2025/01/23     05:29           1172 README.md

  Let's play Beat Streets (Double Dragon Inspired)

    cd beatstreets
    pgzrun beatstreets.py
 
    
    
    
    


