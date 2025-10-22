# HOPE-Final-Project

Link to BOM: https://docs.google.com/spreadsheets/d/1Rpm_pfE3mdXuIPg5WMGOXxpce0Wy2xsk9B6LXBKKtQ0/edit?usp=sharing

In the BOM, there are some components that are really small (202) and a few marketplace products due to the fact that I literally could not find any that matched our specifications. I'll try having a better look later as well. 

The schematic has a few errors in ERC, but I think they are not faults that break function. For example, one of them is that the VBUS pin on the USB receptacle is not driven by an output power pin, but we are not using that to supply power to any components (using it for sensing when a USB is connected to let the MCU know)
