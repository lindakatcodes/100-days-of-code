# 100 Days Of Code - Log

Day 1 - Jan. 3, 2017 (1h39m)

*Today's Challenge* - Finished the last intermediate algorithm challenge on FCC, got halfway through the Git backend challenge.

*Thoughts* - This week I'm focusing on getting through my last few challenges, so i'm at a point where I'm ready to go through some projects. I especially wanted to get partway through the Git challenge because I honestly didn't see the fork button at the top and had no clue how to get my own copy of this repo! lol There's still a LOT of working with Git I don't understand but I've made a small step and can at least get it online. Today's algorithm challenge took a good bit of my time, had to rewrite it a few times before I finally got it working. Feels good to be through the intermediate ones! 

*Link to project/challenge* - Arguments optional (https://www.freecodecamp.com/challenges/arguments-optional)

-----------------------------------------------------------------------------------------------------------------------------
Day 2 - Jan. 4, 2017 (1h12m)

*Today's Challenge* - Finished Git challenge, spent some time investigating google sheets API

*Thoughts* - I want to create a simple inventory site for my current workplace. I've been attempting working on this project for months, and even got the main html set up like I wanted...but I've struggled big time to get the database/object storage side down. Hence me spending time working on the back end challenges to try and figure out how to make this project work. If I can use these 100 days to get that actually working, I'll be incredibly pleased. Today did not make any progress....more of my time was spent trying to set up my dev area for the site (clearing away past attempts). Right now I'm thinking I can somehow use the google sheets API (since I have my current data on my personal google drive) to then show, read, and write to those cells, and let my sheet be my database. Very unskilled in reading and utilizing API's that don't specifically show JS samples, though. 

-----------------------------------------------------------------------------------------------------------------------------

Day 3 - Jan. 5, 2017 (1h53m)

*Today's Challenge* - Worked on getting my google spreadsheet to connect and show data on my solo site - FINALLY GOT IT TO WORK!

*Thoughts* - I can hardly believe that I FINALLY got my data to show! I've spent literally MONTHS trying to work out how to connect a database to this, and have attempted to use the Google Sheets API before without success. Somehow tonight I finally found the right examples and references to work out some code that's actually working. Over the moon excited! Tomorrow I'll focus on setting my code up to a GitHub repo so I can share it as I go with everyone. Next task will then be working out how to make changes to the data so they'll store in the spreadsheet.....

----------------------------------------------------------------------------------------------------------------------------

Day 4 - Jan. 6, 2017 (1h40m)

*Today's Challenge* - Figure out how to get my local machine set up so I can edit / create on there and push my code to GitHub

*Thoughts* - Well, there's still a ton I don't understand about git and GitHub and how it all connects with VS Code, my current editor of choice. My working solution atm is to open just the specific folder I'm working on (which I'm not crazy about - I like having my programming folder open so I can see and switch between all my folders / projects but then the Git tab on VS Code wants to create a repo for the whole folder and it doesn't work right), do whatever work I need to do, commit the changes there, then go to my GitHub on my local and sync the changes with my online version. Seems like too many steps, buuuuut for now, it's working and I reasonably get it. lol Also added what I still have left to do for full functionality on the project's readme so I can guide my work and check things off as I go!

----------------------------------------------------------------------------------------------------------------------------

Day 5 - Jan. 7, 2017 (2h42m)

*Today's Challenge* - Created my own start/home page! 

*Thoughts* - I've wanted to do this for awhile and even started a few weeks ago, but other things kept coming up. Today I finally sat down, changed a few things up, and got together a site that I actually really like. I'm hoping it'll make things faster for me when I'm working on other challenges!

-----------------------------------------------------------------------------------------------------------------------------

Day 6 - Jan. 8, 2017 (~2h44m)

*Today's Challenge* - Completed the Express challenge on FCC & helped my partner show his live streaming video on a personal webpage

*Thoughts* I am still majorly confused about Express. Did not feel like I really understood much about what I was actually doing through the tutorial. I mean I got through it, but I have zero faith I could actually use it in a real application. Still a long ways to go with that. Also felt like it used a TON of outside 'middleware' / libraries. I mean I think that's part of how it is, but....just confusing. 

Getting the video on a webpage was not near as hard as it sounded when my partner asked me...we found an easy way to get the embed code from the media server he's using, and from there it was just a matter of getting it saved in the right folder and getting the hosting for the webpage set up. Did a little bit of styling to get the video horizontally centered and changed the background color. He's super pleased with it, so I'm really glad I could help him. :) 

-----------------------------------------------------------------------------------------------------------------------------

Day 7 - Jan. 10, 2017 (2h55m)

*Today's Challenge* - Fixed the search bar I broke the other day on home/new tab page; moved my stamp inventory files to cloud9; started work on Reverse Phone Numbers algorithm

*Thoughts* - Today is definitely a rough failure day. I spent the majority of my time attempting to be able to properly view my stamp inventory site on cloud9. If I use their run feature, it doesn't load my script or style pages....and I utterly failed at getting my gulp/browser-sync files to work properly. Still can't actually view the site properly on there. Which doesn't allow me to make progress during free/down time at work. No idea what I'm doing wrong or might be missing to get it to show properly. In an attempt to ease my frustration and feel like I made actual progress today, I started the algorithm challenge. I did at least make some progress there, but naturally there's a lot of edge cases to cover and I'm too tired now to keep working through it.

-----------------------------------------------------------------------------------------------------------------------------

Day 8 - Jan. 11, 2017 (1h28m)

*Today's Challenge* - Finished the phone number verifying algorithm & the symmetric distance algorithm.

*Thoughts* - Made much better progress on the phone number algorithm today. A day's worth of thinking gave me a better idea of what to test for, and I got it done with 4 regexp's. The Regexr.com site was a huge help for this! I still have plenty of time so tackled the symmetric difference algorithm too (the record collection one was already done, as it used to be in the json challenges). It took some time and testing in VS Code to use the debugger, but finally figured out why my reduce method wasn't returning anything (you have to return the value, duh) and got that solved too! Well on my way to finishing the algorithm's this month so all I have left for front and back end are full projects - mini goal #1. :)

---------------------------------------------------------------------------------------------------------------------------

Day 9 - Jan. 12, 2017 (2h16m)

*Today's Challenge* - Got my cloud9 stamp inventory program finally fixed so I can view everything correctly; started exact change algorithm.

*Thoughts* - Well it took me an hour tonight (not to mention a chunk of time earlier today and frustration a few days ago), but I finally got my cloud9 workspace set up and working correctly. I ended up having to completely scrap the workspace I had, make a brand new one, update the node version, and add my three files (html, css, js) to the root directory. Then I had to figure out why I still couldn't see my google sheets data (I had to add the cloud9 preview address to my google api authorization). But it finally works, so I can make progress during down times at work! Then started the exact change algorithm, got the easiest parts taken care of and now just have to work out how to count down the change and log it into the right format.

---------------------------------------------------------------------------------------------------------------------------

Day 10 - Jan. 13, 2017 (1h18m)

*Today's Challenge* - Completed Exact Change algorithm

*Thoughts* This one was stumping me for a bit. Got a hint from the forum's post on this algorithm to account for the individual amounts (a penny, a dime, etc) which helped a lot. Then it was just a matter of figuring out how to fix the odd rounding it kept doing, so it would account for everything like I thought it should. 

--------------------------------------------------------------------------------------------------------------------------

Day 11 - Jan. 14, 2017 (3h08m)

*Today's Challenge* - Complete the learnyoumongo exercises

*Thoughts* - I struggled for a good while on exercise 3....it took me a long time to realize that each new terminal I opened needed to have mongodb installed onto it for it to work. Still doesn't quite make sense to me...but it solved my error I was getting, so I rolled with it. Once that was solved, the rest went by reasonably easily. Definitely lots of new terminology, I wouldn't say I fully understood and could reapply it all right away....but it made enough sense that I feel like with some dedicated time I could get used to it and make it work for me if I wanted. 

-------------------------------------------------------------------------------------------------------------------------

Day 12 - Jan. 16, 2017 (2h46m)

*Today's Challenge* - Completed Inventory Update algorithm, started No Repeats Please algorithm

*Thoughts* - I was able to solve the Inventory Update algo in about half an hour, which was awesome. I'd seen a few times that the no repeats algo was causing people trouble....and I can see why! lol It took me a good while to implement a version of Heap's algorithm (the recommended option), lots of searching and trial and error until I could get one to work. So I'm getting all of the possible permutations for each string. I started working on a regexp to catch repeated letters and remove those from the possibilities, but it's not quite catching everything yet.

-------------------------------------------------------------------------------------------------------------------------

Day 13 - Jan. 17, 2017 (1h30m)

*Today's Challenge* - Worked on stamp inventory site

*Thoughts* - Well, I've got what I want down for the used stamp form. It adds a new line easily so it can tailor to however many it needs and not have to show all possible options each time. Needs some work for where to add the finished button and toggling the display, as well as the actual storing/updating of entered values. Still, it took some work to get the dynamically adding thing to work so I'm pleased overall! Some of that was started at work yesterday, but some more final touches were added tonight. Also got my cloud9 setup connect to my github repo for it and so it's able to push and update whatever work I do, so I can work online or on my local machine and use the same code. Blows my mind that that's possible - to type a line into the terminal somewhere and it updates my github pages! Crazy.

--------------------------------------------------------------------------------------------------------------------------

Day 14 - Jan. 18, 2017 (1h49m)

*Today's Challenge* - Finished No Repeats algorithm, started Friendly Dates algorithm

*Thoughts* - Got no repeats working relatively easily today, just took creating a variable to count the number of strings that passed instead of trying to change the whole array. Friendly dates is kicking my butt currently....got the month figured out easily, thought I had the date pretty easily (though I've got a bit to tweak there). When to add the years is what's messing with me right now. It works for some but not all, and I keep confusing myself. Might just be because it's late for me and my brain's tired. lol 

--------------------------------------------------------------------------------------------------------------------------

Day 15 - Jan. 19, 2017 (2h14m)

*Today's Challenge* - Added footer to stamp inventory & updated with git; finished Friendly Dates algorithm; daily css tutorial

*Thoughts* - Spent some time in the morning adding a footer (and therefore a bit more space on the bottom) and updating my changes with git to my github repo. Also finished up the friendly dates algorithm so that was done. Felt great to start the day with finishing some things that were on my mind. Then finished the day in the evening following the blog post/walkthrough for the daily css images deal, making the little koala and adding my own mouth onto him. lol 

---------------------------------------------------------------------------------------------------------------------------

Day 16 - Jan. 20, 2017 (2h4m)

*Today's Challenge* - Daily CSS Images D1: bear cub

*Thoughts* - I was going to do some algorithm work, and even spent about 45 minutes reading through articles and trying to wrap my mind around them...but I just wasn't getting anywhere. Had no idea where to go or quite what to do. So instead I changed course, cleared off my time tracker, and started over by creating the first daily css images challenge - a bear cub! I can tell I'm going to get extra picky on these, trying to tweak and tailor everything very minutely - but it was fun and he's not all that bad. :)

----------------------------------------------------------------------------------------------------------------------------

Day 17 - Jan. 21, 2017 (1h2m)

*Today's Challenge* - Two algorithms complete - Make a Person and Map the Debris

*Thoughts* - I couldn't wrap my mind around these last night, so today I took my time during commerical breaks of Disney movies and worked through them with the help of the FCC forum articles on these algorithms. Just looking at the hints it gives you on the wiki/forum pages makes a big difference for me sometimes in getting through these. Only one more algorithm left to complete until it's just projects for my certs! Though I'll likely be waiting a bit before starting those, as I know they've got a new setup in beta that might get pushed in soon - we'll see on that. 

----------------------------------------------------------------------------------------------------------------------------

Day 18 - Jan. 23, 2017 (1h12m)

*Today's Challenge* - Pairwise algorithm complete - meaning all algorithms are done! Also two CodeWars katas done.

*Thoughts* - Woooohoooo all my algorithm challenges are done! Nothing left to do on FCC but projects. :) Think I'm going to take a break from FCC for a bit, do the Javascript30 class I got next month, and see if the new beta map will be cleared for the live version in a month or so. If not, there's at least two projects I can do now that will copy over to the new version. Plus I'll have Daily CSS challenges to do and my stamp inventory to finish. Maybe some websites to make and portfolio to redo. :) I had only done ~45 minutes when I finished the algorithm, so I did the two CodeWars katas to fill in my hour and give me a litle more practice on things.

---------------------------------------------------------------------------------------------------------------------------

Day 19 - Jan. 24, 2017 (1h50m)

*Today's Challenge* - Work on forms for stamp inventory

*Thoughts* - Did some good work at work earlier today on getting my used form to look right, and then duplicating it (with some changed names) for the stock form. So the look is there (though when I tried to look at it locally tonight the size of one field does not look right and wouldn't adjust no matter what I did, no idea what that was about)....mostly. The remove button on mobile goes just slightly outside of the form box but I can't work out how to prevent that and still keep it on the right line, so...meh. Tonight, on the code clock, I tried to work on getting the data from the form and actually updating my stamp array with that data. No luck yet that I can tell.

--------------------------------------------------------------------------------------------------------------------------

Day 20 - Jan. 25, 2017 (1h23m)

*Today's Challenge* - Still trying to fix the form functionality

*Thoughts* - Super frustrated tonight. I found where my issue is - my form submit function is getting the values from my form, but for some reason it can't find the name value in my stamp array, even though when I print out the array I can clearly see it there. Somehow using indexOf isn't finding it. No idea what's wrong....both the stamp value and the form returned values are strings, there's no extra spaces anywhere that I can tell, the spelling and capitalization are the same....yet somehow, it doesn't see it. I'm at my wits end for tonight, I had to stop. I mean at least I know where the hangup is, I guess....but I have NO CLUE how to fix it. Ugh.

----------------------------------------------------------------------------------------------------------------------------

Day 21 - Jan. 26, 2017 (1hr33m)

*Today's Challenge* - MY FORM/SITE IS WORKING!!!!

*Thoughts* - I don't even have words. I'm so dang excited!!! I FINALLY got the functionality for my stamp inventory site working!!! Lots of time struggling with the Google Sheets API, some help from some freeCodeCampers, and plenty of frustration went into this. I worked some outside of my timed coding (while at work) on getting this problem solved. It still has some final style and wording to clean up, and I still have a little bit of work left to do as far as if I want to prevent the default submit and clear/reset the forms manually or if I want to let it submit and somehow redirect or clear the url so the query doesn't show. But oh my glob - IT'S UPDATING THE GOOGLE SPREADSHEET AND SHOWING ON MY PAGE AND I JUST CAN'T!! lol

----------------------------------------------------------------------------------------------------------------------------

Day 22 - Jan. 28, 2017 (5h11m)

*Today's Challenge* - Final tweaks on my stamp tracker site!! *Happy dance*

*Thoughts* - I didn't get to code yesterday, but I was itching too all night. So I made up for it today. lol Bit of a marathon, but I got the last few touches I wanted done worked out (toggle for my inks, some sizing / style issues on my forms, conditional formatting for my table if something's below a certain range) and cleaned up my code on my github repo so my personal stuff is removed and folks could view/copy it if they'd like. :) I am beyond stocked. This project has been on my mind for literally MONTHS and I've made a few attempts before and got so frustrated I had to walk away. My mind is blown that I finally worked out how to do it and got it all working and it's beautiful and amazing and just UGH I'm so happy with myself. lol :) The final test will be showing the folks at work on Monday and updating all my info the the correct quantities so I can start really using it! Oh, and I guess uploading it to my server so it's an actual site too. lol

