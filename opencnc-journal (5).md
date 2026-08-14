# OPENCNC — Journal Export

- Exported at: 2026-08-14T21:33:11Z
- Project ID: 1046
- Entries: 9

## Entry 1
- ID: 7098
- Author: potato
- Created At: 2026-05-14T15:46:11Z

### Content

Brainstorming and research - Consolidated machine design ideas and looked up typical cutting forces, expected constraints.

Also started drawing up CAD - Basic concepts with both potential final parts and also placeholder parts.
Fusion decided to corrupt the CAD file i was working on and as of right now it's impossible to fix - keeps on crashing. I'm going to restart my pc and see if that helps.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTUxNjQsInB1ciI6ImJsb2JfaWQifX0=--18d57920cd71f8af6af7ec1e70f21c572a167d86/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/79124575-5793-4e47-b9d8-2962ff60d2cb/video.mp4

## Entry 2
- ID: 7443
- Author: potato
- Created At: 2026-05-16T16:11:18Z

### Content

Worked on the CAD for the y gantry and made the base structure.
A few placeholder parts made - to be determined by final toolhead weight and space constraints, as well as FEA results regarding rigidity - I'm going to have to draw up the automation stack soon
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTYyNjQsInB1ciI6ImJsb2JfaWQifX0=--fc62676b0fb4097fccd5f9197448328aab126554/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/71837a9d-d42a-445c-b17b-93f718ac400e/video.mp4
- https://lookout.hackclub.com/api/media/18cfe746-ee67-4b2b-96be-01d0cffd4945/video.mp4

## Entry 3
- ID: 7622
- Author: potato
- Created At: 2026-05-17T15:23:27Z

### Content

Cleaned up stuff in CAD and did FEA (had to learn a little)
The current FEA is not representative as i still need to get proper numbers on the milling forces and actually add in the milling head to be able to do an accurate simulation, but it was a good opportunity to learn and take a look at what might need improving

FEA of the uncompleted machine frame with forces of 1KN on x,y,z at the head mounting area showing a maximum displacement of 0.1mm
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTY2MzAsInB1ciI6ImJsb2JfaWQifX0=--dcb7664b52a5530bc4ae1912b403c7c622dfffb8/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/5d4ffa50-5c90-430f-8190-1df5945d06de/video.mp4
- https://lookout.hackclub.com/api/media/7ce84808-51e4-4c99-8fa9-81ec6e706ca5/video.mp4

## Entry 4
- ID: 8223
- Author: potato
- Created At: 2026-05-20T21:10:31Z

### Content

Added the spindle to the frame, now re running the FEA with more accurate force points. Also fixed some more little CAD issues


![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTgwMDcsInB1ciI6ImJsb2JfaWQifX0=--c14fc9c956317cee85aa631514e6c2e933cf192c/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/9fe61441-2394-4a2c-82c2-21f2813beab4/video.mp4

## Entry 5
- ID: 8376
- Author: potato
- Created At: 2026-05-21T21:01:49Z

### Content

I've been working more on the FEA - it keeps on dying at the last stage due to bad geometry, I've had to reduce some parts to simple blocks while trying to find the issue. FEA running again and hopefully actually useable now.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTgzMTcsInB1ciI6ImJsb2JfaWQifX0=--0b8f9a949f549a731e21971768569ccb400dc6b6/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/7077767a-d67a-4390-a850-72d7831648b1/video.mp4
- https://lookout.hackclub.com/api/media/e305fe6b-3e59-437d-8629-745847f56645/video.mp4

## Entry 6
- ID: 17014
- Author: potato
- Created At: 2026-08-02T13:57:39Z

### Content

My exams are done and i'm finally free so I've decided to lock in and get this whole thing designed before the extended deadline.
I've worked heavily on the cad and started moving from something which was a conceptual movement frame to something which will actually be a useable, working machine.
- I determined what motors i needed to use via research and some maths and my now fixed specifications (1KN of absolute maximum milling force - this is now my value for my FEA)
- I chose the axis limit switches after some research
- I started to look at where i could source the 10mm plate i need to build all the major parts (eBay and Alibaba both have competitive prices)
- I made myself a to-do list and a GitHub for the project
- I finished a bunch of missing things in the cad (motor mounts, switch mounts, etc)
- I started to design the tool changer and iterated it a little : much more work needed here but I've got a good idea.
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDI2OTAsInB1ciI6ImJsb2JfaWQifX0=--7448f5bea5cde96621abbdb5f3392ab2ada1d609/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDI2OTEsInB1ciI6ImJsb2JfaWQifX0=--ca0058c866ccfd8c9a399219d37c0e4f4b1eecdd/image.png)

