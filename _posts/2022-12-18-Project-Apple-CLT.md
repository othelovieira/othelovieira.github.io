### Apple Command Line Tools - Field Notes

The below is based on an Intel based MacBook Air (MacBookAir7,2) running macOS Monterey (v12.6.2).

#### Check if the Xcode Command Line Tools are installed.

```
% xcode-select -p
```

If you get something similar to the below the Tools are installed

```
/Library/Developer/CommandLineTools
```

#### Check the version installed.

```
% clang --version
```

You should get the below output

```
Apple clang version 14.0.0 (clang-1400.0.29.202)
Target: x86_64-apple-darwin21.6.0
Thread model: posix
InstalledDir: /Library/Developer/CommandLineTools/usr/bin
```

Looking at the above output I have version 21.6.0 installed

#### Install Xcode Command Line Tools.

```
% xcode-select —install
```

#### Uninstall/Reinstall the Xcode Command Line Tools.

```
% xcode-select -p
```

You should get the below output

```
/Library/Developer/CommandLineTools
```

Remove the Tools folder (This will depend on the above output and command run at your own risk).

```
% sudo rm -rf /Library/Developer/CommandLineTools
```

Verify the Tools have been removed

```
% xcode-select -p
```

You should get a similar output to the below

```
xcode-select: error: unable to get active developer directory...
```
