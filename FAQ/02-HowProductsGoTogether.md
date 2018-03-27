# How OpenBCI products go together?

![image](../assets/images/How_products_go_together.png)

## What products should I get?

If you are new to OpenBCI or you are just curious about our products don’t fret! Here is a detailed explanation of what you need to get started:

The first component you would need is one of our 3 Biosensing Boards. You will select a board depending on how many electrodes you want to analyze data from. In general, with additional channels, you have additional spatial resolution that enables more diverse types of research. We offer three different boards, the [Ganglion Board](https://shop.openbci.com/collections/frontpage/products/pre-order-ganglion-board) (4 channels at a sample rate of 200Hz), the [Cyton Board](https://shop.openbci.com/collections/frontpage/products/cyton-biosensing-board-8-channel?variant=38958638542) (8 channels at a sample rate of 250Hz), and the [Cyton + Daisy Boards](https://shop.openbci.com/collections/frontpage/products/cyton-daisy-biosensing-boards-16-channel?variant=38959256526) (16 channels at a sample rate of 125Hz). Each channel lets you plug one electrode into them, so the more channels you have the more electrodes you can play with. If you are purchasing the Ganglion board and you are working primarily on Windows or Linux computers you will need to get our [Bluetooth Dongle](https://shop.openbci.com/collections/frontpage/products/csr-4-0-bluetooth-dongle?variant=34793373070). Note that if you are using a Mac or you are using the Cyton board, you don't need this dongle.

The boards sample rate is limited by the bluetooth bandwidth. In order to increase the sample rate, you can purchase the [WiFi Shield](https://shop.openbci.com/collections/frontpage/products/wifi-shield?variant=44534009550). The [WiFi Shield](https://shop.openbci.com/collections/frontpage/products/wifi-shield?variant=44534009550) increases the sample rate by transmitting the data via WiFi as opposed to Bluetooth. You can stream data over your home WiFi network or directly from your WiFi Shield. The WiFi Shield is controlled through HTTP requests and can send JSON objects with data in nano volts. With the WiFi Shield connected: 

* The Cyton can stream data at 250Hz, 500Hz, 1000Hz, 2000Hz, 4000Hz, 8000Hz and 16000Hz. 
* The Cyton + Daisy can to stream data at 250Hz, 500Hz, 1000Hz, 2000Hz, 4000Hz, and 8000Hz. 
* The Ganglion can stream data at 200Hz, 400Hz, 800Hz, 1600Hz, 3200Hz, 6400Hz, and 12800Hz

Now that you have the board, the second thing you need to get started is a set of electrodes (or a headset, we’ll talk about it after). Our Boards have male header connectors, so you would need to get electrodes that are compatible. If you are interested in mainly doing EMG or ECG, we recommend you use our [EMG/ECG Snap Electrode Cables](https://shop.openbci.com/collections/frontpage/products/emg-ecg-snap-electrode-cables?variant=32372786958) with [EMG/ECG Foam Solid Gel Electrodes](https://shop.openbci.com/collections/frontpage/products/skintact-f301-pediatric-foam-solid-gel-electrodes-30-pack?variant=29467659395) (30/pack), these electrodes are a ready to go solution and plug in directly into our Biosensing boards. If you want to be able to do EEG as well as EMG and ECG, we recommend you get our [Gold Cup Electrodes](https://shop.openbci.com/collections/frontpage/products/openbci-gold-cup-electrodes?variant=9056028163) with [Ten 20 Paste](https://shop.openbci.com/collections/frontpage/products/ten20-conductive-paste-2oz-jars?variant=31373533198). You can affix these electrodes (almost) everywhere with some medical tape, which allows you to measure EEG, EMG, and ECG. If you already have your own electrodes, or have an electrode cap with touch proof connectors, you can still use them with our Biosensing Boards, by purchasing our [Header Pin to Touch Proof Electrode Adapter](https://shop.openbci.com/collections/frontpage/products/touch-proof-electrode-cable-adapter?variant=31007211715). 

Another way to go is to purchase the [Mark IV headset](https://shop.openbci.com/collections/frontpage/products/ultracortex-mark-iv). At its core the Mark IV is a frame with dry electrodes, that allows you to affix the dry electrodes to the scalp without having to use any paste. If you are mainly interested in EEG and do not want to have to go through the hassle of using EEG Paste on your hair, this is the way to go. You can purchase the Mark IV with either 8 electrodes or 16 electrodes (you don’t need to purchase extra electrodes). The Mark IV comes in 3 configurations, Print it Yourself, Unassembled, and Pro-Assembled. The Print it Yourself version is great if you have a 3D printer and you are able to print some of the parts yourself. The Print it Yourself version includes all of the electrodes, cables, and all of the other parts that aren’t 3D printable. The Unassembled version comes with all the necessary materials to build the headset, sort of like a puzzle but easier. You can check the [assembly guide](http://docs.openbci.com/Headware/01-Ultracortex-Mark-IV) for instructions. If you don’t want to bother with assembly or 3D printing parts, you can buy an already assembled headset, our Pro-Assembled Mark IV. Note that neither headset comes with a Biosensing board.

We recommend that if you are getting the 8 Channel Mark IV you pair it with the Cyton board, and if you are getting the 16 Channel Mark IV you pair it with the Cyton + Daisy Boards. Nevertheless you can use all of our boards with the Mark IV. 

In addition to OpenBCI products, we also sell compatible products like the [Myoware Muscle sensor](https://shop.openbci.com/collections/frontpage/products/myoware-muscle-sensor?variant=29472011267) and the [Pulse Sensor](https://shop.openbci.com/collections/frontpage/products/pulse-sensor?variant=22543672899). Both can be connected to the Cyton and Ganglion Boards to add more capabilities, they are also both compatible with the OpenBCI GUI.

## What about Software?

You can use both the Cyton and the Ganglion with the OpenBCI GUI to get started with reading your brainwaves. Here is the [tutorial](http://docs.openbci.com/OpenBCI%20Software/01-OpenBCI_GUI) on installing the OpenBCI GUI. 

Regarding third party software, the Cyton board is compatible with:

* [OpenViBE](http://openvibe.inria.fr/drivers-openbci/)
* [neuromore studio](https://doc.neuromore.com/?cat=0&page=2) (Bio-data acquisition, processing and visualization software)
* [BrainBay](http://www.shifz.org/brainbay/) (Open-source neurofeedback application, OpenBCI tutorial [here](https://sites.google.com/site/biofeedbackpages/brainbay-openbci) and another [here](http://www.autodidacts.io/use-openbci-with-brainbay-on-ubuntu-linux-and-wine/))
* [BioEra](http://www.proatech.com/be/manual.html#_OpenBCI) (Visual designer useful for analyzing signals in real time)

The Ganglion board is currently compatible with: 

* [BioEra](http://www.proatech.com/be/manual.html#_Toc477624700)
* [BrainBay](http://www.shifz.org/brainbay/) (Open-source neurofeedback application)

Currently new drivers are being developed to add OpenBCI compatibility to Bioexplorer (tbd), BCI2000 (tbd), etc.

In addition, if you are really comfortable with programming you can use [MatLab](http://docs.openbci.com/3rd%20Party%20Software/01-Matlab) or [Python](http://docs.openbci.com/3rd%20Party%20Software/04-LSL) tools to analyze the raw data of your OpenBCI boards.
