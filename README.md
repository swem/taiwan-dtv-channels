# taiwan-dtv-channels
DVB-T channels list for Digital television in Taiwan.

## Usage
Insert dvt-t usb stick into PC. Download [channels.conf](https://raw.githubusercontent.com/swem/taiwan-dtv-channels/master/channels.conf) and open channels.conf with VLC
```
wget https://raw.githubusercontent.com/swem/taiwan-dtv-channels/master/channels.conf
sudo apt-get install vlc
vlc channels.conf
```

## Re-scan channel
Verified on Ubuntu 16.04
```
sudo apt-get install -y dvb-apps
scan /usr/share/dvb/dvb-legacy/dvb-t/tw-All >channels.conf
```
