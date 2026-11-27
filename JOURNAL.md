---
title: "AeroTrack"
github: "https://github.com/Ollie17112/AeroTrack"
description: "An overhead gantry system for makers who need an extra hand in their workspace. This Gantry will be able to move autonomously with capability for a multi-modular system such as a spot light, camera, or arm. I am building this project as I always find my desk cluttered when trying to complete an electronics project. The plan for the project is to create a belt driven gantry with an arm capable of positioning the modules autonomously. This unit will also be controllable through a web interface where different modes can be programmed."
created_at: "2026-11-25"
total_time: "7h"
---

# November 25, 2026: Linear rail selection
<!-- fabricate:entry 3917 -->

This session I researched viable linear rails for this project. I have decided on using a MGN12H rail due to its small form factor and low cost. 
![](https://fabricate.hackclub-assets.com/cbd6add562d6f6585029188697824c547cb9fda5f7ed6d7870fb94d851d40206/image-jpeg/61Hq5Yj27LL._AC_UF894%2C1000_QL80_.jpg)
I have also finished the assembly of the rail and car in SolidWorks by modifying the existing MGN12H components from the SolidWorks part library. So that I can use this assembly in the future I have used fully defined limit mates to allow the car to slide freely on the linear rail.

![](https://fabricate.hackclub-assets.com/13b45cdeadf51bc46bb5af5f6659e8295717e6e77b271e40f4f7c0b058a63ef5/image-png/image.png)
![](https://fabricate.hackclub-assets.com/44b736288ef0929410affb69554cb5cb3246e94a7d5384471e9d0bb618358add/image-png/image.png)

In my next journal I will build a bracket to attach to the car which allows the belt to connect to it. I will also need a wheel at one end of the track and a discrete way of housing the stepper motor.

**Total time spent: 1h 30m**

# November 26, 2026: Began Stepper motor assembly
<!-- fabricate:entry 3989 -->

This session I began modelling the motor housing for the x axis along the linear rail. This fits nicely onto the end cap of the rail. The stepper motor used will be a NEMA 17 standard as it has a good torque range and is a good size for this project.
![](https://fabricate.hackclub-assets.com/1be1d07cc2cee85278d265c9d240a500ebba3c603036274918aa10d69e023dba/image-png/image.png)
As shown in the image above a GT2 20 tooth timing pulley will be used to drive the belt. The stepper motor will be attached to the assembly with the included mounting screws. I will need to ensure the mound is strong enough especially if 3d printed. The image below shows a very provisional unfinished idea for the motor bracket.
![](https://fabricate.hackclub-assets.com/434459485776b3174455256d13570487e493d1b41ef2aeff6846bc18a223389b/image-png/image.png)
The side with the holes connects to the end cap and the blank side will have holes to attach the stepper motor.
Additionally i finished the design for the end caps with embedded nyloc nuts and the groove so it sits on the rail nicely whilst being secure. 
![](https://fabricate.hackclub-assets.com/e9fe92ce79391d9c9bb950b6786ddd1f2bd925e21081abdc0d1fa7fb35a28d3b/image-png/image.png)

![](https://fabricate.hackclub-assets.com/342df73850b5924a1ae043b1360c6c9c6d2fec9addaaabf86524028e7c388cfb/image-png/image.png)

In the next journal entry I will finish the stepper motor mount and work on the other side with the driven pulley. I may also need to consider a tensioning method for the belt.

**Total time spent: 3h**

# November 27, 2026: stepper assembly draft complete + Driven gear progress
<!-- fabricate:entry 4040 -->

In this session I completed the draft for the right hand side stepper motor mount. This part is still a draft as going forward I will need to test its strength to see if I will need to change the design.

![](https://fabricate.hackclub-assets.com/a0a90afc77cd375d4e28cb70507e70fe4d97bdd1872d034753d4d1cd37fa9d05/image-png/image.png)

![](https://fabricate.hackclub-assets.com/07dfd98283a558b6a200aaeae0f298779fe814537df06962a3ada2f9d3ac717e/image-png/image.png)

For the left hand side there will be an idler gear which the belt will move on. In the next journal I will finish this assembly making sure both sides line up and the belt is straight.

![](https://fabricate.hackclub-assets.com/7ce75b91bd680718cf5e3df46a679ff890cedd2064c65feeaa52bde35c2adb1d/image-png/image.png)
![](https://fabricate.hackclub-assets.com/f37159d5dafa70f0d56703b979027a1dade5bd28a4c80edea0c22fce73f8a9e9/image-png/image.png)




**Current progress in the master assembly**

![](https://fabricate.hackclub-assets.com/559f120b04a705ceec78e93a96974cae3931cc409a4e015b4ed120d4bc93b33e/image-png/image.png)

**Total time spent: 2h 30m**
