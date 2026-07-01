
# 10/12/2025 - Began main design in OpenRocket!  

_Time spent: 4.0h_  

October 9, 2025

Openrocket is a rocketry simulation software useful for getting overall layout, fin size/geometry, motor selection, etc. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkwODAsInB1ciI6ImJsb2JfaWQifX0=--612542fd674f02ec70692f7ced1323dce17e5f30/image.png)
Common practice is to start with the top of the rocket and work backwards, so that's what I did. This took about 4 hours as I had to research and select options for nosecone geometry, couplers, and where I want the rocket sections to seperate for parachute deployment. 
  

# 12/5/2025 8:33 AM - Improved Openrocket Sim  

_Time spent: 5.0h_  

I spent about 5 hours selecting my motor, fin geometry, and finalizing length of the rocket. I also adjusted parachute selection to account for the new weight total. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkwODEsInB1ciI6ImJsb2JfaWQifX0=--9b9b49e53fb9896e607eaae3d254ee41458b56cb/image.png)
I actually also spent some time investigating what it would be like if I made a much skinnier but taller rocket. While it would have been interesting, it's not super practical for a certification flight. 
I didn't get many photos of the long rocket, unfortunately. I repurposed the sim for a potential future project almost immediately and didn't share with anyone. 
I chose the aerotech I500 engine and a dual deploy parachute setup. Both of these are largely intended for high performance rockets - but because I wanted to get the experience of building a big rocket, I also chose to practice the more advanced techniques required for those processes.   

# 12/5/2025 8:37 AM - Began Cad Design  

_Time spent: 6.0h_  

I decided to start the CAD design in fusion 360 as I felt pretty comfortable with where the openrocket sim was at. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkwODQsInB1ciI6ImJsb2JfaWQifX0=--8cc3e20a3ec33479ab13fdeddb51412cbf960e7d/image.png)
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkwODUsInB1ciI6ImJsb2JfaWQifX0=--f8e46836cabc6669a2ec109fcecf85d88c3a2fff/image.png)
I know I said that common protocol is to start from the top and work down. However, the fin can was by far the most complex part of this design, so I chose to start with that. 
Fin cans typically just slide over the air frame (assuming you use a fin can). I didn't really like the way it made a bump due to the changing diameter. So, I thought it could be cool if the airframe tube slotted over the fin can. I think it looks really nice! 
  

# 12/5/2025 8:41 AM - Continued CAD Work   

_Time spent: 4.5h_  

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkwODYsInB1ciI6ImJsb2JfaWQifX0=--bb746bf6e32a6c7985a33b769ef0af6bef2243c9/image.png)

I decided to rough out the rest of the rocket. It's really just empty tubes and basic shapes, but it still took a little while to match my sim 1:1. I even took the time to model the two airframe layers, with the cardboard base and fiberglass sleeving. 
  

# 12/5/2025 8:48 AM - Began Work on Main Coupler/AV Bay  

_Time spent: 6.0h_  

So, in the middle of the rocket there is a black band, called a switch band. Because your power switch access goes in it! Thus, this notates where the AV bay is, and in my case, the main coupler. In the section of the rocket above the av bay is the main parachute and in the section below the av bay is the drogue parachute. The drogue deploys at apogee to allow for slowed descent, but still fast enough to not drift far, and then the main parachute deploys at a lower altitude. These parachutes are deployed via black powder charges. There are a few methods of charge containment, but I chose to do what is called "charge cannons". Long metal tubes with black powder in them, allowing for the black powder to pressurize and fullly ignite inside the cannon regardless of altitude. It also is a much more elegant solution that the standard for L1 rockets - a rubber glove tip filled with gun powder. I'm not kidding. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkwODcsInB1ciI6ImJsb2JfaWQifX0=--66a090c2d119fbc45f8ffb031787772bf9dfcc77/image.png)
There are also U bolts for parachute and shock cord attachment. 
  

# 12/5/2025 9:08 AM - The Actual AV Part of the AV Bay   

