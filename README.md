**Spreading joy- A skirt**

**Description:** A fun skirt that changes colour when you hug someone and becomes the colour of their clothing, and lights up in different colours.
Using LEDs that make the skirt light up and a colour sensor to make the skirt change colour!

**Idea:** My idea was to create a fun project that allows you to change the colour of your skirt when you hug someone. I wanted combine fashion and electronics in a fun way that allows people to enjoy and interact with their clothing. Additionally the projects aims to spread love and happiness by encouraging people to hug others and simply make people smile by this simple act.

**Prototypes and rejected versions:**
Problems I faced- my colour sensor needed to be on the outside of the skirt as for it to detect colour it needs to have no obstacles obstructing its view, however, it also has to look nice and the wires or the colour sensor cannot directly be visible. Secondly, the colour sensor needed to be surrounded by some sort of housing so that it did not detect the colour of the skirt itself or have any other interference. My initial models did not have a housing for the colour sensor so the values predicted it by it were not accurate. The RGB strip also needed to be cut and each individual piece soldered to the next which was a time consuming and difficult task. A 12V battery supply was also too large to fit a portable light skirt that you can dance in, but all the long RGB strips were only powered by a 12V power supply. Additionally, I struggled a lot with calibrating my colour sensor and ensuring it can detect the colours in my surroundings.

**Paper prototype:**
For my paper prototype, I wanted to see how I would place the led strip on the skirt, and I wanted to try seeing where all my wiring would go so that it would not hurt the person wearing the skirt and would not be visible. I also wanted to see how I could hide the LED strip so that I could ensure the person wearing it had a fashionable skirt. I thus came up with the idea of having 2 layers for my skirt, the first inner layer where the LED strip was secured and the second outer translucent later that allows the light to pass through while covering the LED strip and also houses the sensor. The bubble wrap does this in the prototype and theres a small inner pocket that houses all the wiring in the skirt.
Solutions and changes: To ensure my colour sensor is on the outside of the skirt and can detect different colours, I came up with the idea of making a second translucent outer layer to my skirt that can hold the colour sensor easily and still look nice. Then to solve the problem of housing my colour sensor I 3d printed a case for my colour sensor that ensures no other colours can interfere with it and affect it. Then to ensure I didn’t have to solder each individual RBG strip to a belt at the top of the skirt, we decided to connect the RBG strips to each other using wires. We also decided that a 9V battery would be good enough to power a 12V RGB strip and it would still glow brightly and be portable.

**Objectives of the project:**
Detect the colour of the surroundings easily
Change the colour of the skirt according to the detected colour of the surroundings Have a skirt that looks cool and changes colour

**Materials: **
Skirt :
A plain straight skirt
An outer translucent skirt
Fabric glue or fevikwik
Thread and a small stiching set, including scissor

LED strip:
10m total RBG LED strip - https://www.amazon.in/Protium-Lights-Multi-Colors-waterproof-Controller/dp/B08YKBRSB4/ref=sr_1_11? crid=3LQOJ6J16MNGD&keywords=rgb+neopixel+led+strip&qid=1696230770&sprefix=rbg+neopixel+led+strip%2Caps%2C191&sr=8-11      
Wires
Soldering iron

Colour sensing:
tcs 3200 colour sensor- https://www.amazon.in/Robodo-Electronics-SEN41-Recognition-Detector/dp/B0787N1L24/ref=sr_1_2? crid=332Y5Y5U4F87S&keywords=colour+sensor+for+arduino&qid=1696230879&sprefix=colour+sensor+%2Caps%2C194&sr=8-2
3d printed and designed enclosure or housing

Power supply:
Rechargeable Batteries (9V)- https://www.amazon.in/Envie-2xC-Size-Rechargeable-Batteries/dp/B00BOLC962/ref=sr_1_1_sspa? crid=8MHD2RY7D6UC&keywords=9v+rechargeable+battery&qid=1696230562&sprefix=9V+rechargeable+batter%2Caps%2C213&sr=8- 1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1
Charging Module- https://www.amazon.in/Charger-Charge-Control-Rechargeable-Batteries/dp/B0BCG3W4L5/ref=sr_1_1? crid=1IOIABLJQ45KZ&keywords=9v+rechargeable+battery+charger&qid=1696230614&sprefix=9v+rechargeable+battery+cha%2Caps%2C 1
Power Convertor if using less than 9V or if using 5V (the dress will not be portable if this is used

Controller:
Arduino nano - https://www.amazon.in/Maison-Nano-Board-CH340-ATmega328P/dp/B0C1H271SP/ref=sr_1_5? crid=2E5Y3JJTCRWWO&keywords=arduino+nano&qid=1696230648&sprefix=ardui%2Caps%2C207&sr=8-5

**Skills used in the project:**
Throughout the course of this project I learnt a variety of skills and was able to apply a lot of the skills I learnt in both the online and offline sessions at the asylum. I got to work a lot with arduino which helped reinforce all the skills I learnt in the electronics session. I also got to use C while coding the arduino to work and this further strengthened my coding skills. I also worked a lot on my soldering skills which helped me become much better at soldering and more comfortable with all the tools. Additionally, all the CAD sessions were very helpful while designing the case for the colour sensor and I also learnt how to 3d print and design 3d prints. Additionally, all the guidance and support of all our mentors made this project possible and I also learnt many new skills through it like troubleshooting and using a multimeter.
Working of Individual blocks:
The first block was the colour sensor. To test the colour sensor, first you needed to calibrate the colour sensor using a black paper and a white paper. Then once the colour sensor was calibrated we put the minimum and maximum RGB values into the code that runs the colour sensor, this code gave us RGB values. This allowed me to test the colour sensor. We then tried connecting the sensor to an RBG led to see how this was working. The second block was the RGB led strip, this has to be cut to the length of the skirt and then soldered to each other. Then we tested out the working of the strip using a power and supply.

**Logic of the complete program:**
1. When you hug someone, the colour sensor identifies the colour of their clothing and reads the RBG values. 2. These RGB values are then transferred onto the RBG LED strip which changes colour according to this.
3. All the LEDs then change colour and become a certain colour making your dress change colour.
In the end we connected the two blocks to make the final skirt which changes colours, spreading more hugs.
Assembly:
To assemble the skirt, first take the skirt and measure the lengths and distances at which you want to space the led strips. Then cut the LED strips according to the length and cut wires according to the distance between LED strips. Then solder the strips and wires together to form a long connected strip. Then connect the led strip to the arduino and colour sensor and to the power supply. Then stick the strips onto the skirt, and place all the wiring except for the colour sensor in an inner pocket in the skirt. Then place the colour sensor on the center of the outter skirt and stick it there. The skirt is now ready.


**References and sources:**
For inspiration on design and ideas:
https://learn.adafruit.com/florabrella/overview
https://learn.adafruit.com/chameleon-scarf
For help with the code and troubleshooting:
https://dnschecker.org/convert-rgb-to-pantone-pms.php https://dronebotworkshop.com/arduino-color-sense/
https://www.youtube.com/watch?v=uczaIETo_Jg https://randomnerdtutorials.com/arduino-color-sensor-tcs230-tcs3200/https://github.com/nthnn/TCS3200
