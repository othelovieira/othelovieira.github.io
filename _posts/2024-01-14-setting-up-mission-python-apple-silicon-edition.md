### Setting up Mission Python – Apple Silicon Edition

A few years ago I published steps on how to setup Python and Pygame Zero on a Macbook (Intel based) to follow along with [Sean McManus’s – Mission Python: Code a Space Adventure Game](https://www.sean.co.uk/books/mission-python/index.shtm) from [No Starch Press](https://nostarch.com/missionpython).

I recently did the setup on a MacBook Air (M1 running Sonoma 14.2.1).

Below are the updated steps -


```
*** Installing Python 3.12.1 ***
```

Download Python 3.12.1 from https://www.python.org/downloads/macos/

Double click the installer and follow the on-screen instructions.

Once installed Open Terminal (Cmd+Spacebar, type Terminal, press Enter).

```
  Type which python3, at the prompt
```
You should get the below result-

/usr/local/bin/python3


```
*** Install pip3 ***
```

pip3 (23.2.1) is automatically installed with Python3 (3.11.5), I would recommend checking if there is a newer version, in Terminal>

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