_Time spent: 5.5h_  

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMDAsInB1ciI6ImJsb2JfaWQifX0=--f7e062c6d4b12a4eb7f127d92bfe0b681c43665a/image.png)
I chose to run a featherweight blue jay and rrc2+ altimeter for my parachute deployment electronics, as well as a custom gps tracking setup using a particle boron and adafruit featherwing gps thingy that I had sitting on a shelf.
The mount I designed is pretty simple and non structural besides holding the electronics. Instead, all force goes through the 3 threaded steel rods, which is significantly overrated (but that is ideal). There's no dedicated battery mounting, but rather just a bunch of slats for zip tying them on, as that allows for better flexibility (lipo batteries are so fragile D:).
Currently, the plan for the charge cannons is to 3d print a threaded cap, as the body of the cannons are coupling nuts (long internally threaded cylinders). I just have to make them very thin so that they get effectively vaporized by the charge rather than shot off like a bullet, straight into my parachutes.  

# 12/5/2025 9:14 AM - Recovery Attachment Points  

_Time spent: 6.0h_  

I spent a while researching and planning how I would attach the sections of the rocket to the parachutes and shock cords. There are many methods, including epoxying the cord to the airframe. I did not like that option. So, for the lower section, I put two eye bolts in the fin can, allowing for a Y-harness to be attached, distributing the force across the two eye bolts so I don't have to deal with fitting larger ones. 
For the upper section, since my nosecone is 3D printed, I just included a bulky channell that the cord will be fed through and then tied off. The nose cone is permenantly affixed to the upper airframe section. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMTgsInB1ciI6ImJsb2JfaWQifX0=--b0d385b710489a62e6739a9373143b91ea59b646/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMTksInB1ciI6ImJsb2JfaWQifX0=--f11808867b3210732ca4532f3964f009cddf9e02/image.png)
  

# 12/5/2025 9:21 AM - Aesthetics !  

_Time spent: 5.0h_  

At this point, I decided to address the appearance of the rocket. While I already sort of had a color scheme, it wasn't finalized, nor had I planned any decals. I messed around with physical sketches, asked friends, even tried to use blender (never made progress on blender. I hate blender.)
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMjMsInB1ciI6ImJsb2JfaWQifX0=--49e9a74e3530555ff7fdb6a276b2611b664457be/image.png)
So I took that render, which took a while to get right. And then I went to do decals - I want one with the rocket name and one with my personal sponsor, Sunlu. 
However, this was when I found out my fins were too small. Which means... fin can redesign! 
  

# 12/5/2025 9:24 AM - Fin Can Redesign Part 1   

_Time spent: 4.5h_  

So, I had to go back to my openrocket sim. My fins had too low of a span (how far it stuck out from the rocket) and too short of a root cord (the base of the fin, where it attaches to the rocket. I also wanted to increase the fillets just in case something wonky happens, I want the fins to stay on.

Old Fins
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMjYsInB1ciI6ImJsb2JfaWQifX0=--7d2b23849e22abc337fbc501b0aedb43b41dff8e/image.png)

New Fins 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMjcsInB1ciI6ImJsb2JfaWQifX0=--a5dcbd6234fd9d2f129faf22649af42baea9a6af/image.png)

Pretty big difference! This mistake was pointed out to me by some of the members of the r/rocketry discord that I met, who have a lot more experience than I do. I am thankful for them. 
  

# 12/5/2025 9:28 AM - Fin Can Redesign Part 2  

_Time spent: 7.0h_  

Now that I had optimized the new fins in Openrocket, I had to model them in Fusion 360. 
I follow NACA airfoil guidelines for a very neutral airfoil. Max fin thickness is at 30% of the chord length and defined minimum/maximum radii for the leading and trailing edge so that it is printable. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMzEsInB1ciI6ImJsb2JfaWQifX0=--4b8758dcee16d1f8ef5f3db21c849beab89be1b2/image.png)
Specifically this one, NACA 0015. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMzIsInB1ciI6ImJsb2JfaWQifX0=--de3b6a0deba348119ca7843ece1f40ed83c1f2c9/image.png)
New bigger fins
AND
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMzMsInB1ciI6ImJsb2JfaWQifX0=--6346e26fc525dfc90838722d181e5f369e43f57b/image.png)
New internal support structure for the motor. Being able to define the voids myself saves more material than slicer auto infill generation. 


  

