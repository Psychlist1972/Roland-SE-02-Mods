# Roland SE-02 Mods

![](https://c1.staticflickr.com/5/4470/23565982808_7e845ae9a8_c.jpg)

_This project is in no way affiliated with Roland, Studio Electronics, or anyone else._

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

# Controller Keyboard

I'm likely to use an inexpensive Roland A-500 Pro keyboard controller. 

This is unlike other rebuilds where I'm using a Novation SL49 mkII. Despite the wooden cabinet, I want to have a Roland feel, as opposed to a Moog feel, or trackpad and joystick, so went with the Roland-style paddle for pitch/mod. This keyboard also supports velocity and aftertouch/pressure. Intent would be to remove as much as possible from it, and stick it in a cabinet not much different from either a Moog Sub 37 or Voyager. TBD.

There were some other contenders for a controller, but they either did not support aftertouch/pressure, or did not have physical (non-USB) MIDI connections.

The A500 Pro supports dedicated power connection, and also has inputs for pedals. I haven't tested pedal inputs with the SE-02 to see if they map to anything useful.

![Roland A500 Pro](https://c1.staticflickr.com/5/4370/37161393360_3656193bc2_c.jpg)

![Roland A500 Pro](https://c1.staticflickr.com/5/4416/23566572048_f228d71372_c.jpg)

I will need to test the A-500 Pro before committing to it being the right controller here. Specifically, I need to see how much I can remove, whether the MIDI, power, and pedal jacks can be easily relocated to the back, etc.

# Panel Design

Again, sticking with something that is more Roland in flavor, I will likely go with Jupiter 8 style (well, classic 80s analog synth style) LED buttons rather than silicone pads. TBD, of course.

Additionally, I'll use flat round style knobs rather than Moog-style. Jupiter 8 style knobs are impossible (or very difficult) to find, so these will be more akin to more modern Roland synths. 

I may also go with sliders for the envelope settings. TBD.

For panel graphics, [Maverick Label](https://www.mavericklabel.com/products/graphic-overlay.html) looks to be a good company. That is the company used for the Meeblip and others. Companies like Synthgraphics, Dave Smith Instruments, Moog, and others all use 10mil lexan with 3m adhesive backing.


