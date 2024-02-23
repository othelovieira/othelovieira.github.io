### Installing Homebrew on a MacBook Air (M1) - Field Notes


I recently had to install the Homebrew Package Manager on a Macbook Air (M1 running Sonoma 14.3).

Below are the steps (Field Notes) that I ran through via the Termainal (Cmd+Spacebar, type Terminal, press Enter).


Install Xcode Command Line Tools 

```
xcode-select --install
```

Install Homebrew [updated command link](https://brew.sh)

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Set Homebrew Path

```
export PATH=/opt/homebrew/bin:$PATH
export PATH=/opt/homebrew/sbin:$PATH
```
Check Homebrew is Installed and Ready

```
brew doctor
```