# 12/5/2025 9:31 AM - Back to Aesthetics!  

_Time spent: 5.1h_  

I decided to take a bunch of renders for promotional instagram material (gotta make my sponsor happy), sharing with my teachers, and for the github repository. This was also when I added my decals. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMzUsInB1ciI6ImJsb2JfaWQifX0=--0624183c561e8ca8f179a7185de4286d9a9f71a2/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMzYsInB1ciI6ImJsb2JfaWQifX0=--2d0bdca2327c5735ed75f0838cac2c1621fad6ee/image.png)

The odd clipping black lines are internal geometry such as couplers. Fusion doesn't like rendering thin walls. 
  

# 12/5/2025 9:32 AM - Write BOM, polish repository, submit for grant.   

_Time spent: 4.0h_  

I spent a couple hours writing out my BOM and cost optimizing it, as well as organizing the repository files and making everything look nice. I made the bom in Google Sheets and all renders are from Fusion. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMzcsInB1ciI6ImJsb2JfaWQifX0=--a4e0a028d1c30490794ea513a6bd3430a55b5994/image.png)

  

# 12/5/2025 9:35 AM - Grant denied  

_Time spent: 3.0h_  

So there was a big mess in rocketry stuff due to misunderstandings/miscommunications on safety and design expectations. It took a while to work out, but for a while I thought this would have to be tier 2 unless I had a custom flight controller (which I cannot do for a certification flight). It got worked out though! I just had to overhaul my journal, which has taken about 3 hours. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxMzgsInB1ciI6ImJsb2JfaWQifX0=--6e9ed991c668a7f3e1266f87cc7cf5d54147f8d8/image.png)
  

# 12/5/2025 9:38 AM - A little bit of hyper obsession  

_Time spent: 6.0h_  

Okay so. I discovered that there is a public engineering drawing of the solid rocket engine I am using - yet there was no 3D model. 
There is now a 3D model. Not only did I take the time to match it to the drawing identically, but I even took the time to material match every component to the point of the model being within roughly 2% of the real mass. 2%. Once I fire a motor I will cut it vertically down the middle and verify all of my dimensions. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxNDIsInB1ciI6ImJsb2JfaWQifX0=--d99a0adbb75963a3e0e9db6f484ac0d54b36d925/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxNDMsInB1ciI6ImJsb2JfaWQifX0=--6fe1972e43da2d2e987f8f57006658c62c1fff4c/image.png)

And of course, that makes my cross section look sick as hell. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxNDQsInB1ciI6ImJsb2JfaWQifX0=--2546c7283e8b59b60de71db455d1838106821629/image.png)


This likely took more than 6 hours but I can't accurately say how much it actually took, so I am gonna call it 6 hours. It did make me pull an all nighter though...   

# 12/5/2025 9:42 AM - Resubmit with New BOM, New Journal, and New Fancy Render  

_Time spent: 5.5h_  

I put a lot of effort into redoing this to match the higher quality standard that CAN expects of me. I also had to give a school presentation on this project, which was the main reason for the new render actually. It's a really cool render though! And was only like... kind of done stupidly? 

Like, great render!!
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxNDcsInB1ciI6ImJsb2JfaWQifX0=--0200ad755a5cef742874aed6c282307ecedde692/image.png)

But the way I pulled it off was a bit... quirky... 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTkxNTAsInB1ciI6ImJsb2JfaWQifX0=--c1698ebf4bee62569af299214b1af90390506d37/image.png)

That flame texture took 3 hours. Dead serious. It was so annoying and fusion was definitely not the right tool for this but man I just really hate blender. 


  

# 12/11/2025 - Ordered all the grant parts!   

_Time spent: 1.0h_  

