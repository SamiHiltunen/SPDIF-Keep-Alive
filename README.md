# SPDIF Keep Alive
SPDIF Keep Alive is a daemon for OS X that prevents the optical audio output from sleeping. Normally the optical audio output goes to sleep after 30 seconds of inactivity (as in no sound has been played). After waking up from the sleep, the beginning of the audio starting to play will be cut off by about 1 second. This daemon fixes the issue by playing a silent sound every 30 seconds.

## Installation

The installation requires administrator privileges. Open a terminal and type the following commands:
```Batchfile
git clone https://github.com/SamiHiltunen/SPDIF-Keep-Alive.git
cd SPDIF-Keep-Alive
./install.sh
```

The daemon will be launched after the installation and will be always running in the background. 