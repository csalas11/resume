# README

This project was for my CS121: Software Development course at Harvey Mudd. 

We were asked to have fun and create something using Ruby on Rails

Intro:
This website used a theme from StartBootstrap called Freelancer. It is mainly used for Graphic Desiginers specializing in UX and UI, which is what I plan to do someday. There are some compatability issues I still need to fix, such as the scroll down menu not working. Otherwise, the page has been modified to my liking. I attempted to add a download_pdf generator that would allow for my resume to be downloaded. It crashed everything and had to restart my git. 

This was all done using component based methods, since I gathered other peoples components and gave credit, in order to create something for myself. Gained a lot of experience reading other peoples code and figuring out what everything does.

It took me about a week and a half to get this theme to work, lots of trial and error. Some tutorials didn't help since they were for earlier versions of Ruby/Rails. Was also at a conference and finally got it to work on a plane flying back to California. Will definitely go back to this website and make sure everything works. 



Summary:
A website resume for myself, Carlos Salas Ortega, it allows the user to use a single, simple page to get to know me and what I can bring to a company. Someone can contact me using the contact form, as well as, connect with me on LinkedIn. The color scheme is closer to that of Pomona College's where I attend school at the moment. 
The problem that my project aims to solve is a personal one, that some companies have told me that I should have a website for myself. My hope is that this is the start of solving that problem. 

MVP:
The most essential features for my MVP is the contact form, along with the courses I've taken so companies have a simple way of contacting me, as well as, getting to know some of the skills I've acquired through the courses I've taken, which is why I added the images to each course taken. 

MVP Functionality:
Got the basics of the simple things that companies should know about me, as well as, an image of myself. This is like my own personal LinkedIn. 


Images below show functionality

Major Components: 
The major component of this project is the theme I managed to get to work with my Ruby on Rails project. It contains CSS files and JS files that I needed to run through and edit so that the website would work as I like.

Ran into the issue of the theme not being compatible with my project for a really long time. It took lots of trial and error, and starting over. 
Also attempted to implement a Resume Download generator that would allow the user to actually download my resume when they clicked that button, however, it crashed everything since I needed to build new generators, some that conflicted with existing ones created for the theme itself. Really want to fix that. 


Known bugs are described throughout this README.md the main ones being the navbar at the top right not working when used on smaller screens. The download resume button also doesn't do anything. I tried fixing it, but I think it may be more of a compatability issue since I have all of the necessary files, it just me that some code isn't connecting well together. Will definitely look into it when I get back on this project in my own time. 

Struggled a lot with getting the theme to work, but ultimately the themes gems tutorial linked below helped a lot, I still had to move files around before it finally worked. 


Think of a component as a part of the system that contributes to the system's functionality. For example, user data input is a functionality that is accomplished using components such as data collection interface and database storage. Describe what technology you used for each.
Would have used File generation technology to create a PDF on rails that would be my resume, and have be downloadable for the user. Another solution I thought of was to linked the Button to an external website that would just prompt the download of my resume. This would require external storage so that I could put my resume there. Something like dropbox. The contact form requires some sort of server that would send me an email whenever someone sends a succesful message, meaning all forms are filled out. It uses JS to accomplish this. 


![MainPage](https://github.com/csalas11/resume/blob/master/screenshots/mainPage.png?raw=true)
This is the main page with an image of myself I edited using Photoshop to fit the page well. 


![NavBarHi](https://github.com/csalas11/resume/blob/master/screenshots/navBarHighlight.png?raw=true)
This is the main navigation bar being highlighted. 

![MenuHi](https://github.com/csalas11/resume/blob/master/screenshots/menuHighlight.png?raw=true)
This is the menu highlight on the top right when the mouse hovers over it. Mostly done using CSS .hover action. 


![SkillsUnmoved](https://github.com/csalas11/resume/blob/master/screenshots/SkillsUnmoved.png?raw=true)
This is the skills section, with the courses I've taken, along with images I added from the internet in order to show some sort of timeline/progress of the CS I've done throughout college. This one is when the screen is large, such as a desktop, had issues rearranging them to the center, might actually work out for better since I think I want to have the left side with courses, and right side with languages I've worked with. 

![skillsMoved](https://github.com/csalas11/resume/blob/master/screenshots/skillsMoved.png?raw=true)
This is how it looks when the screen is something like a mobile phone, it centers automatically, but for whatever reason won't do it when in full screen.

![skillsHighlight](https://github.com/csalas11/resume/blob/master/screenshots/skillsHighlight.png?raw=true)
When you hover over the image it turns a light shade of blue, using hover, and RGB transperancy values on CSS file. 

![moreSkills](https://github.com/csalas11/resume/blob/master/screenshots/moreSkills.png?raw=true)
More of the skills section


![about](https://github.com/csalas11/resume/blob/master/screenshots/about.png?raw=true)
The about me section of the website, which just gives a little bit of insight as to who I am and what I'm interested in when it comes to being a software engineer. 

![fullInfo](https://github.com/csalas11/resume/blob/master/screenshots/fullInfo.png?raw=true)
About me section on full screen desktop mode. Not compressed. 


![contact](https://github.com/csalas11/resume/blob/master/screenshots/contact.png?raw=true)
The contact form, that I believe will work, since I added a missing PHP File and editted it accordingly. Will know for sure when I have my website on the internet. May require setting up some sort of server as well, will cross that road when I get to it. 

![fullContact](https://github.com/csalas11/resume/blob/master/screenshots/fullContact.png?raw=true)
Contact form on full screen desktop mode. Not compressed.

![info](https://github.com/csalas11/resume/blob/master/screenshots/info.png?raw=true)
Info page showing different ways to contact me online through LinkedIn, or mail me something. 



Had lots of fun working on this, despite the times of desperation, glad I was finally able to get the theme working and then understanding the code to modify it was also really fun.


The following links were used while creating my resume website. Would like to thank all these open source projects and youtube tutorials for helping me to complete this
assignment. 



BootStrap GitHub link: https://github.com/twbs/bootstrap-sass 

Bootstrap Contact Form Tutorial: https://bootstrapious.com/p/how-to-build-a-working-bootstrap-contact-form

Issue page I visited: https://github.com/BlackrockDigital/startbootstrap/issues/61

StartBoostrap Link: https://startbootstrap.com/template-overviews/freelancer/

Freelancer Source Code: https://github.com/BlackrockDigital/startbootstrap-freelancer

Youtube Tutorial for Installing Startbootstrap Themes using Gems: https://www.youtube.com/watch?v=5vuF0n4Qlxk

Youtube tutorial for Installing Startboostrap Themes: https://www.youtube.com/watch?v=Nf_Si8_szmM

Tutorial on how to download files using Rails 4: http://teksourcery.com/download-links-sending-files-through-a-rails-4-app/



