---
layout: post
title:      "Installing and Using Gems"
date:       2020-08-10 01:12:33 +0000
permalink:  installing_and_using_gems
---


One of the funnest things I learned about Ruby is the existence of gems, which are prepackaged applications or libraries that you can install and run in your own applications. Everything from changing text color to interfacing options to parsers to launching external programs within Ruby; if you think of it there's probably a gem already made for it.

Gems are as diverse as they are numerous, and they can really add that extra bit of functionality or polish to your project to really make it pop. Let's look at the basics for finding and installing these lovely bits of pretty!

**Finding the Right Gem**

The best (and most obvious) place to find ruby gems is at https://rubygems.org/, a massive repository and hosting service where coders can publish gems they create, or install gems from other users. The site also provides server support and tools to help install and manage your gems. In short, a great big pile of digital awesome.

So now that you're at the site, it's time to select a gem to install.Let's say you want to change the color of the text in your application. Go to the search box and type in "colorize", and click the first option. You will see things like versions, number of downloads and other information pertaining to the gem. Now we have everything we need to install the gem!

**Installing the Gem**

Under Total Downloads on the right, you will see two text boxes containing the Gemfile and Install commands. These are necessary for installing gems. Use the follwing steps to finish installing:

              1. In your environment file, type 'require "colorize"'. This will add the gem's lib directory in your load path.
              2. Next, go back to the RubyGems site and copy the Gemfile text to your clipboard.
              3. Paste into your Gemfile (or just type 'gem "colorize"')
              4. Lastly, copy the Install text to your clipboard, paste and run it in your terminal.
              5. Check your Gemfile.lock to make sure the gem has been added

And you've done it! You can use these steps to add any gem to your project and really bring it to life! 
