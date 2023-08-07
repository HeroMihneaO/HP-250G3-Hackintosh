# HP-250G3-Hackintosh
So I decided to hackintosh my old Hp laptop for fun and I think the end result is actually good.
# Specifications
CPU: Intel core i3 4005u
iGPU: Intel HD 4400
Ram: 4gb ddr3
Trackpad: Synaptics trackpad
Ethernet:Integrated Realtek 10/100 NIC
Wifi: Some mediatek wifi card so no wifi (see in What's not working)
# What Works
-gpu acceleration
-sound
-Keyboard and Trackpad(see bugs)
-Ethernet
-webcam
-usb ports
-iServics(see in Installation guide)
-Brighntness keys (I forgot to add the kext and I won't add it anytime soon cuz I use my laptop at max brightness all the time)
# What's not woking
-Wifi and bluetooth as I said in specs the wifi card isn't supported by macOS AT ALL
-Airdop and Handoff (related to the wifi card)
# Bugs
-Wake/sleep not working correctly yet
-Trackpad gestures that require 4 fingers don't work the rest like 3 fingers up for mission control and the rest work fine
# Untested
-Hdmi
-Vga
-Hdmi audio
-3.5mm jack
#Installation Guide
For BigSur and Monterey(and anything older than Sierra)
Generate your own smbios since I won't provide mine. The smbios I used was MacBookPro11,4.
For High Sierra to Catalina
Like in the Monterey guide generate your smbios and mod under the UEFI>APFS the MinVersion and MinDate based on what the opencore install guide says
