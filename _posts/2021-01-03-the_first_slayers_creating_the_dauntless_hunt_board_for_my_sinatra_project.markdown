---
layout: post
title:      "The First Slayers: Creating the Dauntless Hunt Board for my Sinatra Project"
date:       2021-01-03 14:23:31 +0000
permalink:  the_first_slayers_creating_the_dauntless_hunt_board_for_my_sinatra_project
---


When I first began this module, I admit I wasn't sure how I felt about it. I mean the idea of creating integrated databases didn't seem terribly interesting to me, at first. But once I got into it a little and learned of the requirements for the portfolio project, I knew exactly what I wanted to do: create a digital version of the Behemoth hunt board from the video game Dauntless.

This menu listed all the behemoths available and grouped them by their corresponding element. Players could then choose to pursue and slay a specific behemoth. But who created those entries? Who went out and brought back vital information to add to this ever growing database so slayers would know exactly how to find which behemoth and where? Logically I felt it had to be the NPCs who assist the player in the game world, and I dubbed them the First Slayers.

**The Bare Bones**

I decided to go with slayers (users) and behemoths as my two models. the slayers model consists of the following parameters: slayers_id or the foreign key, name, username, and password. The login credentials are username and password. The association is has_many behemoths, because each slayer can add any number of behemoth entries.

As the slayer model is the user, all slayers can create an account, log in, and log out. Additionally they can create new behemoth entries, edit existing entries, and delete them if need be. These functions are of course limited to each slayer's own entries. They can merely view other's.

Not needing nearly as much functionality, the behemoth model has only two attributes: name and element. And since there is only one entry per behemoth, it makes sense to assign the belongs_to association to this model.

**Stretch Goals**

Now that the MVP requirements have been met for this project, I now turn my attention to my stretch goals, which mostly center around aesthetics. I would like to improve the app's overall layout to give the slayers a better looking user experience, place a picture of each behemoth on their corresponding entry page, and perhaps add a button that plays the behemoth's sound file. I have no idea how to do the last one, but I look forward to the challenge.

**Conclusion**

Now that I have completed this project, I was surprised to learn that I had a much easier time with the curriculum than I thought I would. And although I did get overwhelmed initially by the scope, I was able to fulfill the requirements. This accomplishment was due in no small part to the incredibly detailed and informative video series made by Howard. So a big thank you to him!

This video game is quite near and dear to me as I play it with my mother and partner every week, and I am excited that I was able to create a fun little app from such a simple concept. I had a lot more fun with this project that I thought I would, and I plan on improving on my application until it is something I would be proud to show a potential employer. Perhaps I will one day put the app online and allow other fans of the game to enjoy it as well.

Until then,
Happy hunting Slayer!