The final repo: https://github.com/lindakatcodes/StampInventory

-----------------------------------------------------------------------------------------------------------------------------

Day 23 - Jan. 30, 2017 (1h00m)

*Today's Challenge* Watched the Getting Started and Drum Kit videos on JavaScript30, read a tech blog post

*Thoughts* I really wanted to make more progress tonight, but my new work schedule and an unplanned errand took most of my time. At least got a slight start on JS30, and am ready to really dig into the first project tomorrow. Gonna be learning a lot about ES6, which I haven't really used yet! Wish I could host my files on CodePen, but some of the files (audio files so far) I don't have a way to support on there. Ah well. Screenshots & gifs it'll be. Gonna work to make more time tomorrow!

---------------------------------------------------------------------------------------------------------------------------

Day 24 - Jan. 31, 2017 (2h40m)

*Today's Challenge* JS30 Drum Kit, Daily CSS elephant work

*Thoughts* Felt much better today. Got the JS30 drum kit working, which is pretty cool. It's much more walkthrough/tutorial like than I expected, but I'm gonna pick up a lot of ES6 stuff and event functionality and such so it's gonna be fun. To counteract the guided learning for 100Days, I started working on my elephant for day 2 of Daily CSS. He's actually coming along quite nicely, I got probably 70% of the way done. Just gotta add the eyes, maybe some back legs and a tail, and a few other little details and he'll be good to go. I've never considered myself to be good at drawing or creating art, so this is actually turning out to be really fun. I get to feel artsy by just writing out code and having it become some simple art on my screen. Pretty cool. :) 