I ordered everything that the grant is paying for, which is the rocket itself (save for paint), no flammable/explosives. Which is completely fair ! It took about an hour because some of the sites were being really annoying and confusing about the billing address and one site was freaking out with their shipping calculator but I called them and we figured it out. Yay ! ![IMG_2808](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjI4NDUsInB1ciI6ImJsb2JfaWQifX0=--3b7aeaf7e80c12098d22bc1363ee86fe6fa0f6c5/IMG_2808.jpeg)
  

# 12/20/2025 12:24 AM - Body Tube Work! Part 1  

_Time spent: 4.5h_  

Some of my orders arrived! I got cardboard body tubes and fiberglass sleeving to layup onto them. This is called "glassing" the part and I will be refering to it as such from now on. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NjQsInB1ciI6ImJsb2JfaWQifX0=--20f64f2bf3285d76127f36473d44a2bdf44715ea/image.png)

I started with the shorter section, the fore (upper) airframe. This is an 18" cardboard tube and one layer of medium weight fiberglass from Soller. I used a PVC pipe through the tube as a sort of tensioning rod. That way I could use zip ties to pull the fiberglass sleeve tight onto the cardboard. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NjUsInB1ciI6ImJsb2JfaWQifX0=--8384a192c314a20807fc6151e8acc4e3ae0df9ba/image.png)

This is the longer section, the aft (lower) airframe. This is two cardboard tubes, one 18 inches and one roughly 7.85 inch section. The tubes shipped in 18" sections, so one is cut down and one is not cut. These are joined by a printed coupler I epoxied in place. Most of the structural load should go through the fiberglass sleeve, which is not split along the length of the tube at all, so I felt comfortable using a printed piece. Did I get photos of that? No, I forgot. But here it is in CAD, and once the tube is finished I will take some photos of the coupler epoxied in place. 
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NjYsInB1ciI6ImJsb2JfaWQifX0=--82678013aedd1b68263042cf1078cfb7467764a1/image.png)

Prep took so long dude. So long. 
  

# 12/20/2025 12:36 AM - Body Tube Work! Part 2  

_Time spent: 5.0h_  

This time was applying the epoxy! Which was so, so messy, and I went through 6 pairs of gloves! 6!
I also realized I needed to do a fiberglass layup on the AV bay coupler and I decided to coat the fin can and nose cone in epoxy in an attempt to improve interlayer adhesion by bonding together the layer lines. It also means less sanding work to get it smooth.

So here are the two tubes AV bay coupler, fin can, and nose cone:

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NjcsInB1ciI6ImJsb2JfaWQifX0=--916df58871c70029f7e892a60fa7aebdbda2aa9b/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NjgsInB1ciI6ImJsb2JfaWQifX0=--0a58f61b5d35b9e2178cb37e57ed090efe3fda19/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NjksInB1ciI6ImJsb2JfaWQifX0=--5a561e56da1411738bb3fb775def0c2eea9e997d/image.png)

And a bit closer up of the tubes: 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NzAsInB1ciI6ImJsb2JfaWQifX0=--4f6d0672e694dfd257c66d31e48438d633b90def/image.png)

These will be curing over the weekend until I can come back to the school shop monday! 

Also once again, this took way longer than expected, and I had to work in a full face respirator the whole time, as I am sensitive to epoxy. 
  

# 12/20/2025 12:43 AM - Quick Recap of Printed Parts (forgot to do this earlier)   

_Time spent: 3.5h_  

Printing everything took a few weeks and a couple attempts, and total post processing time was right about 3.5 hours. Sanding, removing brims, troubleshooting, etc. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NzEsInB1ciI6ImJsb2JfaWQifX0=--5a620abe3b37c8eca6d879c430313066aba0e892/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NzIsInB1ciI6ImJsb2JfaWQifX0=--3fe8f7f97bc2f4a9ddec56a9f18506c67fe02783/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NzMsInB1ciI6ImJsb2JfaWQifX0=--54c5cf250a4348534b29e9f098a299ab7c557ab7/image.png)

