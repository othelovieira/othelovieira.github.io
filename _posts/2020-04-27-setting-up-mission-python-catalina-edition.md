### Setting up Mission Python – Catalina Edition

```
Update: I have updated the below post to use Python 3.11.5 and has been tested on macOS Catalina, Big Sur and Monterey.
```

A couple of years ago I picked up a copy of [Sean McManus’s – Mission Python: Code a Space Adventure Game](https://www.sean.co.uk/books/mission-python/index.shtm) from [No Starch Press](https://nostarch.com/missionpython).

In my opinion, it’s still a great book to get into coding a game in Python using Pygame Zero.

The book explains how to set up your adventure on a Windows PC and Raspberry Pi, but been a macOS user, I decided to post the steps below on to set up your adventure on a Mac.

macOS 10.15 (Catalina) now ships with Python3 but I would recommend installing a second version as not to “upset” the OS native shipped version.

The book recommends Python 3.6.6 (at time of writing), I have based this post on Python 3.11.5

```
*** Installing Python 3.11.5 ***
```

Download Python 3.11.5 from https://www.python.org/downloads/macos/

Double click the installer and follow the on-screen instructions.

Once installed Open Terminal (Cmd+Spacebar, type Terminal, press Enter).

```
  Type which python3, at the prompt
```
You should get the below result-

/Library/Frameworks/Python.framework/Versions/3.11/bin/python3


```
*** Install pip3 ***
```

pip3 (23.2.1) is automatically installed with Python3 (3.11.5), I would recommend updating it to the latest, in Terminal>

```
  Type pip3 install --upgrade pip

  Type pip3 --version
```
You should get the below result-

pip 23.2.1 from /Library/Frameworks/Python.framework/Versions/3.11/lib/python3.11/site-packages/pip (python 3.11)

```
Install Pygame Zero
```

In Terminal>
```
  Type pip3 install pgzero

  Type pip3 show pgzero
```
You should see the below in the results-

Name: pgzero

Version: 1.2.1

Once the above has been completed, you are ready to test Mission Python on your Mac.

Download the Mission Code file from https://www.sean.co.uk/books/mission-python/index.shtm

Once the file has downloaded and unzipped from within Terminal move to the escape folder (I unzipped the into my Downloads folder to test).

  Open Terminal (Cmd+Spacebar, type Terminal, press Enter).

```
  Type cd Downloads

  Type cd escape

  Type pgzrun escape.py

```

Once you have done the above the game should start. You are now ready to begin your adventure with Mission Python.

