---
layout: post
title:      "Script for my CLI Project Video"
date:       2020-08-09 23:25:39 +0000
permalink:  script_for_my_cli_project_video
---

<Start on dnd api website>

Hello my fellow humans, my name is Maika, and this is the demo video for my CLI Portfolio Project!

 I have chosen this lovely Dungeons & Dragons API as my scope, and the reason for that is simple: I'm a huge nerd, I've been playing D&D for almost 20 years, and the game has helped me with a multitude of issues; from learning social skills, coping with my anxiety, and even acting as a sort of bridge between me and my family. So needless to say it has a very special place in my heart, odd as that may sound. Anyways I'm excited to show you what I have so let's jump into it!

So once I decided on a D&D API, I just googled it and this was the first option. It's very compact, simple, and easy to use. 

<Demonstrate with 'spells' query>

As you can see, there's a lot of info in this thing. I'm fairly certain the creator put the entire PHB in it. But obviously I didn't want to grab all of that and pull it into my CLI, so I chose a few select options.

<Switch to Atom>

I decided that I wanted to approach it from the perspective of a brand new player, someone who has never played the game, is making their first character but has no idea what options they have available. I kept it simple with three options: classes, which returns a list of class names; races, which returns a list of race names; and search by class or race name, which returns the name of said class or race as well as other attributes.

<show Classes file>

So the first option will only return the name attribute here, but the search will return these additional attributes as well. The find_by_name method just ensures the user input is not case-sensitive, so you don't get a false error for not capitalizing the word. And the pretty_print method just returns everything in a clean aesthetically pleasing way. (Clutter stresses me out in real life and it's the same with my code.) Also the saving_throws attribute is written this way because we need to go one level deeper to get the names, otherwise it would return the entire hash.

<Show Races file> (Same here with the Races class file)

Now here we have the APIService class, which handles all the uri requests to the API itself. So here's the fetch_class_by_name method, which is the first to run when the search option is selected. And if the user input matches any of the names it will return the appropriate info, but if it does not it will come down here and run the fetch_race_by_name method instead.

After that is the CLI class, which does the bulk of the work in the program. It starts with a welcome message, then prompts the user for input and presents a list of options. Each option has a corresponding number to input, which will then run the appropriate method. The menu continues to come up after each query until the user terminates the program.

<Run the program and demonstrate>

And there you have it! I hope you enjoyed this as much as I did making it, please leave any constructive criticisms or comments down below, and happy adventuring!