---------------------------------------------------------------------------------------------------------------------------

Day 25 - Feb. 1, 2017 (1h20m)

*Today's Challenge* Finished my elephant, completed JS30 day 2 - clock

*Thoughts* - Pretty pleased with my final elephant! He gave me some practice with using transform, plus working on taking a drawing a piece at a time and helping it all fit together. There's still some things I know can be done better that I just don't know how yet, but for being my second solo css drawing - big improvement! The JS30 clock was interesting....kind of fun to see the hands ticking along. He mentioned at the end of the video that you could prevent the skipping look when the hands hit the top by toggling the transition time or counting the time or something....but honestly I just removed the transition entirely and everything still seems to be working and it doesn't do the skipping thing. Without numbers on the clock I might be wrong that it's not messing anything up lol buuuuut it doesn't seem to! I don't know, seemed odd but I'm too tired to worry too much about it. Definitely need to find something to point out specific ES6 traits soon though....there's things we write (like the little tick marks) that I know are specific to it but I don't really get what they're doing. I was hoping this course would be a bit more in depth with actually learning what things are and how/why they work, rather than simply following along and creating. It's definitely still good exposure, just...not quite what I expected & hoped for.

-------------------------------------------------------------------------------------------------------------------------

Day 26 - Feb. 2, 2017 (1h31m)

