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

