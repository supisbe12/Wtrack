# Total time : 25 hours
**_Day 1_** - Searched for parts to plan out the schematic for this project - **5 hours**

I spent a lot of time to find out the exact footprints that I needed for each part of the schematic like capacitors, inductors, and antennas and many of the other parts.
It was difficult because I had to choose the exact needs of every part by using the datasheets.
I also spent a lot of time trying to figure out the problem that I had with importing symbol and footprints straight for LSCS or JLPCB using the ImpartGUI. This part took me like 2 hours and afterwards I asked a friend to help me and he introduced me to another plugin that allowed me to do
the same thing and it actually worked this time.

<img width="592" height="665" alt="image" src="https://github.com/user-attachments/assets/eada622d-895b-4374-9dd5-4db7bf3a0062" />

**_Day 2_** - Searched for Datasheets to connect schematics together - **7 hours**

Learned a lot about datasheets today and how to read them. It was really hard to figure out what some of the labels meant but google explained it well

<img width="739" height="497" alt="image" src="https://github.com/user-attachments/assets/3d78c793-49ac-462f-aa3c-795acd5b1cb5" />

Then I learned how to connect Antennas together and it was quite complicated with the usage of a lot of back and forth of capacitors and inductors which I didn't understand why then I researched it. which is required because to match the frequency.
Also learned that Antennas sometimes have different modes like active and passive.

<img width="730" height="559" alt="image" src="https://github.com/user-attachments/assets/3151ea74-b15f-4bc5-8483-23e6a1335296" />

Also got the board wrong yesterday so had to find a new one.

<img width="761" height="524" alt="image" src="https://github.com/user-attachments/assets/e6014a4c-4b59-4aba-81c3-32a00eb0ab65" />

Schematic kinda messy gonna organize it tommorrow.

**_Day 3_** - Set up Kicad and easy EDA on my computer and finished schematics- **2 hours**

It took me a long time to setup kicad and all of the imports and file path right but when I finally got it working I was able to finish connecting the bluetooth harmonic filter and everything on that track.

<img width="1406" height="962" alt="image" src="https://github.com/user-attachments/assets/1a2c779c-d10a-4650-a5a2-8b0862e4cadb" />

It is still very messy I am going to clean it up soon when i get motivation.

**_Day 4_** - Fixed Footprints, Started PCB and wiring- **6 hours**

I had to add my old footprints which was on my computer and moved it on over to my laptop So I had to refind the footprint for some of the older parts that I placed.

<img width="1026" height="626" alt="image" src="https://github.com/user-attachments/assets/d78ba806-f359-4356-97b8-5b6cfc736fa1" />


After that, I was organizing the location of the hardware until I found it really hard to wire the NRF52840-QIAA-R because of it's extremely small pads.

<img width="854" height="844" alt="image" src="https://github.com/user-attachments/assets/6998cd85-2e25-4084-9f43-c4d97e0a524f" />

It wasn't fitting the JLPCB standard and I decided to stop for the day and ask for help on slack and try again tomorrow.
I learned about some new stuff like impedance and stub routing/trace and new constraints that JLPCB have.

**_Day 5_** - Finished PCB- **5 hours**
I explored more options for JLPCB production and decided to use the smallest possible Vias that is allowed by JLPCB to wire the NRF. After that I just finished wiring everything based on my schematic while i did get a little confused at some point but it was pretty smooth sailing.

I learned a lot about the placements of antennas and everything and how they needed to be seperated and different copper

**_Day 6_** - Finished PCB- **2 hours**
Changed the PCB and researched a thinner and stronger capacitor to fit the thin look i'm looking for. updated schematic and BOM for review

<img width="1075" height="661" alt="image" src="https://github.com/user-attachments/assets/1e908871-1e50-4397-97df-9090d65e78f3" />