All parts are PA6-GF from Sunlu, which is sooo lovely to work with. Prints like a dream, crazy strong, super pretty. Side note - Yes, I am sponsored. But, I have zero obligation to say positive things about this filament. I actually used to pay for this stuff myself, AND the college rocketry team I am a part of pays for it themselves too! No sponsorship on that one, and they've been doing it since before I joined. It's just... awesome. I highly recommend people try it. 

I actually printed two fin cans, one with the earlier smaller fins, which I ended up using to test fin breakoff strength. Not only did the fin can survive being thrown across the room multiple times (as hard as I could manage), but breaking off the fin took around 150 pounds of force! The new bigger fin can can actually support my whole body weight spread across two fins, which currently is about 255lbs!! I don't have photos of that because it was really sketchy. 

Old Can:

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjY3NzYsInB1ciI6ImJsb2JfaWQifX0=--27f35acedd3c04afea1caaa60b0c0b68ff2603f4/image.png)

  

# 1/6/2026 - Making toobs  

_Time spent: 3.5h_  

Sorry for the delay. My whole rocket got locked in my school workshop over Christmas break. But we’re back !!

Today I took my main frame tubes (and a coupler) off the mandrels, cut the ends using a miter saw, and started sanding. Because fiberglass is nasty I did this all with a full face respirator, heavy duty gloves, heavy duty dust extraction (240v cyclone dust vacuum with tubes routed all throughout the workshop), and soaked everything in water to manage dust. As you can imagine that made it take a bit. 

![IMG_3267](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU1ODgsInB1ciI6ImJsb2JfaWQifX0=--92a5534c17222348ab061fb3a552a5d968bb9197/IMG_3267.jpeg)


There’s me with all my gear. 

![IMG_3270](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU1OTMsInB1ciI6ImJsb2JfaWQifX0=--f06d89dda331fb90955673896ca6f1051cf7c7f8/IMG_3270.jpeg)
![IMG_3269](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU1OTIsInB1ciI6ImJsb2JfaWQifX0=--34b22b756dc4ab630efed5d61eb60b5991f522e1/IMG_3269.jpeg)![IMG_3271](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzU1OTQsInB1ciI6ImJsb2JfaWQifX0=--776a1c4c24c8b63cae5f9e99d5ff617442d3dd11/IMG_3271.jpeg)

  

# 1/7/2026 - Fin Slot Cutting Jig  

_Time spent: 2.0h_  

Needed to design a simple jig to cut the fin slots. Unfortunately there is no way for me to avoid using supports on this.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzYwNzYsInB1ciI6ImJsb2JfaWQifX0=--0e1e8ee71eac9a7b75da9589e09b43442a6b9902/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzYwNzcsInB1ciI6ImJsb2JfaWQifX0=--f8ba83b02d387423ebc64625c445f621fe3c6003/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzYwNzgsInB1ciI6ImJsb2JfaWQifX0=--1b5adadeaa9e752eaf54ac763648d36a1e2f7f56/image.png)

The bottom of the tube slots in and then I can cut it with an xacto. If that doesn't work then I will be marking it and cutting it with a dremel. 
The rectangular cutouts are the fin slots, while the elipses are just for material savings.   

# 1/16/2026 - New Eye Bolts and Fancy Sanding Block thingies  

_Time spent: 4.2h_  

Okay so, been working on sanding stuff and ended up buying some fancy foam sandpaper block things. Are they actually fancy? No, they're pretty cheap tbh. But they're way more comfortable to hold and they can absorb water for wet sanding so win-win. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODM3MTgsInB1ciI6ImJsb2JfaWQifX0=--ebc7b01b8a29d75d484e8119d62c78bc9a2ef568/image.png)

I also sanded the fin can a fair bit, but that was before the foam blocks. It now needs another coat of epoxy, but I want to do that after full fin can assembly, which requires epoxying in the upper puck that holds the eye bolts. I might print a little retaining thingy that gets epoxied in above the puck and is basically just a hollow tube with a lip on the bottom, that lip resting on the puck. That way when it gets yanked on by recovery forces there is more epoxy surface area holding it in place. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODM3MjAsInB1ciI6ImJsb2JfaWQifX0=--659b469d590a5c649ab8a4e1754762a052c15be1/image.png)

