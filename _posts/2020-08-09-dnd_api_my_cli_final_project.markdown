---
layout: post
title:      " DnD API: My CLI Final Project"
date:       2020-08-10 00:28:12 +0000
permalink:  dnd_api_my_cli_final_project
---


Coming into my cohort I knew there was a CLI final coming, and I spent roughly a third of the time leading up to it trying to think of the perfect project to both fulfill the criteria and showcase my skills. Originally I had settled on a scraper project that would scrape info from a video game developer's site. My Unknown Worlds scraper was going to accept input from the user and return info regarding the games made by the developer, such as Subnautica, a survival/terror game and their biggest title to date. (I cannot recommend this game enough, it is fantastic!) However after spending the first week of project time working on this, I came to realize that this project idea was not to be. 

I was having all manner of issues with it. The scraper was extremely slow to respond to any queries, no matter what corrections I made; after a respite and getting back to it, previously working code would just randomly break, even though I had changed nothing during that interim; and the overall look of the project was just very messy and not professional at all. So I opted to change my scope in favor of something that would be significantly less stressful and even fun: a Dungeons & Dragons API.

Why Dungeons & Dragons you ask? Simple, I'm a huge nerd and I've been playing D&D for almost 20 years. When I was 16 I joined a campaign with my mom, brother, stepdad and stepbrother, and it really helped me improve my relationships with them. It established video games as a means of communication and positive interaction, and through the years we've maintained this connection. To this day I have a weekly game night with my mom, stepdad and my partner. So after a minimal amount of Googling, I found the site https://www.dnd5eapi.co/.

Now with my project choice made, the next step was to determine what attributes I wanted to pull from the API and return in my CLI. There is A LOT of information in it; I'm fairly certain that its creator put the entire Players Handbook in there. But I decided that I wanted to approach it from the perspective of a brand new player, someone who has never played the game, is making their first character but has no idea what options they have. I kept it simple with three options:
             
						 1. Classes
						 2. Races
						 3. Search by class or race name
	
To elaborate, my CLI will present the previously mentioned options in a menu format, and will return the value associated with the option chosen by the user. Typing 1 or 2 will return a list of the classes and races respectively, and 3 will prompt the user for the name of a class or race. 
A correct class name will return the class 
            * name
            * hit die
            * proficiencies
            * saving throws
            
A correct race name will return the race
            * name
            * size
            * speed
            * languages

Now obviously there is a great deal more information in the API, but in the interest of time I opted to select what I consider the most important attributes.

I made the following video showcasing how I coded my CLI and a little demo of it working in all its nerdy glory.

Enjoy and happy trails adventurer!

https://drive.google.com/drive/u/0/folders/1_70vR_arEiLzGDvKbrtrcaX8o1DnZlqi