I've probably got 10-20 hours more of CAD to complete the core of the machine (not including tool changer) and then i'll have to move towards completing wiring diagrams and figuring out final sources for parts, exactly what controller i'll be using (or if i make one, design it)


### Recording Links

- https://lookout.hackclub.com/api/media/9042908a-a362-4a95-9e73-b0b41dba6200/video.mp4
- https://lookout.hackclub.com/api/media/ef6ca4cf-73bf-4c3b-8bba-a12961c5d291/video.mp4

## Entry 7
- ID: 17030
- Author: potato
- Created At: 2026-08-03T13:23:31Z

### Content

Day 2. I continue to be locked in.
Started adding all of the necessary things surrounding the core system (end stops, the machine door, electronics box, machine body, etc)
Also designed the chip collection chute - temporary model as i'll have to review it soonish to make it actually printable.
Re ran the FEA displacement analysis for my near final motion system frame and found acceptable results in both 1KN and 500N modes (check the github)
Continued to plan out and design the tool changer (tricky)
Contacted several sellers through Alibaba to get quotes on the metal plates and motors I need - I seem to have found appropriate deals for both of these.
Started to think out the actual control system which will be an old laptop running linuxCNC + a PLC and a self designed machine controller for stuff like safety interlocks, doors, tool changer, etc.

Up next is properly figuring out all of the electronics I need as well as looking into a potential final design for the tool changer and actually making the designs for the part clamps.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDI3MzksInB1ciI6ImJsb2JfaWQifX0=--c6aa5f8bea20ba2ee40b73060235ce52f3a4e1fc/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/d23b8386-a52d-4ccc-b189-a4f6178b6941/video.mp4

## Entry 8
- ID: 17041
- Author: potato
- Created At: 2026-08-04T12:46:12Z

### Content

Started working on making sure everything has all screws and is ready for manufacturing : the motion system is mostly ready to go, just need to add Z homing switches.
I finalized the door design - decided to go with a simple hinge.
I finally came up with a very solid ATC design - now need to make a complete manufacturable design
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDI3ODgsInB1ciI6ImJsb2JfaWQifX0=--ff96292a3b43f76f5d4a1ee6be5e3483b3fbcafc/image.png)
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDI3ODksInB1ciI6ImJsb2JfaWQifX0=--4ff665551311ebf357aa06ab063fce4ca6aac71d/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/056c4f3c-6802-4fd1-8512-2ecff9fe21ee/video.mp4
- https://lookout.hackclub.com/api/media/3936b510-9473-4f72-9e4d-c4c741b3f566/video.mp4

## Entry 9
- ID: 17062
- Author: potato
- Created At: 2026-08-05T10:49:33Z

### Content

CAD progress - primarily work on the Tool changer. 
Progress on the part sourcing as well - currently talking to two Alibaba sellers regarding aluminium sourcing.
Today and tomorrow I gotta draw up all my engineering drawings as i'm going on vacation for a few days - i'll start writing the build guide then. 
Electronics are still pending but depends on the final design of a few things - still need to finish up the final body of the machine, electronics rack, and user interface.

Here's the carousel of the toolchanger as of the most recent design : 
![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NDI4MzQsInB1ciI6ImJsb2JfaWQifX0=--8b172f953d768e06b2ed5b713efd6410b28ab968/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/81a3c828-55ca-4822-b278-15a530a3ac21/video.mp4
- https://lookout.hackclub.com/api/media/360a892e-9d1d-4bd6-aa91-b8c44e2b5e25/video.mp4