This is the fin can after sanding. I used the epoxy to fill in gaps/layer lines and then sanded smooth. This will increase interlayer adhesion and provide a more aerodynamic surface finish. I mostly sanded the fins as those are the only exposed parts. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODM3MjEsInB1ciI6ImJsb2JfaWQifX0=--2a0465b6f174ae6a2b2e1c61ead24c77881bc6db/image.png)

I ended up buying new eye bolts with my own money as the others were slightly too small. I am working on a refund for those other ones but... it isn't looking good. These will work though. 

Oh! I also got some radio trackers. 

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODM3MjIsInB1ciI6ImJsb2JfaWQifX0=--56a87fb934f9b5ff8b547ce63ce1290e76a33a8e/image.png)

Each one of these can beep out a signal at 440mhz, which I can use to find the rocket by having a radio and essentially walking in the direction that the beeps get louder. I paid for these myself, but they are designed by a wonderful rocketry enthusiast named ElvinC https://github.com/ElvinC/rocketbeacon.
They still need battery leads and wire whip antennas but thats the gist of it. 

Hours counted here are just sanding as that was most of the word - the rest is just updates! I have been doing some sanding on the tubing and coupler but those have very minimal progress so I didn't want to share quite yet. Coming soon though! 

  

# 2/5/2026 - An Update - Full Progress Check  

_Time spent: 3.2h_  

Alright. It’s been a while since an update. Basically, I moved to a new house. That took up all my free time and was not fun, to say the least. But I am back now and have a cooler space in the new house as my bedroom has counters.
Things remaining for the build:
Sand everything 
Make bulkheads
Install fin can in aft body tube 
Paint

Things are going quite well and I am really enjoying this build.

I also did 3 hours of sanding on the fin can so now the fins are ready for primer and paint. 
![IMG_3853](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTkwODksInB1ciI6ImJsb2JfaWQifX0=--dbefe21357f147d309aef9eea0e6fe614094a9e8/IMG_3853.jpeg)
![IMG_3856](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTkwOTAsInB1ciI6ImJsb2JfaWQifX0=--aa3a14f34871f2b91512df618d85b68509957100/IMG_3856.jpeg)

# 2/10/2026 - Fin Can and Nose Cone Installation. 

_Time spent: 4h_

Today was thge big day. I cut out the slots in my aft tube and prepped the fore tube for nose cone installation by sanding the interior. Then... I epoxied them in place! 

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/6d4ce795-d4e5-464f-aaac-2b2ff7d408d4" />

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/2ce069de-0f90-41f8-b21e-5a88b978acb5" />

The fin can tube slots turned out a bit rougher than intended because I cut them with an xacto knife. Learning for next time, I'll use a dremel or something. 

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/2f3c8c74-74c9-44ce-bb2d-afbd900e1d08" />

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/97100bc5-b8a6-4011-9eea-7e335a317c93" />

After installing the shock cord mounts, I was no ready to epoxy everything in place. These mounts take all of the recovery load so they are rather robust. 

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/37ac7a20-e445-48ed-b6e2-6725757e34f8" />

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/e2610787-5582-4df9-9190-91473bbb3601" />

And that's it! Turned out quite a bit rougher than expected but it's nothing I can't fix with some Bondo and filler putty. And sanding. So much sanding. 

# 2/12/2026 - Made bulkheads and AV Bay
_Time spent: 1.5h_

I had to make a whole new coupler but that's ok. This time I incorporated the switch band from the start. I also had to laser cut bulkheads and design a new sled for new electronics. Easy enough! Here are how those turned out:

<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/832a5785-4624-4cce-a37f-5ebfad5a116d" />

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/ffe3f246-ac1e-4526-993b-a03e690389c7" />

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/0e8e1484-e6ad-4298-ae0e-b32a01cf0fe9" />

