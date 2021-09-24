
# Glowing Earrings    

![130743502-4d3e4393-e0c3-4c22-a5b3-375d550cd5b7](https://user-images.githubusercontent.com/72219191/133019025-9370bce6-2b1d-479c-8323-1afc08ca9c91.jpg)

## Project Overview

I came up with the project after thinking about cool jewelry I could make for my girlfriend. I had thought that earring was always a formfactor which I could do something cool with. I had wanted to make the earring as simple as possible to use, disassemble, service, and find replacement parts for. I think I was successful in all these aspects as well as creating cool and intriguing statement pieces. 

## First Design 

My first design was very crude and failed in almost every aspect, but it was a great stepping off point and allowed me to see that the project had potential. 

### Material Choice and Design 

I used acrylic for the first design since I did not want to have to deal with my 3D-Printer. I used a bandsaw and disk sander to create the basic shapes. I wanted to stick to straight lines since it was easy to fabricate and evoked a glowing mineral vibe. I used a router to carve out space for the battery. All of these fabrication techniques lacked precision and produced a very crude looking chassis. As well the design was clear, not translucent. This meant that the battery was part of the earring in a way that made the design look over complicated instead of intriguing. The channels that the led probes slid into were cut using a Dremel. This looked ugly when fully assembled and only added to the messing look. The dremmeled out channels were also very finicky and unable to provide enough clamping force to create a solid connection between the battery faces and the probes. 

everything except the overall design language of the initial design would be replaced with much more robust choices in the following iterations. 

### Electrical Components 

The electrical components of the earring needed to be as brain-dead simple as possible for me to feel comfortable giving the earrings as a gift. The meant that the less parts in the circuit the better. LEDs generally need 3 volts to shine brightly, so I found that a 3.3-volt coin battery would be an adequate choice. Although this does slightly overvolt the LED, I felt that the tradeoff in lifetime was worth the simplification in design. I ended up using a CR2016 battery since they have a decent life and are a good size and thickness for the project. 

To allow the LEDs to be replaceable (for both serviceability as a well as color choice) I decided to use the LED probes as their own retention mechanism. I designed the chassis to accept slightly bent in probes. These applied enough tension to keep consistent contact with the sides of the LED faces.

For the LEDS I went with an assortment of solid colored 5mm LEDs as well as a pack of RGB cycling LEDS. The only problem I had using this form factor of LED was that the "purple" LEDs were actually UV. These require  more than 3.3 volts to power to full brightness. This meant that batteries wear out faster and the LED glows dimmer than the other colors. **This sucks since my girlfriend's favorite color is purple. :(** 
### Securing Devices 

My acrylic designs used two different systems for securing the two halves of the earrings together. The first was two random computer screws self-tapped into the acrylic. These were very bulky, easily chipped the acrylic, and were not long enough to solidly hold together the halves. After running out of screws (a lack of matching screws and losing multiple) I decided to use another system. 

My next design used small rare-earth magnets. These were much cleaner but added even more weight to the design and increased the size of the chassis. They also had very poor binding force and caused the LED probes to not make solid contact with the battery faces. After this complete failure I decided that screws would be the way forward. 

![131619885-9d6a4d3d-b459-42d8-a84b-ebb3a429b0bb](https://user-images.githubusercontent.com/72219191/133016695-ca8907c2-7d0d-4335-8f47-27643d0a409b.jpg)

**^(This image shows my first acrylic designs on the left with the subsequent redesigns (detailed below)**

## 3D Printed Design 
  
After my acrylic designs showed potential but significant issues in almost every aspect, I decided to use my 3D printer. This meant that I had to print 20+ variations to figure out the correct tolerances, printing settings, and infill patterns. the 3D printer and its glass bed also allowed me to not need to worry about surface finish and have a smooth polished feel straight off the printer. 

### Design Changes

The 3D printer allowed me to do much more complex designs that had much better tolerances while using less material. I ended up trying to target 6 grams per earring. The 3D printed designs were all made in Solidworks and featured very thin features. These had to be kept to a minimum thickness of 0.4mm due to the 3D printer's nozzle. I was able to drastically slim down the design of the earrings, which was needed. 

The 3D designs allowed for M2 nuts and bolts to be inset into the chassis. I made many variations with pockets for the nuts but ended up using self-tapped holes instead. The nuts added unneeded weight as well and required much higher tolerances than the rest of the design. The self-tapped holes were very strong, and I don’t think that they will wear out.

The 3D printer allowed me also to create much more precise holes for the LED probes. This allowed for a much more secure fit of the LED and the ability to create LED diffusers that wrapped around the chassis. 

The final 3D printed designs were held together by the earring ring and hook. This combined with tight tolerances means that the earring can be completely opened for service without any parts falling off the assembly. This makes the design much more user friendly. 

The 3D printer also allowed me to use infill to help hide the battery and capture some light from the LED diffusers. I used 30% gyroid infill for both sides of the chassis.

![Capture1](https://user-images.githubusercontent.com/72219191/133000500-8461e324-5bf4-4049-aca6-04bbe6bb0fe2.PNG)
![Capture](https://user-images.githubusercontent.com/72219191/133000495-bba98bd0-55fc-4320-81e6-3f03e4172cb9.PNG)
![Capture2](https://user-images.githubusercontent.com/72219191/133000464-656ec75f-c3f1-4da4-9e45-4ab98a78e1ca.PNG)

**^(Views of the inside of both halves and the earrings. The third image shows the bottom of the battery casing, which has two holes on either side of the battery for the LED probes to be inserted.)**

## LED Diffuser Designs 

![130743539-ade6c9be-96bd-4a4f-a0a9-d0192c035174](https://user-images.githubusercontent.com/72219191/133017091-49b03cac-d39d-4ee1-9199-a2219fb06b9d.jpg)

**^(This image shows all of the different diffuser designs which were used to experiment with many different print settings. In the bottom right you can see the test jig use to find the correct tolerances for the LED hole in the diffusers.)**

I started out with a simple triangle made of acrylic with a hole drilled into it for the LED. This triangle was then sanded on all faces to allow it to diffuse the LED.

After switching to 3D printed designs, I created 3 designs: a "foxhead", teardrop, and circular design. I did not do any surface finishing to the parts since I was worried that I would over sand and ruin the tolerances and create lopsided faces. The diffusers look somewhat unfinished when not lit up. When lit-up however they all have their own characteristics and look great.

The diffusers all friction fit onto the LEDs and have a satisfying snap or "push" depending on what type of LED is used. Finding the correct dimensions for the hole took quite a few iterations. 

I ended up either using 80% or 100% gyroid infill for the diffusers. 

## Conclusion
Overall, I felt like the project was an overwhelming success. Although starting I felt that the project may hit a dead end, the transition to 3D printing really allowed me to perfect my design and create a well thought out piece of jewelry. 


## Photo Gallery


![130743514-f54b9904-02d2-4719-9709-0f4fdf797280](https://user-images.githubusercontent.com/72219191/131620201-bb4ef7cc-a2a7-4741-91a1-d8d4bc569340.jpg)
![130743512-1178fd71-5b35-4df1-ae26-d2a1c7a6f4b8](https://user-images.githubusercontent.com/72219191/131619879-424537a5-5d60-4b0d-91ac-00bb52923c2d.jpg)
![130743520-3c0bfa15-2930-4da0-a79b-4f76a91ac0bd](https://user-images.githubusercontent.com/72219191/131619889-cc9aec52-554c-4503-8f80-65afdc7a4eff.jpg)