*Today's Challenge* Completed two CodeWars katas, gained a kyu level, completed JS30 update CSS variables with JS

*Thoughts* - I wanted to do some algorithm challenges or something today - I know, what is going on with me? ;) So I went to CodeWars and did two katas, one capitalizing the first letter of each word in a string, one taking two objects of fighters and having them battle then returning the winner. Felt pretty good! Then completed the day 3 challenge on JS30 of updating CSS variables with JS. Pretty cool - I had no idea you could actually use variables in CSS itself! I knew it was possible with SASS and likely others I'm not aware of, but not in straight CSS! So cool. I went back to one of my daily CSS pens and played with creating some variables to store colors on them and it works there too, so this is gonna make future images easier to color and style. :) 

-------------------------------------------------------------------------------------------------------------------------

Day 27 - Feb. 3, 2017 (1h14m)

*Today's Challenge* - Two days of JS30 

*Thoughts* - Went through array cardio day 1 which was helpful. I could always use more practice with map and reduce, which I still struggle with fully grasping. Also went through the next day, flex panels image gallery, because I had an idea for a project start and this sounded like it could help. And the a point, it did. It was definitely interesting and fun, though I'm not sure exactly how much it'll help with my project. Still, two good days. I started to look up some books or classes to help me 'get' ES6 but my internet went down, so that ended my day pretty quickly.

---------------------------------------------------------------------------------------------------------------------------

Day 28 - Feb. 4, 2017 (1h11m)

*Today's Challenge* - Started work on my project - a one page site for displaying some sports photos for a job application

*Thoughts* - There's an option with the mlb to take photos and videos and work with social media stuff for my local baseball team, and I've always wanted to be able to be closer to the field and have a chance to take tons of more shots than I usually can from the stands, so I've decided to apply. One of the requirements is to have a portfolio of previous sports photography. So that's what I'm working on now. Tonight I got the basic set up looking right....got a header bar for my name to go in, got the main section set up to show rows of the photos with proper space in between, and got the footer bar for contact info. Plus put the colors in. This took me longer than I expected, as projects often can lol. So next step is to actually upload my photos and then put all the links in and then work on adjusting things as I'm sure they'll change the current set up.

-------------------------------------------------------------------------------------------------------------------------

Day 29 - Feb. 6, 2017 (1h47m)

*Today's Challenge* - More work on photo portfolio page.

*Thoughts* - Got the images all uploaded onto imgur and then looooots of tweaking to get everything looking right on my page. A bit of work on font and sizing of the info on the page too. All that's left to do is letting the picture increase (& maybe darkening the background) when you click a picture, so you can see a larger size. Really need to finish this up tomorrow....it's already taking longer than I'd prefer for a job app that I don't consider myself likely to get. Still gonna try though. :) 

--------------------------------------------------------------------------------------------------------------------------

Day 30 - Feb. 7, 2017 (2h37m)

*Today's Challenge* - Got photo folio page as close to done as it's gonna get.

*Thoughts* - Well, it's not quite perfect, but it's good enough to move on from. I was able to work out the modal/single image view pretty quickly, then spent a good while problem solving why I was having to double click for it to work (hint: I had the click function going twice, duh lol). Then removing some unnecessary divs, adding a link for the imgur album on the off chance that sizing goes weird or images don't load, attempting to hide the body scrollbar while the modal is up (never could get that to work, just living with it), and trying to decide on how to adjust the sizing so the images look as best as possible on different screen sizes. It's not perfect, but it's as good as it's going to get and I have to just move on from it. I'll write the cover letter and submit everything tomorrow night, then it's adjustment time for my stamp site....got a few changes from using it a bit that I'd like to make. 

--------------------------------------------------------------------------------------------------------------------

Day 31 - Feb. 8, 2017 (58m)

*Today's Challenge* - Quick touch up change on sports folio, reading blog posts on css images

*Thoughts* - Short night tonight, especially since my internet kept going down. Did a final (for reals) touch up on my sports photo page, changing the images from original size to huge thumbnail so it'll load a touch quicker on mobile. Finally sent the actual application off, so that's really truly done now. Was going to start some changes on my stamp site, but got overwhelmed with trying to figure out how to do it so decided to skip it for tonight. Spent some time reading some blog posts on css images and subsequent links from that article.

--------------------------------------------------------------------------------------------------------------------------

Day 32 - Feb. 9, 2017 (1h1m)

*Today's Challenge* - Started work on Daily CSS beaver

*Thoughts* - Didn't honestly think I'd get to working on anything tonight - my schedule's been slipping and I've got to get it back onto a track that suits me better. But I started working on my next Daily CSS - beaver. Did some researching of what I might want him to look like, and got the background and box all set up, along with the basic shapes for the head, body, and tail. Had my positioning all wrong at first (trying to do it from memory of my previous ones) and couldn't quite figure out why everything was working odd....went back to one of the previous ones and found out pretty quick I'd gotten my positions all wrong for the elements. Got that changed up pretty easily though! And still managed a full hour....it's later than it should be but it's done! :)

