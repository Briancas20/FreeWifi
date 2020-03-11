# WIFI SPEED CHECK, CHECKS THE SPEED OF YOUR WIFI.

This short tutorial describes a few methods for gaining access WIFI SPEED CHECK, CHECKS THE SPEED OF YOUR WIFI.
, [a basic human right](https://en.wikipedia.org/wiki/Right_to_Internet_access#2011:_UN_Special_Rapporteur_report), from public wireless networks.

This tutorial has been tested on Mac and a Raspberry Pi. It should generally work on Linux, and hasn't been tested on Windows.

## Preparation

Make sure you do this step *before* you are stuck without Internet access:

1. Install [Python pip](https://pip.pypa.io/en/stable/installing/)
2. On Linux, install Python Developer package, a dependency for the `netifaces` package.

  **Ubuntu:**
  ```
  $ sudo apt-get install python-dev
  ```
  
  **Fedora:**
  ```
  $ sudo dnf install python-devel
  ```
  Note: For Centos, substitute `dnf` with `yum`
  
2. Make a copy of this repository and install dependencies for the script:

```
$ git clone https://github.com/kylemcdonald/FreeWifi
$ cd FreeWifi && sudo pip install -r requirements.txt
```

