---
layout: post
section-type: post
title: Setting Up My Personal Website
category: tech
tags: [ 'tech' ]
---

Welp.  Setting up my personal website took longer than I expected.  Perhaps it's time to adjust my expectations for how long things ought to take.  Or, perhaps I'm making an incorrect assumption that *I* am the problem, when the problem might really be the pace of society.  In pretty much every venue these days, there is a tendency for people to expect far too much from other people, goods, and services.  I think part of this is due to the world growing more complex, and it being an increasingly competitive place.  More competition breeds greater raw quality, though not necessarily perceived quality (more choices don't always result in a superior choice in the end, since humans are generally poor at making decisions under uncertainty).  Lofty expectations aren't all bad though.  There is probably some value in underestimating the amount of time something ought to take, in the way one dangles a carrot in front of a horse to get it to pull the cart.  Humans are different from horses, though, and there's a chance that prolonged carrot dangling may not bode well for motivating society as a whole.  It's a balancing act, and we're all in this together.

Anyway, enough rambling about things I'm not remotely qualified enough to talk about.  This post was not supposed to be about expectations—free form writing just kind of lead me here.  That's part of the beauty of writing though, and it's why I have the desire to start writing more in general.  I'm going to do my best to write reasonably well on this website, but I'm not going to agonize over wording the same way that I would if I were writing an essay.

This blog post was intended to be about setting up a personal website, so let's roll up our sleeves and get cracking.  Don't have any sleeves?  Roll up your pant legs.  Not wearing any pants?  I like your style.  

The goal here is to point readers who are thinking about setting up a personal website in the right direction.  What do you want out of your personal website?  In my case, I wanted a versatile website that I could use for a few different purposes.  Specifically, I wanted a website that could serve (no pun intended) as a professional landing page, a personal blog, and to host music that I've composed over the years.  Wordpress runs something like 25% of the internet, so initially I was going to go with Wordpress to get something up and running quickly.  I had a Wordpress blog maybe 5 years ago but it was a little clunky, and I wanted to try out some new tech.  So I got in touch with a friend of mine who has done a lot of web development over the years, and he suggested I give Jekyll a shot.  

Jekyll is a static site generator that is blog-aware and creates mobile/tablet/web-friendly websites.  In my opinion, if you're going to try using Jekyll, you probably need a bit of a programming background or need to be sufficiently motivated otherwise you're going to get frustrated, which might undermine the fun of creating a website.  To start, I needed a GitHub account.  I already had one through some [prior programming work](https://github.com/jeffbruce/).  For those who don't know, GitHub is a website that allows you to have code repositories online, so you can collaborate with other people on a codebase, keep version histories of your code so you can revert to previous versions if you ever make a mistake, and access your code from anywhere you have an internet connection.  GitHub allows you to host one personal website for *free* on GitHub Pages at the address \<your_github_name\>.github.io, which was definitely a plus for me.  

Once you have GitHub, the next step is to find a Jekyll theme that you like.  Basically, all I did was search free Jekyll themes, and, through a brutal process of trial and error, I finally settled on a theme.  Honestly, I had to try about 5-10 themes before I settled on one that I liked.  The instructions were incomplete or incorrect for a few of the free Jekyll themes which was quite frustrating.  The process was quite cumbersome overall, and the workflow of trying out different themes is far easier with Wordpress.  Here is the process of trying out a theme on Jekyll in more detail:

1. Leaf through Jekyll themes [here](http://jekyllthemes.org/) to find a few candidates that you like
2. Fork the repository for that Jekyll theme (essentially make a copy for yourself)
3. Follow the instructions for that Jekyll theme, but mainly just modify the one file (_config.yml) to personalize it for yourself
4. It's possible to do this all through GitHub online, but I wanted to set up a way of developing and testing locally, which involves using git from the command line and setting up Jekyll on your local machine (can be a bit of an ordeal for a Windows machine, which is what I was using—again, here is where it is massively advantageous to have some sort of programming background)
5. Add a custom domain by ordering one from a site such as GoDaddy, link this domain to https://github.com/\<your_user_name\>/\<your_user_name\>.github.io, then add a CNAME file to your GitHub repository at https://github.com/\<your_user_name\>/\<your_user_name\>.github.io

I have left Joomla, Drupal, and buying themes such as those sold on [themeforest.net](http://themeforest.net/) out of the discussion on what platform you should build your website with.  My understanding is that Drupal is overkill for a basic personal website, Joomla is somewhere in the middle in terms of complexity, and I didn't want to spend much money so I did not entertain the idea of buying a theme from themeforest.  In summary, here are the advantages/disadvantages of Jekyll vs. Wordpress that I can see:

Advantages:

- web/mobile/tablet-friendly
- produces a very fast website so users enjoy browsing it
- very secure since Jekyll builds a static website with no database or server-side junk that can be exploited
- if you are a programmer, Jekyll is a good learning experience
- can build a website for free by hosting it on GitHub pages
- can host your content as basic markdown files (essentially text files) so that transitioning to another platform in the future is easier
- can add Ruby gems to extend the functionality of your site (similar to Wordpress plugins)

Disadvantages:

- much greater learning curve than Wordpress and will probably take much longer to launch your website
- Wordpress plugins are probably easier to use to add functionality to your website
- experimenting with different themes is much easier with Wordpress

Hope this helped someone out there!  Signing off for now.  Godspeed.