------------------------------------------------------------------------------------------------------------------------

Day 33 - Feb. 13, 2017 (1h6m)

*Today's Challenge* - Halfway through course on using npm scripts as build tools

*Thoughts* - I'd heard through a podcast I listen to (can't currently remember which one) that npm scripts were decent for running and watching things, and then the other day stumbled onto a link about using npm scripts as a build tool that looked to be about an hour long. Had initially hoped to get it all done tonight, but through writing my own file along with the videos and adding in notes as I go (so I can actually stand some chance of remember wtf it all does lol) I only made it about halfway through. Some interesting things, definitely learning and getting some ideas that I might be able to play with and use for future projects. Looots of dependencies in these videos though. Still sooooo much I haven't even been exposed to, much less actually using and understanding them. No worries - I'll get there eventually, if I need to.

---------------------------------------------------------------------------------------------------------------------

Day 34 - Feb 14, 2017 (1h20m)

*Today's Challenge* - Finished npm scripts course, eyes and nose on daily css beaver done

*Thoughts* - I think I might have a few interesting things from the npm scripts videos I watched...but honestly I know I missed good info in the last one because I legit almost fell asleep during it. Definitely felt like something I would have gotten more out of if I was a lot more used to npm and the crap ton of packages that exist out there. To finish off my time today, I got back to my beaver and worked out his general eye shape and the beginnings of the nose/mouth area. It's getting harder to get my hour in lately....I'm working longer hours and starting later and just generally tired when I get home. Plus, I think I might be itching for another real project and not so much smaller things. I'm still determined to keep learning and getting better and continuing with this, so I've gotta work on figuring this out so I get my coding time in each weeknight. I want to get my beaver finished, but it might be about time to start my next project idea - a new website for my current company!

--------------------------------------------------------------------------------------------------------------------

Day 35 - Feb 15, 2017 (1h10m)

*Today's Challenge* - Workin' on my CSS beaver

*Thoughts* - Man....beaver's are hard! lol Odd looking creatures too. Half my time was spent playing around with the idea I had, and then the other half was spent finding a picture I actually liked and therefore scrapping what I had and starting over. This one, I think, is going to turn out much better. At least, I hope so! 

---------------------------------------------------------------------------------------------------------------------

Day 36 - Feb. 16, 2017 (1h8m)

*Today's Challenge* - More beaver work.

*Thoughts* - This little dude feels like he's taking forever! lol I got the arm, leg, and tail done today though. Used linear gradients for his little paws, which I think turned out decently. Nothing's blending quite like I want, buuuuut it's good enough for now. Tomorrow will be getting the face details then hopefully any final touches, and I can be finished with him!

--------------------------------------------------------------------------------------------------------------------

Day 37 - Feb. 19, 2017 (1h30m)

*Today's Challenge* - Finished up my daily CSS beaver!

*Thoughts* - Well, he doesn't look quite like the picture I was using as inspiration, but my beaver is as close as I can get him and he's done! I was able to play a lot with gradients this time around....some linear ones for his legs and tail, and a pattern using some layers of linear ones (which I found from someone else online and changed the colors of lol) for the 'fur' texture. Overall I think he turned out alright....I'm always well aware my amateur status when I do these lol but at least I finished and it looks somewhat like a beaver. lol

---------------------------------------------------------------------------------------------------------------------

Day 38 - Feb. 21, 2017 (1h13m)

*Today's Challenge* - 3 JS30 videos

*Thoughts* - Today's videos: ajax type ahead, more array functions, and html5 canvas! I've worked with type ahead before, and at least minor experience with the array functions, so more of that was extra exposure to ES6. The canvas thing was really fun though! I have no doubt it just barely covered the surface of what it's capable of, but it was still a lot of fun to play with. :)

---------------------------------------------------------------------------------------------------------------------

Day 39 - Feb. 22, 2017 (1h23m)

*Today's Challenge* - 3 more JS30 videos

*Thoughts* - Lots of interesting things today. Learned more console commands, like console.info, error, warn, table, dir, plus ways to add different text and variable names in. Learned how to check all checkboxes in between a set of checked boxes while holding down shift. And played with controlling an HTML5 video player. My brain is feeling pretty full today. I do feel like I'm slowly getting more used to ES6 notation of things...I don't really fully understand the what or why of how things are how they are, but I'm feeling like I'm sort of able to see how they work. Definitely still want to learn more about exactly what all the things mean/do, but at least I'm reasonably getting the logic behind it all, which is good.

----------------------------------------------------------------------------------------------------------------------

Day 40 - Feb. 23, 2017 (1h03m)

*Today's Challenge* - Days 13-14 of JS30

*Thoughts* - Today's work included detecting key sequences, sliding objects in & out on scroll, and reference vs copy of arrays & objects. Lots of good basic JS knowledge, as far as detecting certain events and dealing with copies and such. Also got the pen made and background box set for my next daily CSS challenge. Gotta get some ideas flowing....

-----------------------------------------------------------------------------------------------------------------------

Day 41 - Feb. 27, 2017 (1h15m)

*Today's Challenge* - JS30 local storage video, deciding on guide/plan going forward

