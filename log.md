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

