# PSU-Plus
The PSU-Plus is the spiritual successor to Noah's RVL-PSU, designed for ease of assembly and versatility across many micro-type builds.

Like it's predecessor, the PSU-Plus has 1V, 1.15V, 3.3V and 5V regulators. Where the PSU-Plus differs is the addition of a 1.8V regulator for builds that remove the LDO from the Wii (such as Wesk's GC Micro and the GC Nano).

I designed this board when the TLV62130RGTR regulators were out of stock as a drop-in replacement for the RVL-PSU. It has the exact same board outline dimensions, as well as the same screw hole layout / dimensions.

I have added an additional VIN pad for builds that use VIN elsewhere in the project (such as feeding 12V to the audio amplifier / sensor bar in the Noldendo Miicro). I have also added jumper pads to enable / disable the 1v8 and 5v regulars if your build does not require either of them.

**VIN Min: 5V**\
**VIN Max: 18V**\
**Max current output (per regulator): 3A**

<img src="https://github.com/CrazyGadgetMods/PSU-Plus/blob/main/images/render.png" height=600> <img src="https://github.com/CrazyGadgetMods/PSU-Plus/blob/main/images/assembled.jpg" height=600>

If you are interested in buying one of these boards pre-assembled, I sell them on my [Etsy Store](https://www.etsy.com/listing/1510321427/psu-plus-power-board-for-wii-micros).

## Credits
- [YveltalGriffin](https://github.com/mackieks): Holding my hand while I did the layout of the board and answering my infinite questions
- [Noah](https://bitbuilt.net/forums/index.php?members/noah.1/): Making the original [RVL-PSU](https://bitbuilt.net/forums/index.php?threads/rvl-psu.3335/)
- [BitBuilt](https://bitbuilt.net/): Being the best modding community out there!

## License
Solderpad Hardware License v2.1