*Thoughts* - I was pretty interested in this one - I'd tried to use local storage before on a previous project and didn't have any luck getting it to work. I was honestly hoping to understand a bit more by the time the video was done, but overall - pretty decent one. It was good to see it actually working, to get a taste for it at least, and I think it'll be enough that I can play with it in the future and have better success than I did previously. The rest of my time was spent working out which/how many videos to do each day and when I'd finish the course up, plus deciding if I wanted to continue with the current freeCodeCamp curriculum or switch to the beta. I'm gonna switch to the beta after I finish JS30. I like the idea of how they've got it broken up now, I think it'll give some more/better understanding of things, plus I like the idea of having the projects tested each time. A lot of them I'll have done already with the current curriculum and can then update them to pass the new tests. I'll still have to wait awhile (probably) to actually get the certificates, depending on when it goes live, but at that point it'll be relatively easy to simply resubmit my project links and do the algorithms again (practice which will always help lol). Also I'm going to aim for one Daily CSS image every week or two, since I like the challenge and I think it'll be a good skill to keep working on. This'll be what I'm counting for my 100 days...luckily I'm getting to work on projects for work while I'm actually on the clock on Tues/Thurs, which is nice. I'll be taking weekends off from here on out to keep myself from burning out. Excited to see what I continue to learn and build. :)

---------------------------------------------------------------------------------------------------------------------

Day 42 - Feb. 28, 2017 (1h18m)

*Today's Challenge* - JS30 : text shadow w/ mouse move, sorting w/out articles(the/an), tally times; + html setup on daily css tiger

*Thoughts* - The videos were reasonably light and straight forward today. Text shadow playing was fun. The sorting made a lot of sense, most of it I felt like I would've gotten but I learned a new way to do some regex things. Tallying times was decent practice. Plus I got the html divs & classes all set up for my new css drawing, & a picture/idea picked out for how I want to draw him. That's the easier part lol - the hard part comes with actually working out the sizes of parts and fitting them all together.

----------------------------------------------------------------------------------------------------------------------

Day 43 - Mar. 1, 2017 (1h08m)

*Challenge* - JS30 webcam fun video, work on daily css tiger

*Thoughts* - The webcam video was pretty fun to play with after the fact. My own computer doesn't have a webcam, but my partner's does, so we turned it on his and (once we got it functioning on his computer properly lol) had some fun with it. He's liked a lot of the things we've made in this course and wants me to repurpose some of the stuff for him to use in other things, so it'll be fun in the future to see how well that goes. Got the basic head and face shapes done for my tiger. I think this one's gonna turn out really nice, actually - I'm at least excited about my idea and the face shape is working nicely so far, so that might change. lol But I think right now it's going to turn out really well. :)

--------------------------------------------------------------------------------------------------------------------------

Day 44 - Mar. 2, 2017 (1h27m)

*Challenge* - JS30 speech recognition, geolocation, and follow along links + more tiger work

*Thoughts* - Today's videos weren't quite as fun, simply because I don't have a microphone on my desktop & I don't have a mac for the recommended simulator (and wasn't going to look for a windows one for one video). I tried the speech one on my phone (I'm doing them all on codepen) and it registered my speech, though it wouldn't add new paragraphs, only overwrite each one. I think it had more to do with how it was using the phone's microphone than the code, though. The geolocation one I didn't test, might try it tomorrow while I'm at work or something. The links was cool though. And my tiger is coming along nicely, got the eyes, nose, and most of the mouth done tonight. Definitely coming along nicely. :) 

---------------------------------------------------------------------------------------------------------------------------

Day 45 - Mar. 3, 2017 (1h35m)

*Challenge* - Tiger work

*Thoughts* - Man, tonight felt like I worked waaaaay more than 1.5 hours. I had hoped to make way more progress tonight than I did, but some of this is still evading me. I got the ears done though, and one cheek hair. lol 

-------------------------------------------------------------------------------------------------------------------

Day 46 - Mar. 6, 2017 (2h20m)

*Challenge* - Finished my Daily CSS tiger!

*Thoughts* - Worked a lot longer tonight, and finally got my tiger done! I spent the first part of my time finding some articles about using box shadow and pseudo elements with css. The pseudo elements I still couldn't get to work in my own code, though the examples I played with worked....so more to learn there, clearly I missed something. But the box shadow worked like a charm and I was able to use it to really make my tiger come out just how I wanted. Super, super pleased with how it turned out. :) Plus I found some good reference articles, including a good one listing all kinds of shapes made using a single div! 

*Project Link* - https://codepen.io/lindakatcodes/full/MpWPpN/

-------------------------------------------------------------------------------------------------------------------

Day 47 - Mar. 8, 2017 (1h18m)

*Challenge* - JS30 day - speech synthesis, sticky nav, event capture/propagation/bubbling/once

*Thoughts* - The videos were good today - I was worried I wouldn't be able to enjoy the speech synthesis one but luckily I was able to get the google voices so that was a fun one. Sticky nav was very helpful and will come in handy when I redo my portfolio soonish. And the event one had good info on event listeners that was nice to know. I also did a bit of research on what I wanna do for my next daily css - favorite animated animal. Hoping he comes out just as well as my tiger did, which has gotten a lot of awesome attention on Twitter. :) 

---------------------------------------------------------------------------------------------------------------------

Day 48 - Mar. 9, 2017 (44m)

*Challenge* - JS30 follow along dropdown & click drag scroll

*Thoughts* - The follow along dropdown is pretty nifty, can definitely see that being used in the future. Real nice effect. The click and drag scroll is pretty decent too. Thinking about how it could be improved to go faster / slower depending on mouse speed and when you release and such kind of boggles my mind. Cutting it short tonight as I'm just feeling bushed....I could've done another video to reach a full hour but honestly I want to be able to pay full attention and as sleepy as I am right now it just wouldn't happen. Plus I did manage some work on the company website during work hours today, so I'm calling it good.

--------------------------------------------------------------------------------------------------------------------

Day 49 - Mar. 10, 2017 (2h17m)

*Challenge* - Finished JS30! Video speed controller, countdown clock, & whack a mole game

*Thoughts* - Well....I finished it! Definitely grew to really enjoy the course and have honestly been exposed to a lot, and at least some of it has sunk in. Some I still need to dive into more. :) Pretty good videos to wind the course down with. The video controller was relatively simple and fun. The countdown clock was very interesting and will help me with one of my freeCodeCamp projects down the road. And the whack a mole game was fun, once I figured out a way to load the svg images so codepen could see them. :) Had to use my personal site for hosting, basically. But it's the first one I've added a small bit of extra styling to, adding a game over text and tweaking the start button a touch. Definitely lots to think about and reuse in the future, and sparked an interest in learning more about ES6 and just general building. Good way to (basically) end the first half of my 100 Days!