I got a fancy new computer from a buddy that does both gps and flight control stuff and is super small. It will be test flying on my L1 for one of it's first flights, as a backup computer. 
The white parts are all printed out of sunlu ABS-GF. I love the stuff! 

# 2/20/2026 - Bondo day. 
_Time spent: 3h_

Today was bondo day. I spent a few hours applying it... in my bedroom. Not my brightest choice but I had a full face respirator so it worked out. 

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/eaf37576-4630-4c8a-8edd-854432f3cbf6" />

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/2d9ae3f5-7c28-4e5d-81e1-05796b03a985" />

It went on a little thick, but thankfully, it is easy to sand. I was just trying to fill all the little gaps and divots and stuff, which I did manage to do. I just had to go a little bit overboard first. I will not be doing this again - I have since learned you can thin bondo with acetone. Whoops. 

My room stank for weeks. 


# 2/23/2026 - Sanding sanding sanding!!
_Time spent: 4h_

I spent 4 hours sanding. Yeah. My hands are dead. It wass a mix of manual sanding and using an orbital sander. 

<img width="2880" height="2160" alt="image" src="https://github.com/user-attachments/assets/3622b545-734e-40eb-853a-0ab0254d06a6" />

Here's me in my respirator! Bondo dust is gross. This is when I was using the orbital sander. 

<img width="486" height="877" alt="image" src="https://github.com/user-attachments/assets/d7197fb0-b6e9-46c0-9159-826f62502627" />

It turned out real nice though! It looks like a rocket! Coupler fits, everything is the right size, it's quite smooth now. Yay!! I also used some epoxy putty during this process to get some spots the bondo missed as the epoxy putty is way thicker. 

<img width="1189" height="848" alt="image" src="https://github.com/user-attachments/assets/331bafed-befa-4b81-998d-8ba35049d780" />

I love epoxy putty. Man, is it nice to work with. You cut some off, mix it, and just apply it. That's it. Doesn't even stink much.

With that, all that's left is paint.

# 3/2/2026 - Paint!
_Time spent: 3h_

Had to wait a while for good weather so I could paint. 

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/31660d10-c023-44e5-8dd4-a503b3a1fc7a" />

I started with filler primer. This sutff was just once again to fill any little gaps. 

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/7d013a1c-ab23-4cc1-9933-0740a2db7be6" />

This stuff. Super nice. 

From there, it was on to color. 

<img width="676" height="909" alt="image" src="https://github.com/user-attachments/assets/ce2214ed-c1e9-462f-9ce0-40fd9661ca1e" />

This was my setup. I had this little stand I tied the sections to and then I painted each section the final color. I believe each section got about 3 coats? Man, it is looking good.


# 3/5/2026 - Decals and Clear Coat. We are done.

This is the last entry of build. Because, well, it's built. 

<img width="676" height="894" alt="image" src="https://github.com/user-attachments/assets/3df44031-c8cf-4edd-afc2-4558be209945" />

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/7e046fd8-b340-4c78-937a-e41585ac2fea" />

<img width="1180" height="887" alt="image" src="https://github.com/user-attachments/assets/67f5b617-e875-4e38-be20-37b2933829c0" />

I made the decals at school using the school printer and a Cricut vinyl cutter. I printed out the design and the cricut would scan and cut it. One for my sponsor, Sunlu, and one for the name, BECCA. They look soooo good.

One last coat of clearcoat over the decals to make sure they stay on and... We are done! 

<img width="2160" height="2880" alt="image" src="https://github.com/user-attachments/assets/179af31b-1306-4d17-b8d8-9aca7b6471e3" />

<img width="2160" height="3085" alt="image" src="https://github.com/user-attachments/assets/4b1904d7-3fad-4eea-80e4-4cb8aad4fb45" />

It looks so awesome. I am so so excited to finally have this bad boy built. It was a long process with a lot of learning on the way and I can't wait for my next build. This will launch as soon as the fire bans lift on our launch site. So... probably this fall :(
Ta ta for now. This was fun. 
