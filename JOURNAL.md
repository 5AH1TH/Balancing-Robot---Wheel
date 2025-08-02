# My Journal

Total time spent: 30-35 hours

# Summary --
This project is a two-wheeled robot that can balance itself to stay upright at all times, even when given a push. It is designed to move forware, backward and turn using two separate motors. This robot has a lower center of gravity, hence the height. Furthermore, the robot features a carefully balanced chassis with different platforms screwed on to the outer box, holding the motors, batteries, and the rpi-cm5. It runs on two brushed DC motors connected to the wheels via bevel gears. The robot's structure is optimized for passive stability: a wide wheelbase and a low center of gravity to help reduce tipping. This project is part of a bigger one. I'm conducting a study to determine the optimal robot: a wheel based robot with no hip and knee actuators, a leg based robot with hip and knee actuators (but with no wheels), and a hybrid, a combination of two, where the robot can switch between legs and wheels to traverse terrain easier and faster. My hypothesis is that a hybrid will work the best for traveling rough terrain.



# DAY 1 -- 7/22/25 --

Learned and researched about different kinds of self-balancing robots, and all the different parts needed. There are three types of balancing robots: 
The ones with wheels that don't have hip and leg joints,

<img width="361" height="385" alt="image" src="https://github.com/user-attachments/assets/f753c927-a561-46b8-9e05-aa2c3dfcc75a" />

the ones without wheels (and with hip and leg joints),

<img width="417" height="695" alt="image" src="https://github.com/user-attachments/assets/cf9a0691-b76c-4c4f-afc7-90de72db3e43" />

and the ones with wheels and hip and leg joints.

<img width="460" height="778" alt="image" src="https://github.com/user-attachments/assets/1e1414b7-0b80-43da-a7fb-6205c8f3be3e" />

The pros of option 1 is that its simple, easy and compact.
The cons of option 1 is that it isn't very good in rugged terrain, and there isn't much flexibility with it either.

The pros of option 2 is that its pretty reliable, and can traverse terrain easier.
The cons of option 2 is that its really complex and hard to code, as using complicated machine learning is the only way to get it to reliably work.

The pros of option 3 is that its very reliable as being able to switch betwween wheels and legs makes the robot more adaptive of the environment. For example, if there is rugged terrain, the robot switches to legs, but if there is smoother terrain, the robot switches to wheels to make it go faster and to save energy.
The cons of option 3 is that it is pretty hard to cad out.

Time taken: 5 hours

# DAY 2 -- 7/23/25 --

I also began drafting rough mechanical sketches of the layout of the robot. I focused on identifying how to place the essential components like motors, batteries so the center of gravity would remain low and centralized. I also looked into bevel gears to ensure that the motor will be able to spin the wheels at the optimal position (90 degrees). I also fixed some errors about placement and issues like motor torque alignment and wheel spin direction (in the diagram).


Time taken: 2 hours

# Day 3 -- 7/24/25 --

I started the CAD design in Onshape. I also started modeled the two-wheel configuration and built the basic structural frame that holds the motors and battery pack, which is essentially the outside box. 

<img width="654" height="661" alt="image" src="https://github.com/user-attachments/assets/c8ef8c34-a893-43e8-9ad3-c80f6e2d1d04" />

I also created motor mounts with correct shaft spacing to fit perfectly within the limitations of the box. Faced a challenge getting the shaft alignment correct for the bevel gear pairing because the gear distance calculator was extremely specific.
<img width="375" height="319" alt="image" src="https://github.com/user-attachments/assets/44c35cff-14f5-4072-94de-43c3fb712098" />


Time taken: 3-4 hours

# Day 4 -- 7/25/25 --

Refined CAD model. I modeled it so that everything would be perfectly symmetrical to ensure the best reliability. I also added the platform on top to hold all the electronics.

Platform on top: 
<img width="1127" height="567" alt="image" src="https://github.com/user-attachments/assets/53f4bfd6-14df-4961-8ba3-b72f3425ef58" />

