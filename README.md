# Notebook9-Metal-Hackintosh (OpenCore)
Samsung Notebook 9 Metal Hackintosh
for i3-7100u, i5-7200u, i7-7300u

![release](https://img.shields.io/badge/download-release-blue.svg)
-----


### Print Screen key works as touchpad toggle button. Need to fix ECs.

## Not Working

- Hibernate (It dies and does not wake up. Battery should be removed physically.)
- Internal MicroSD Reader ([Sinetek-rtsx.kext](https://github.com/cholonam/Sinetek-rtsx) might solve it)

## Working

- Intel HD Graphics 620 QE/CI
- Realtek ALC256
- SpeedStep
- USB 3.x Type A & C
- Battery
- I2CHID Touchpad
- HDMI External Display
- Brightness Control
- Fn Key Brightness & Sound Control
- Intel AC8265 Wi-Fi Adapter ([Black80211-Catalina](https://github.com/usr-sse2/Black80211-Catalina) alpha 3 can use AirPort menu. Need to update OpenCore 0.6.1)
- Intel Bluetooth
- Realtek RTL8111 Ethernet
- and so much more
