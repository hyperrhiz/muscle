**Materials:**

**Hardware:**

- •Tensor Bandage (quantity: 1)
- •Arduino Gemma (quantity: 1)
- •Adafruit accelerometer (quantity: 1)
- •Alligator clips (quantity: 1)
- •Novelty shock pen (variants on the shock pen may work, including but not limited to shock highlighters, hand buzzers and electric gum packs, so long as the shock mechanism includes an inductor (typically these are encased in a blue plastic with a white circuit attached at the top... which you will probably only be able to determine by opening the instrument) (quantity: 1)
- •3.7v lithium ion battery (quantity: 1)
- •8 x 8 LED matrix (quantity: 1)
- •Wires (quantity: 9)

**Software:**

- •Arduino IDE
- •Arduino sketch for this project: [https://github.com/hyperrhiz/muscle](https://github.com/hyperrhiz/muscle/blob/master/muscle.ino)

**Tools:**

- •Soldering iron
- •Needle and thread
- •glue gun

**Wiring Chart:**

![Figure 1 Breadboard design of the muscle developer](https://github.com/hyperrhiz/muscle/blob/master/img/image001.png "")

_Figure 1 Breadboard design of the muscle developer_

![Figure 2 Wiring schematic for the muscle developer](https://github.com/hyperrhiz/muscle/blob/master/img/image002.png "")

_Figure 2 Wiring schematic for the muscle developer_

![Figure 3 muscle developer](https://github.com/hyperrhiz/muscle/blob/master/img/image003.png "")

_Figure 3 Muscle developer; from top to bottom: accelerometer, LED backpack, 3.7v battery, Arduino Gemma microcontroller, shock pen components, sewn onto a tensor bandage._

![Figure 4 The wiring to connect the shock pen circuit to the Arduino](https://github.com/hyperrhiz/muscle/blob/master/img/image004.png "")

_Figure 4 The wiring to connect the shock pen circuit to the Arduino. Most shock pens I’ve seen opened up follow this same design. _**_Note that both white wires are connected to the center, and not to any of the sides._**_

![Figure 5 The shock pen circuit as seen from the opposite side](https://github.com/hyperrhiz/muscle/blob/master/img/image005.png "")

_Figure 5 The shock pen circuit as seen from the opposite side. The white wire connected to the white circuit and the yellow wire connected to the blue voltage stepper must be in contact with the skin in order for the shock to be felt._

**Arduino Code:**

- •Note: this code was modified from code supplied for another Arduino project on the Learn Adafruit website: [https://learn.adafruit.com/trinket-slash-gemma-space-invader-pendant/overview](https://learn.adafruit.com/trinket-slash-gemma-space-invader-pendant/overview)
- •Further note: Matt Frazer must be credited for figuring out the practical logistics of the code count. While I had my own ideas of how to use them, given the tight deadline I was under to complete this project Matt's solution was the most efficient and achievable, which remains for me an interesting reflection about both the creative and collaborative process. If you are to use the code that Matt and I tweaked from Adafruit.com, I would suggest tinkering with it too. 

**Instructions for making the exact same object:**

- •Wire your materials as shown in the wiring chart. Solder in place.
- •The novelty shock pen will come with attached wires which will likely need to be replaced (I found myself having to do this _during_ an exhibition featuring of the device, so I would suggest doing this along with the rest of the wiring). Clip the spring coils off the original wires and replace these with thicker, more securely soldered wires. Tip: Make sure to solder the wires to the correct place (I ended up buying a second shock pen because I thought I had broken the first one, but it turns out I had simply re-attached one wire to the wrong spot on the diode).
- •Upload the provided code to the Arduino Gemma
- •Reinforce the transistor connections with a glue gun (optional, but the device is very delicate otherwise)
- •Sow the device to the tensor bandage. Use picture for reference as needed.
- •Attach the battery to the Gemma
- •Lift, ‘bruh!’

**Instructions for critically making this object:**

- •Reflect on any maker project.
- •Consider the factors of its production, including the positionality of the maker and the materials.
- •Think about the systemic pressures that contributed to the production of this maker object.
- •Build a better system. Learn tools and skills as needed.