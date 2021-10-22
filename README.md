[![YouTube Channel Views](https://img.shields.io/youtube/channel/views/UCz5BOU9J9pB_O0B8-rDjCWQ?label=YouTube&style=social)](https://www.youtube.com/channel/UCz5BOU9J9pB_O0B8-rDjCWQ)

# We're Doomed - A Fear and Greed index visualiser for Bitcoin

This code visualises the [Fear and Greed Bitcoin index](https://alternative.me/crypto/fear-and-greed-index/visualiser) using the Doom health monitor icon on a 128x128 RGB OLED (**SSD1351**) screen. It can easily be adapted to pretty much any single index that can be generated by the computer via web scraping or other means (eg. how long since a plant was watered, hard disk space remaining, unread email count etc etc)

The Fear and Greed Index is a multifactorial Bitcoin market sentiment analysis. This code is just a simple tool that pulls that index and visualises it in a window inspired by the health status graphic from Doom. Doom is a first-person-shooter from the 1990s.

- Low health images used for low index value  (**Fear**) 
- High health images used for high index value (**Greed**)

This does not mean greed is good, m'kay?

# Hardware

Uses a Waveshare 1.5 inch RGB OLED, 128 x 128 pixels. Tested with Raspberry Pi Zero. **TO DO: Pico or STM32 Version**

# Installation

Follow the [setup instructions](https://www.waveshare.com/wiki/File:1.5inch_OLED_Module_User_Manual_EN.pdf) for the OLED screen. 

Clone this repository:

    git clone https://github.com/llvllch/doomed.git
    cd doomed

Install the required Python3 modules
```
python3 -m pip install -r requirements.txt
```

# Running

To start the code running, issue the command: 

    python3 main.py

# Acknowlegements

- The default images are based on the sprite set [shared online](https://spritedatabase.net/display.php?object=549) by FalconDelta.
- Doom - https://en.wikipedia.org/wiki/Doom_(1993_video_game)
- `OLED_Driver.py` from Waveshare

# Licence

GPL 3.0