--------------------------------------------------------------------------------------------------------------------

Day 50 - Mar. 15, 2017 (1h45m)

*Challenge* - Adjustment on personal home page, container set up for next daily CSS image, research on possible books/classes

*Thoughts* - A few things done today. Got the background color and container positioning set for my next CSS image, plus the colors identified for my character so it's ready when I get into the actual shape making. Most of my time tonight went to adjusting my personal home/start page. I took off a course I just finished, created/touched up a few icons for new pages I wanted to add, and did some rearranging of links/icons so it flows well. Then a bit of research on books to read and/or classes to start to further my learning. I'm having a hard time deciding on a true course of action. I have a reasonable idea of the work that I want to create most and a layman's understanding of what it is that I should learn....but when I go to actually research and find materials to learn that, I either feel way over my head or it just doesn't sound right. Like I'm getting ahead of myself, or else I can't find a straight forward path. I don't know. I love working with JavaScript, and I find myself wanting to create pages/apps that help to organize, track, and update inventory/work orders/data in general. So clearly I need some database work, and some back-end JS. Just...haven't managed to come across the right materials to really help me understand how to do it. So I guess my current plan is to work through the freeCodeCamp beta (I like the organization better, plus new material I think will help), read either You Don't Know JS or Eloquent JS (likely both, just gotta pick one to start with), and work on these daily CSS images. And keep an eye/ear out for other things that will help me learn more about databases and what can work with JS and working with forms and storing/updating data. 

-----------------------------------------------------------------------------------------------------------------------

Day 51 - Mar. 16, 2017 (1h52m)

*Challenge* - Started the freeCodeCamp beta route, plus some work on my daily css image

*Thoughts* - So I've decided I want to work through the beta version of freeCodeCamp, both because I think the curriculum seems filled out better and because it's been a big help to me and I want to help test and point out / fix problems so the beta can become the main and help more people. I made it about halfway through the HTML section, making little notes along the way of minor changes I think could/should be made. I made my first github issue comment too! lol Was able to take a gif of my screen to show a small problem and add to an issue already started to help clarify what's going on for those who could fix it. 

Also made some decent progress on my next css image, got the face shape worked out and the ears, some basic posititioning set and colors picked out that match as best as possible. My image won't have any of the texture or color gradients as the image I'm working off of, but I'm gonna get it as close as I can, dangit. lol Also my image is my favorite character from a video game that I adore, and it was super fun working on this image while listening to the soundtrack from the game. :)

------------------------------------------------------------------------------------------------------------------------

Day 52 - Mar. 17, 2017 (1h43m)

*Challenge* - Finished fcc beta HTML section, more work on daily css image

*Thoughts* - So, the HTML section is done now. No new bugs that I noticed, just continuations of issues I noticed yesterday. The two big ones have current open issues on github so I'm not the only one noticing them and they're being addressed. I made some good progress on my image today too, got the ear details and hat done. All that's left to do is facial details - eyes, brows, nose, and mouth. I think this one's gonna turn out really cute and just how I want. :) Another good feeling! Gonna ride it while I have it, for sure. lol

----------------------------------------------------------------------------------------------------------------------

Day 53 - Mar. 20, 2017 (1h30m)

*Challenge* - fcc beta CSS challenges, more daily css work

*Thoughts* - Got started later than I intended tonight but I still got some good time in. Made it a third of the way through the fcc beta CSS section - all stuff I know already, but I'm trying to check for spelling and understanding in the instructions. Then spent the rest of my time working on my daily css image. I only got the eyes and eyebrows done tonight, which doesn't feel like enough...but they were being super finicky. lol Definitely coming along! 

------------------------------------------------------------------------------------------------------------------------

Day 54 - Mar. 21, 2017 (1h27m)

*Challenge* - fcc beta CSS challenges, daily css work

*Thoughts* - More CSS challenges on fcc beta tonight. Thought the parts about inheritance of styles was pretty nicely done, though it irks me that you can't really see what you're doing on the little sample screen. Spent most of my time working on my css image - I got the nose and mouth basically set up tonight, so all that's really left is some more tweaks on the shape of facial features and maybe a few details for the tounge and eyebrows. He's so close! Honestly he looked more like himself without the facial features lol which tells me I'm still pretty bad at working out detailed shapes that aren't fully circular or rectangular. But it's all practice, so eventually I'm bound to get better. lol Still, he's looking pretty decent - some finishing touches are all that's left!

------------------------------------------------------------------------------------------------------------------------

Day 55 - Mar. 22, 2017 (1h43m)

*Challenge* - daily CSS image work

*Thoughts* - UGH. The outline of my character looks just like I want....but the facial features are all wrong, and just look too fake/cartoony. Which, you know, this IS a cartoon/animated character I'm making. But still. It just looks silly and amateur and wrong, and I don't like it. But also am completely out of ideas for making it more like I want. No idea what to do now. Pretty frustrating spending all night on a thing to get it done and feeling worse about it now than I did when I started tonight. Honestly not sure what I'm gonna do.

----------------------------------------------------------------------------------------------------------------------

Day 56 - Mar. 23, 2017 (1h26m)

*Challenge* - continuing daily css work

*Thoughts* - Went back to the drawing board today and made some big changes on my current image. Adjusted the face height as I felt I'd made it too tall, so then had to go in and adjust the cheeks and ears and such. Then (almost) completely redid the face, working on each piece at a time to make adjustments to size and shape and then copy and tweak it for the other side of the face. Definitely feeling better than I was yesterday. Just the mouth to go tomorrow, and possibly some more eyebrow work if I get the mouth curve working like I want (as the brows could use some more curving as well if it's possible). Hallelujiah, I'm so glad this seems to be working better. Yesterday was rough.