As said before, I focused heavily on weight distribution, keeping the motors lower and the compute module higher. I also found every single part I would need for the cad. What I used in my cad were bevel gears, motors, shafts, and ball bearings. I also need screws to attach the separate parts to the box.


Time taken: 4-5 hours

# Day 5 -- 7/26/25 --

I worked on modeled the bevel gear assembly and figured out placement of the 4 mm round shaft for wheel drive. I worked on cadding the gears to be the optimal distance apart, which was provided by the gear distance calculator. I also made sure that the bevel gears had the proper 90° interface to match the motor and wheel axes. This took a long time because making everything symmetrical meant that whenever I made a big change to the design, I had to constantly check the placement of the gears and motors to make sure they were still in the right position. If they weren't, I would spend at least 25 minutes fixing it to find the problem, and fix it in a way that doesn't affect any other components. The bevel gear assembly also includes this cantilever structure to help stabilize the shaft as one point of contact would just make the shaft bend.

Front view: 

<img width="703" height="542" alt="image" src="https://github.com/user-attachments/assets/14848581-91a6-4902-98a9-e729ef61471a" />

Back view: 

<img width="530" height="445" alt="image" src="https://github.com/user-attachments/assets/712b7e86-36ad-4aed-af6e-1f3218e17b81" />

In context of the robot: 

<img width="629" height="480" alt="image" src="https://github.com/user-attachments/assets/cc954b4d-ac96-409a-b926-4e779a7c62dc" />


Time taken: 3 hours

# Day 6 -- 7/27/25 --

I refined the design of the box to fit the wheels and beveled gear meshing. I also added screw mounts and filleted sharp corners to improve aesthetics. I also focused on making sure the bevel gear assembly was properly assembled, using mates wherever I could. I also changed the inner parts of the robot to make the robot even more symmetrical than before. Thats because the symmetricalness of a self balancing robot is one of the most important parts.

Time taken: 3 hours

# Day 7 -- 7/28/25 --

I added screw holes for every single component that was going to be screwed on. I researched different types of screws and determined which would be the best for my project. I determined that threaded screws that are around 12 mm long and have a diameter of 3 mm would be the best for my project. This is what my screw holes look like:

<img width="649" height="670" alt="image" src="https://github.com/user-attachments/assets/387f6e73-098d-43d8-b573-44ef72f4b00c" />

<img width="1043" height="247" alt="image" src="https://github.com/user-attachments/assets/54e7addc-8f8e-4cef-9f71-1af030876476" />

These are just a few examples.

Time taken: 3-4 hours

# Day 8 -- 7/29/25 --

I worked on making the cad look nice and compact. I also organized everything by labeling all the part studios and assemblies for an easier experience with the cad file. I also changed the colors of the components to make it look neat. I did this so that I could take screenshots of the cad after I was fully done cadding.

Time taken: 1-2 hours

# Day 9 and 10 -- 7/30/25 and 7/31/25 --

I spent the last two days reviewing the design, making minor corrections, such as fixing some height and gear meshing issues, and preparing the model to 3D and share here. I also increased the amount of screw holes for extra sturdiness, and removed any unnecessary parts to reduce the time and cost of 3d printing it.

For example, I changed this to this:

Previously: 

<img width="386" height="430" alt="image" src="https://github.com/user-attachments/assets/7927a429-4be4-4b14-ad92-8e2e997b299b" />


After: 

<img width="389" height="427" alt="image" src="https://github.com/user-attachments/assets/d0af5e7e-38d5-48a8-b229-a2b5e662e17d" />


Made sure the center of gravity was not only low but directly between the two wheels for better passive balance. I also took the pictures at the end. I also worked on the wiring diagram which connects all the electrical parts together.

Wiring Diagram:

<img width="2605" height="1598" alt="image" src="https://github.com/user-attachments/assets/9d6309c3-b59a-43f0-817d-459169af7bc4" />


Time taken: 6-7 hours

