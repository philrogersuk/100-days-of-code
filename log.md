# 100 Days Of Code - Log

### Day 26: 2nd August 2020

**Today's Progress**: Create test react styled-component

**Thoughts:**
- Test to embed a static component into sidebar
- Helped by J with last step
- Currently injects from static HTML -> can I inject from a script on HTML side?

**Link to work:** http://www.hendonfc.net

### Day 25: 1st August 2020

**Today's Progress**: News Admin Controller fully tested!

**Thoughts:**
- Put all changes in last week live
- Sponsor box looks much better!

**Link to work:** http://www.hendonfc.net



### Day N/A: 31st July 2020

**Today's Progress**: Day off

**Thoughts:**

**Link to work:** N/A


### Day 24: 30th July 2020

**Today's Progress**: Further admin controller testing, refactor return values on POST

**Thoughts:**
- ResponseStatus still needs some work
- Edit left to test

**Link to work:** N/A


### Day 23: 29th July 2020

**Today's Progress**: Some admin controller testing

**Thoughts:**
- Not too much work done

**Link to work:** N/A


### Day x: 28th July 2020

**Today's Progress**: None

**Thoughts:**
- Couldn't be bothered to do anything
- Bleugh

**Link to work:** N/A


### Day 22: 27th July 2020

**Today's Progress**: Configure acesss log & re-style sponsor box

**Thoughts:** 
- Also started news refactor; separation of concerns
- Improving test coverage (all classes except Admin Controller are done)

**Link to work:** N/A


### Day 21: 26th July 2020

**Today's Progress**: 404 fixes.

**Thoughts:** 
- Fixed a heap of issues relating to 404s and 500s
- Bit painstaking, but necessary

**Link to work:** N/A


### Day 20: 25th July 2020

**Today's Progress**: Merged doc upload, added Corona-RA document.

**Thoughts:** 
- Bit crude; non relational.

**Link to work:** N/A


### Day x: 24th July 2020

Day off

### Day 19: 23rd July 2020

**Today's Progress**: Started document upload functionality

**Thoughts:** 
- Able to build on image upload :)
- Quick to create an upload page/index.
- Still need to provide a way of linking to them in News items etc.

**Link to work:** N/A


### Day 18: 22nd July 2020

**Today's Progress**: Mostly smaller changes

**Thoughts:** 
- Quick create of Covid banner; bit ugly, but fast and functional
- Added info about unplayed and abandoned fixtures to display
- Fix to allow creation of league entries
- Add horizontal line above lower advert to demark end of main content.

**Link to work:** N/A


### Day 17: 21st July 2020

**Today's Progress**: 404 fixes + Analytics

**Thoughts:** 
- Fixed a number of 404s on various pages
- Fixed GA script.
- Plenty more 404s to handle, but dealt with 30+

**Link to work:** N/A

### Day 16: 20th July 2020

**Today's Progress**: New website support

**Thoughts:** 
- Upgrade EC2 server to t3a.small; memory issues led to downtime
- Uploaded last season's penpic images
- Change server timezone to London
- Do work to handle pages that have "Gone" on the new site

**Link to work:** N/A

# 100 Days Of Code - Log

### Day 15: 19th July 2020

**Today's Progress**: New website goes live

**Thoughts:** 
- Lots of small fixes
- Had to reduce springboot xmx to 256mb.
- Seems stable
- Most of the day adding assets/content

**Link to work:** https://www.hendonfc.net

### Day 14: 18th July 2020

**Today's Progress**: Now starts greensnet as a service

**Thoughts:** 
- Bit messy to achieve, but got there. Need to save .conf and .service files locally and script anything required still
- Now have uptime monitor for main site and test url at uptimerobot.com.

**Link to work:** https://test.hendonfc.net

### Day x: 17th July 2020

Day off

### Day 13: 16th July 2020

**Today's Progress**: Fixed youtube video link on HFCTV watch page

**Thoughts:** 
- Super simple & fast. 5 minute fix.

**Link to work:** N/A

### Day 12: 15th July 2020

**Today's Progress**: Added new sponsor to HFCTV page on new site

**Thoughts:** 
- Bad; not automated
- Good; quick and not common (yearly at the most)
- Not committed yet; need to fix the "watch" page still.

**Link to work:** N/A


### Day 11: 14th July 2020

**Today's Progress**: Fixed bug on reports

**Thoughts:** 
- Small quick change and fix
- Used optionals to handle possible nulls; could be cleaner overall, but keeps the fix isolated from the wider architecture.

**Link to work:** N/A

### Day 10: 13th July 2020

**Today's Progress**: News Items & Youtube fully integrated nicely

**Thoughts:** 
- Easier than I thought. A few silly bugs from yesterday though; obvs wasn't up to it then!

**Link to work:** N/A

### Day 9: 12th July 2020

**Today's Progress**: Add corporate sponsors incl logo & start news item video itgration 

**Thoughts:** 
- Bleugh.

**Link to work:** N/A


### Day 8: 11th July 2020

**Today's Progress**: Fixes to admin pages

**Thoughts:** 
- Snowball admin now available
- Penpics now updated separately to rest of player profile
- Also installed Docker on Win 10 Home!!!

**Link to work:** N/A


### Day x: 10th July 2020

Day off

### Day 7: 9th July 2020

**Today's Progress**: Fixes to the staff admin page

**Thoughts:** 
- It's a horrific page
- Need to handle penpics better
- Does at least work. Just about!

**Link to work:** N/A


### Day 6: 8th July 2020

**Today's Progress**: React.js pluralsight course stuff

**Thoughts:** 
- Useful refresh of what I went through ages ago
- Should setup Greensnet npm-app with my own config, not create-react-js

**Link to work:** N/A



### Day 5: 7th July 2020

**Today's Progress**: Refactoring, refactoring, refactoring

**Thoughts:** 
- Cleaner code = nicer code :)
- Lots to still do though :(

**Link to work:** N/A


### Day 4: 6th July 2020

**Today's Progress**: Monday = Exercism exercises. 4 simple solutions completed

**Thoughts:** 
- Relatively simple exercises. Completed:
  - Pangram
  - Hamming
  - Gigasecond
  - Space Age
- Surprised to see two stars on an earlier solution!

**Link to work:** https://github.com/philrogersuk/Exercism


### Day 3: 5th July 2020

**Today's Progress**: Small bugfixes and CMS migration

**Thoughts:** 
- Added total player appearances and goals back into player profiles
- Added the ability to enter teams into a league back into CMS.
- Some progress on Stand sponsorship CMS, but incomplete.
- Some minor refactoring improvements, but much to still do!

**Link to work:** N/A;


### Day 2: 4th July 2020

**Today's Progress**: Updates to Stand Sponsorship page. Now works on new site and uses new styling

**Thoughts:** 
- Incomplete; needs the page content adding and styling. Also need to add the admin tools for this page.
- Also migrated test.hendonfc.net to port 443 with the new site and refreshed the database from prod site.
- Fixed index out of bounds bug on front page league table.
- Slow work today.

**Link to work:** https://test.hendonfc.net/GaryMcCannStand


### Day 1: 3rd July 2020

**Today's Progress**: Automated SSL Certificate renewal

**Thoughts:** 
- Scripted the renewal of SSL certificates on Unix.
- Stops the springboot app, renews the certificates and restarts the app. Neat & secure :+1:

**Link to work:** N/A

