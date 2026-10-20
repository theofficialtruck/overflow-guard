---
title: "OverflowGuard"
github: "https://github.com/theofficialtruck/overflow-guard"
description: "A boil-over alarm which is installed on a pot handle where a liquid level laser distance sensor on a custom PCB registers how high the pot (milk, soup, pasta, water, chai) is boiling and sounds an alarm when the liquid approaches the top"
created_at: "2026-10-19"
total_time: "TBD"
---

## October 19, 2026: Analyzing the project and restrictions, setting up and planning project, researching

Today I was taking the first measurements of the target default pot, the pot handle, the depth of this pot, and other measurements that I can use later for reference when designing the product and its case. Because the pot's handle is higher than the near side pot rim, I am able to mount the device on the handle of the pot. There is also a convenient hole in the pot's handle which I may possibly use to my advantage. The pot also has a shiny reflective material, which might show bad readings for the laser.

I also do not know how to solder, which is required for this project as it will mostly be through-hole soldering. So, I am going to learn how to solder! I have watched many YouTube videos (not included in the time below) to help me learn more about soldering. My learning is explained with the picture below. The solder tin is the actual substance that connects the two components and electrically conducts them. The solder tip must be touched to the two components that are being soldered together, then add in the solder tin for the solder to properly melt on the components. I also read this [article](https://www.ifixit.com/News/6864/how-to-solder) from iFixit (counted in below time spent) to learn more about soldering.

![image](<assets/Screenshot 2026-10-19 214435.png>)

For the actual project, I plan for this to be mainly for an audience who does not like to constantly sit at the stove waiting for their dish to boil. Instead, with this product, they can go sit down and do something fun while waiting for their dish to boil, all without having to worry about the dish overflowing and spilling all over the stove. I plan for this project to have a Tier 3 grant cap and mostly through-hole solder joints because I am still a beginner. I do not plan to use an expensive Raspberry Pi and also plan to use eye-safe lasers only to ensure the customer's safety.

While brainstorming about how I thought this project would work out, I first thought that I would clip the whole device onto the rim and have some little liquid sensor pins drip into the pot. I realized this would be very inconvenient for the customer to have to always wash the pins each time they make a new dish, as the pins are directly into the food. Moreover, the extreme heat from the stove, pot, and steam coming off of it, is too dangerous for electronics so I decided I needed to move it somewhere else. I thought about a large arm over the pot, dripping pins into the pot but I realized this is also retains the same inconvenient design with the pins and it is also very bulky. Then I came to the idea of a wireless design with a camera pointing at the pot. This would remove the inconvenience of the pins and introduce an entirely new aspect of viewing the pot. However, this design would require an AI model to process the video and detect if it is about to overflow or not. This design requires too much compute power and also raises a privacy concern with the camera. Then finally I came to the main idea of a laser on the handle. This would remove the inconvenience of the pins, remove the privacy concerns and excessive compute power of a camera detection device, and it would result in a cleaner design overall.

Although this project can greatly help a customer with cooked, I cannot advertise it as a safety device, but instead as a tool. This is because the detection of the overflow is not necessarily guaranteed due to the different designs of pots and also sometimes a glitch can occur. However, this is a very useful tool and would save customers a lot of waiting around and doing nothing!

**Total time spent: 1h**