------------------------------------------------------------------------------------------------------------------------

Day 57 - Mar. 24, 2017 (1h57m)

*Challenge* - Finished my daily css image!

*Thoughts* - Well, my image is as good and done as it's going to get. The main things that will make it better are skills and practice that I just don't have yet. I'm definitely much happier with it now than I was a few days ago. I wish I could do curved lines more/better, especially lines that have multiple different curves, which border radius can't do. Will need to look into something for that. Also will soon need to get into 3d transforms and ways to gives some depth to my drawings. Otherwise....I think it's a pretty decent first drawing of one of my favorite animated characters ever. Will likely want to come back to him down the road and try another one when I've got some more skill under my belt.

-------------------------------------------------------------------------------------------------------------------------

Day 58 - Mar. 27, 2017 (45m)

*Challenge* - fcc beta CSS challenges

*Thoughts* - Getting myself caught up on the freeCodeCamp beta challenges tonight. Still making notes of the random things I notice that somehow I'll need to post to the group github so others can test and fix if needed. Couldn't make it the full hour tonight, I'm falling asleep at my desk and that's no good for learning.

--------------------------------------------------------------------------------------------------------------------------

Day 59 - Mar. 28, 2017 (43m)

*Challenge* - fcc beta Applied Visual Design challenges

*Thoughts* - Another shorter day today. Looking into buying a laptop for mobile coding and so I got distracted. :) Made some good progress on the fcc beta site tonight though. Actually learned a new thing too, hsl()! Also up to a point where the rest of this section will be new stuff for me, playing with animations in css and such which I've been wanting to get into but haven't been sure where to start. 

-----------------------------------------------------------------------------------------------------------------------

Day 60 - Mar. 30, 2017 (1h07m)

*Challenge* - fcc beta Finished applied visual design section

*Thoughts* - Got some good, new practice with the end of this section! Worked with animations, keyframes, and bezier curves. I hadn't really delved into the idea of animations and how that might work so this was a nice introduction. Definitely interesting in trying some of this out in my next CSS image. Also a few examples of using :before and :after to create images which was really nice to see, as I've still struggled to implement this at all in my challenges. The bezier curve section could use some visuals though...describing a curve with simply words is a bit hard to understand what it's doing and how it works. Overall a really nice end to the section though and I'm glad I've started to gain some new informaiton. A lot of this first section in the beta is information I've already covered a few times before so is mostly practice, so it's fun to get to some new ideas.

---------------------------------------------------------------------------------------------------------------------------

Day 61 - Mar. 31, 2017 (40m)

*Challenge* - fcc beta Accessibility challenges

*Thoughts* - Got through half of the accessibility section on the fcc beta page. (Honestly don't remember much exactly as I forgot to log this on the day it actually happened. lol)

---------------------------------------------------------------------------------------------------------------------------

Day 62 - Apr. 4, 2017 (1h03m)

*Challenge* - Finished fcc beta accessibilty section & responsive web design principles section

*Thoughts* - More good information tonight, covering accessibility and responsiveness. I'm almost positive I won't remember all the accessibility stuff as I keep moving forward....a lot of it was pretty surface level and didn't realy feel like it sunk in. But also a lot was pretty common sense "label your stuff and keep it in order" ideas, so maybe more will get through than I think. I felt the same about the responsive web design section, which was much shorter and mostly covered @media and viewport sizing. All good info, just....not sure how much really sank in. We'll see in a day or two as I'm about to hit the first projects! 

----------------------------------------------------------------------------------------------------------------------------

Day 63 - Apr. 5, 2017 (1h06m)

*Challenge* - fcc beta flexbox challenges + tribute page research

*Thoughts* - Finished the last of the learning/reading challenges for the Responsive Web Design section! Now on to the projects. The flexbox section finished tonight was decent....felt like it gave a good overview of the different properties. Definitely liked having this in there, instead of jumping straight to Bootstrap as the current version does. This will be a skillset that'll go a lot farther into a developer's workflow. Did some more checking out of other people's tribute pages to get some creative ideas. I feel like I want to completely redo a new tribute page instead of updating my first one to pass the new tests (which I love the idea of the tests!). Just....have no idea who to make it about! Same problem I had last time. lol 

----------------------------------------------------------------------------------------------------------------------------

Day 64: Apr. 7, 2017 (3h7m)

*Challenge* - fcc beta tribute page project

*Thoughts* - Finally decided on a subject for my tribute page - my favorite baseball team. :) Picked out some history facts of the team to put into the page, got some pictures, and got it all set up! Actually pretty pleased with it. It's still simpler than a lot of other samples I saw, but I think it looks decent for a night's work. Felt good enough about it to submit it and move forward. 

*Project Link* - https://codepen.io/lindakatcodes/full/wJbZwB/

----------------------------------------------------------------------------------------------------------------------------

Day 65: Apr. 10, 2017 (1h1m)

*Challenge* - Started fcc beta survey form project

*Thoughts* - Having some fun with this one in choosing the questions. :) The hardest part for me in all of these is picking/writing the material...this one I had an idea on the way home so I'm going to make it work. Got about halfway through writing out the questions & basic format tonight, so should probably finish that up tomorrow and get started on the design. We'll see how it goes!

-----------------------------------------------------------------------------------------------------------------------------

Day 66: Apr. 11, 2017 (1h18m)

*Challenge* - More work on survey form

*Thoughts* - Made some good progress on this tonight. Got the questions finished up and all the tests pass. Picked out the font and got the main section styled. All that's left is to touch up styling on the questions themselves, style up the button, and then see if I can get the submit response to work how I have in mind. My questions are so ridiculous(ly good), I just can't with it. lol Can't wait to share it when it's done! 

----------------------------------------------------------------------------------------------------------------------------


