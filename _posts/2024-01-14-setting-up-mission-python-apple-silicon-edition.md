### Setting up Mission Python – Apple Silicon Edition

A few years ago I published steps on how to setup Python and Pygame Zero on a Macbook (Intel based) to follow along with [Sean McManus’s – Mission Python: Code a Space Adventure Game](https://www.sean.co.uk/books/mission-python/index.shtm) from [No Starch Press](https://nostarch.com/missionpython).

I recently did the setup on a MacBook Air (M1 running Sonoma 14.4.1).

Below are the updated steps -

**Installing Python 3.12.3**

  - Download Python 3.12.1 from https://www.python.org/downloads/macos/
  - Double click the installer and follow the on-screen instructions.
  - Once installed Open Terminal (Cmd+Spacebar, type Terminal, press Enter).
  - Type which python3, at the prompt.

     You should get the result - /Library/Frameworks/Python.framework/Versions/3.12/bin/python3

**Installing pip3**

  pip3 (24.0) is automatically installed with Python3 (3.13.3), I would recommend checking if there is a newer     version.

  - In the Terminal type pip3 install --upgrade pip
  - Type pip3 --version

    You should get the result - pip 24.0 from         /Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages/pip (python 3.12)

**Installing Pygame Zero**

  - In the Terminal type pip3 install pgzero

    You should get the result - Successfully installed numpy-1.26.4 pgzero-1.2.1 pygame-2.5.2

Once the above has been completed, you are ready to test Mission Python on your Mac.

Download the Mission Code file from https://www.sean.co.uk/books/mission-python/index.shtm

Once the file has downloaded and unzipped from within Terminal move to the escape folder (I unzipped the into my Downloads folder to test).

  - Open Terminal (Cmd+Spacebar, type Terminal, press Enter).
  - Type cd Downloads
  - Type cd escape
  - Type pgzrun escape.py

Once you have done the above the game should start. You are now ready to begin your adventure with Mission Python. 

**Field Notes**

I recommend installing Python as per above and not via Homebrew, I have picked up issues with a blank screen when pygame is installed. 

    
            
