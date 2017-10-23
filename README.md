# Roland SE-02 Mods

![](https://c1.staticflickr.com/5/4470/23565982808_7e845ae9a8_c.jpg)

___This project is in no way affiliated with Roland, Studio Electronics, or anyone else.___

The Roland SE-02 is a fantastic-sounding synthesizer that suffers from having a tiny user interface. I've found that adjusting values with the stiff-turning (but surprisingly wobbly) switches leads me to accidentally nudge tiny and very sensitive pots like the oscillator pitch. 

Also it's economically not something everyone would want to do, I've decided to give a go at creating a new front panel. Rather than do something destructive with the existing panel, and solder new pots/controls in place and use flying wires to connect to a panel, I've decided to create a new front panel from scratch.

The new front panel would be connected to the existing voice and digital board using the same mezzanine connector that Roland uses:

![Mezzanine Connector](https://c1.staticflickr.com/5/4397/37350883412_9683ebab33_c.jpg)
![Mezzanine Connector](https://c1.staticflickr.com/5/4467/23566663928_13495e024c_c.jpg)
![Mezzanine Connector](https://c1.staticflickr.com/5/4421/36748155763_2c035b64df_c.jpg)

* Mouser part number: [656-WR40PVF50N1](http://www.mouser.com/ProductDetail/JAE-Electronics/WR-40P-VF50-N1/)
* JRC Part Number: WR-40P-VF50-N1

Additionally, I would put it into a full synthesizer body, with a MIDI keyboard controller built in. The controller, unlike the 25 key version that Roland supplies, would have pitch/mod wheels and also velocity and aftertouch (channel pressure). Many of the SE-02 sounds really light up with these features, something you might never realize if you only used the 25 key keyboard Roland sells.

![](https://c1.staticflickr.com/5/4371/37371051356_6557153450_c.jpg)

Excel spreadsheet with existing UI parts (buttons, switches, pots, etc.) from the existing front panel:
[Roland SE-02 Panel Components.xlsx](Existing%20Panel/Roland%20SE-02%20Panel%20Components.xlsx)

Additional photos here:
https://www.flickr.com/photos/psychlist1972/albums/72157685399706662

# Panel/Synth Design

![Synth Mockup](https://c1.staticflickr.com/5/4447/37836820012_5bb31beed7_b.jpg)
[Larger size image](https://www.flickr.com/photos/psychlist1972/37836820012/)

The SE-02 doesn't really sound like a Moog or a Roland, so I've decided to just run with a more classic Roland design for the synth itself.


For panel graphics, [Maverick Label](https://www.mavericklabel.com/products/graphic-overlay.html) looks to be a good company. That is the company used for the Meeblip and others. Companies like Synthgraphics, Dave Smith Instruments, Moog, and others all use 10mil lexan with 3m adhesive backing.

# Controller Keyboard

Roland A-500 Pro keyboard controller is what I've used here. It has a great classic Roland-style pitch/mod wheel, and comes apart quite easily. The pitch/mod wheel also comes out as a single assembly, which is very helpful.

![A 500 Pro Pitch/Mod Wheel](https://c1.staticflickr.com/5/4503/37114598463_f2aa383f5a_c.jpg)

The keyboard has a channel pressure/aftertouch strip, as well as velocity, and uses a standard 26 pin connector for the matrix.

![A 500 Pro keyboard connector](https://c1.staticflickr.com/5/4469/37114599083_096e0c9b29_c.jpg)

![A 500 Pro pressure connector](https://c1.staticflickr.com/5/4502/37735480516_29e924a5a1_c.jpg)

It's not as nice as a Fatar, but it's available, relatively inexpensive, and easy to work with.

![Roland A500 Pro](https://c1.staticflickr.com/5/4370/37161393360_3656193bc2_c.jpg)

![Roland A500 Pro](https://c1.staticflickr.com/5/4416/23566572048_f228d71372_c.jpg)

# Additional Electronics

A more time-consuming part of the project, but one I want to do and then modify/reuse for other projects, is the performance/controller circuit. This will do the keyboard scanning, arpeggiator, additional midi controls for "hidden" SE-02 functions, pedal inputs, etc. It'll also do a MIDI merge to make sure that both the SE-02 front panel controls and the performance controls are sent out through MIDI.

Combining USB functions is out of scope. I'm going to have a separate USB connection for programming the controller vs. the MIDI/audio one that the SE-02 surfaces.

# Other interesting bits

I'm considering throwing a second SE-02 intot he box for split/stack and duophonic playing. Roland supports this in the hardware already with a poly-chain style approach, I'd just need to make sure it makes sense with the panel and whatnot. This is a wishlist item in any case, not a commitment. 


