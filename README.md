# WinRAR-Keygen

[中文版README](README.zh-CN.md)

## 1. What is WinRAR?

WinRAR is a trialware file archiver utility for Windows, developed by Eugene Roshal of win.rar GmbH. Command line version for Linux/macOS is also available.

It can create and view archives in RAR or ZIP file formats and unpack numerous archive file formats. 

WinRAR is not a free software. If you want to use it, you should pay to [__RARLAB__](https://rarlab.com/) and then you will get a license file named `rarreg.key`. 

This repository will tell you how WinRAR license file `"rarreg.key"` is generated. 

## 2. How is "rarreg.key" generated?

See [here](doc/how-does-it-work.md).

## 3. How to build?

This project supports both __Windows__ and __Linux/macOS__ platform.

To compile, see [here](doc/how-to-build.md).

PS: Thanks to Multi for providing unix support.

## 4. How to Use?

```
Usage:
        winrar-keygen.exe <your name> <license type>

Example:

        winrar-keygen.exe "Rebecca Morrison" "Single PC usage license"
  or:
        winrar-keygen.exe "Rebecca Morrison" "Single PC usage license" > rarreg.key
```

```console
$ winrar-keygen.exe "DoubleLabyrinth" "Single PC usage license"
RAR registration data
DoubleLabyrinth
Single PC usage license
UID=d2fb7cb15c078a3def58
6412212250ef58bef21cdcb49ca34b7040112cae5a512f1adad1a8
f6d2ee8c382fe64f8e3d6035c6ab9048e2c5c62f0238f183d28519
aa87488bf38f5b634cf28190bdf438ac593b1857cdb55a7fcb0eb0
c3e4c2736090b3dfa45384e08e9de05c5860d3051942adf2db9d96
e2ec37f1cfae00b3e2455093b90e4e352f016f6b9853c735d45fb4
01f9cbb91d3f3ac5664511229f8c9b0a9e1d61a2e087b481607e91
bfc8a83414f6807d31a5f8c587513aa54f9b1249ad804214409316
```

