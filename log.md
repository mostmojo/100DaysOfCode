### Day 1: Friday, Feb 1, 2019

**Today's Progress**: Restarted development on a pro-bono site redesign I was doing for a volunteer group I'm part of ([Coder Brixton](http://coderbrixton.com/), they're cool!). Had to put it on hold for a couple of weeks but it works out to be a good project to use for \#100DaysOfCode. 

**Thoughts**: I just finished a boot camp after leaving my job. It's safe to say that job hunting itself is a miserable pit of despair. But the one thing that actually takes my mind off it and I find enjoyment in is coding. So I figured committing to the 100 days would be a good way to fend off the blues. Also, it means that I get to improve my skillset which is great.
I also realise that I actually really like front end. I originally found it quite intimidating but the recent changes to CSS are amazing. 

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 2: Saturday, Feb 2, 2019

**Today's Progress**: More work done on the Coder Brixton site. Concentrated on getting the Vimeo embed to be responsive.

**Thoughts**: After a fair amount of frustration trying different approaches, CSS grid once again came to the rescue. The solution ended up being a 3x3 grid and placing the video in the central container. The trick to keeping the aspect ratio at 16:9 of the video was to actually use a width of 80vw and a height of 45vw (NOT vh). I managed to find this aspect ratio trick from a codepan trying to solve the same problem (but with a different implementation). 

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Codepen: A less awful responsive vimeo embed (by Liz)](https://codepen.io/lixelart/pen/eyZNeX)

### Day 3: Sunday, Feb 3, 2019

**Today's Progress**: Started re-designing the way quotations looked like on the site. Went for a card format that looks a lot nicer.

**Thoughts**: A fair bit of time was spent getting responsive behaviour to work correctly using `@media`. It went okay, but it did feel like trial and error at times. If anybody reading this has and advice on methodology and approaches on responsive behaviour, please reach out to me on Twitter via [@BrotherKaif](http://twitter.com/brotherkaif)! 

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 4: Monday, Feb 4, 2019

**Today's Progress**: Fixed a bug with the responsive cards. Also added in some FontAwesome icons.

**Thoughts**: Fixing bugs with responsive elements is horrible. At first I attempted to redo the entire card only to totally revert back to what I had originally and just tweak it slightly. Lesson learned, it's not worth tearing it all down just to resolve an edge case that can be fixed with minor tweaks. Also added in some Font Awesome icons, because who doesn't like Font Awesome?!

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Font Awesome](https://fontawesome.com/)

### Day 5: Tuesday, Feb 5, 2019

**Today's Progress**: A bit more work on styling the rest of the sections.

**Thoughts**: Didn't have a huge amount of time to code today so tackled some of the low hanging fruit of marking up the sections. Also started a project kanban on GitHub to start keeping track of the tasks that still need to be done.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 6: Wednesday, Feb 6, 2019

**Today's Progress**: Loads of stuff. Got the photo gallery sorted out and started making the sections responsive.

**Thoughts**: Had a lot more time to code today. Got the photo gallery sorted thanks to a wonderful tutorial (linked below). Also started work on making the main sections responsive. Nearly there but will continue tomorrow. Another side note, it's becoming clear that CSS grid and flex pretty much negate the need for frameworks like Bootstrap. So I've slowly been pulling out the Bootstrap classes so that I can strip the thing out entirely by the end of it.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Mosaic Layouts with CSS Grid | Axel Valdez](https://axelvaldez.mx/blog/2018/05/mosaic-layout-with-css-grid/)

### Day 7: Thursday, Feb 7, 2019

**Today's Progress**: Finally got the responsive sections to work correctly.

**Thoughts**: Getting the responsive behaviour to work well using CSS Grid is a bit of a challenge but I managed to track down where a lot of the bugs were coming from (it was a simple syntax error). Found a great guide which got me through some of the tough bits which I've linked below. Just a couple of more components left and then I can get onto the fun stuff of choosing fonts, colours and other little tweaks.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Day 8: Friday, Feb 8, 2019

**Today's Progress**: Worked on the cards for the mentors

**Thoughts**: Things are starting to come together! Today I worked on the mentor cards. The main components of the site are pretty much complete. I feel the next few days will be spent doing layout tweaks.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 9: Saturday, Feb 9, 2019

**Today's Progress**: Rebuilt the cards using CSS grid.

**Thoughts**: I wanted to have a nice gradient to overlay on the mentor avatar, but the way I built the cards yesterday meant I'd have to do some complex absolute/relative placement. Re-did the cards in (wait for it...) CSS grid. Once again, I'm convinced that this is *the* solution to about 90% of CSS layout work. The card took me about an 30 mins to re-do; whereas yesterday it took me 3 hours to put together a pretty complex and difficult to manage layout using `position: relative;` and `position: absolute;`.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Day 10: Sunday, Feb 10, 2019

**Today's Progress**: Work done on responsive behaviour for mentor cards. 

**Thoughts**: It's a Sunday so didn't do anything too intense. Just worked on the responsive behaviour for the mentor cards. I really want to make sure that the site looks good on any size of device. Its a bit of extra work, but I'm learning a fair bit in the prcoess.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 11: Monday, Feb 11, 2019

**Today's Progress**: Learning Git rebasing.

**Thoughts**: Had to use git rebasing for the first time today. I _think_ it's worked out okay. It's a bit terrifying as you are essentially re-writing history. Fingers crossed the pull request goes in without any issues.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Working while waiting for pending PR](https://stackoverflow.com/questions/35790561/working-while-waiting-for-pending-pr)

### Day 12: Tuesday, Feb 12, 2019

**Today's Progress**: Minor footer changes (and setup experimentation)

**Thoughts**: Just a small one today, worked on the footer. The biggest thing today was actually to do with trying out a new setup! I decided to try out a cloud based IDE and moved my work over to coder.com. So far, I'm really impressed! Essentially, it's Visual Studio Code (like, the _actual_ VSCode) in the browser with a virtual Linux server behind it. What makes this even more impressive is that it's browser based and so totally works in a chromebook. I think I may stick with this one for a while longer.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Coder (the cloud IDE I've been playing around with)](https://coder.com)

### Day 13: Wednesday, Feb 13, 2019

**Today's Progress**: Updating links and optimising images.

**Thoughts**: Ran into one of the first big limitations of this cloud IDE; No easy way to upload files to your virtual machine! The horrible workaround that I came up with was to host the images on a free service somewhere and then use `wget` to pull them onto the virtual machine again. Not the smoothest solution but it all worked out okay in the end. Hopefully they'll fix it soon and provide an easier means of getting files on there. I mean, it is an alpha so I'll cut them a bit of slack at least.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 14: Thursday, Feb 14, 2019

**Today's Progress**: Practiced API calls in JavaScript

**Thoughts**: Spent the day working at Le Wagon code bootcamp on teaching assistant duties. The topic today was `fetch` in JavaScript (and API interaction in general). Quite a few interesting problems to resolve but really good practice overall!

**Link(s) to work**
1. [Le Wagon](https://www.lewagon.com/)

### Day 15: Friday, Feb 15, 2019

**Today's Progress**: Started work on supporters section

**Thoughts**: Back on the Coder Brixton redesign today. Added in a section to link back to our supporters. Also reached out to one of them to get hold of some nice high res versions of their logo.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 16: Saturday, Feb 16, 2019

**Today's Progress**: More work on the supporters section

**Thoughts**: Added in some small animation to the supporters section.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 17: Sunday, Feb 17, 2019

**Today's Progress**: Started work on a navbar

**Thoughts**: Added in a navbar by utilising code from a previous project. However, the navbar does rely quite heavily on the Bootstrap library which I have been wanting to remove from the for a couple of weeks. I may redo this next week with a non-bootstrap version.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 18: Monday, Feb 18, 2019

**Today's Progress**: Re-coded the navbar

**Thoughts**: Decided to re-code the navbar instead of using the one from an old project. The new navbar is going to be vanilla css and not rely on Bootstrap. Found a pretty good thread on Reddit about best practice for this. Less is definitely more when it comes to this kind of stuff. Not really styled the navbar yet, I just want to get the responsive behaviour sorted tomorrow.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Best Vanilla Navbar Practices (Reddit thread)](https://www.reddit.com/r/HTML/comments/8m11b3/best_vanilla_navbar_practices/)
2. [Vanilla Header (Codepen)](https://codepen.io/MathiasaurusRex/pen/NMZLxg)

### Day 19: Tuesday, Feb 19, 2019

**Today's Progress**: Git rebasing and link styling

**Thoughts**: Had to do another `git rebase` as my previous branch got merged in. I'm feeling a bit better about rebasing now. Although it does seem like it can get very messy very quickly. For this project things aren't too complicated as it's just me working on it. However, I can see how it can get very messy very quickly if working in a team with poor communication. Also managed to do a bit more styling on the navbar links. Will work on responsive behaviour tomorrow.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 20: Wednesday, Feb 20, 2019

**Today's Progress**: Tried (and failed) to work on navbar

**Thoughts**: I made an attempt to put together a responsive navbar that didn't require Javascript based on a guide that I found. Unfortunately, it didn't work out too well and I think I'm going to have to bite the bullet and at least accept a bit of Javascript. To be honest, I'm not quite sure why I'm avoiding it, I actually _do_ want to learn Javascript. I might have to hit some more tutorials.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [How To Create A Responsive Navigation Menu Using Only CSS](https://medialoot.com/blog/how-to-create-a-responsive-navigation-menu-using-only-css/)

### Day 21: Thursday, Feb 21, 2019

**Today's Progress**: Got the navbar behaviour working

**Thoughts**: Found a guide to get the navbar working properly. The styling is still all over the place and will need a bit of work, but the basic responsive behaviour is there.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

**Link(s) to resources**
1. [Create an Absolute Basic Mobile CSS Responsive Navigation Menu](https://blog.teamtreehouse.com/create-an-absolute-basic-mobile-css-responsive-navigation-menu)

### Day 22: Friday, Feb 22, 2019

**Today's Progress**: Added in another supporter

**Thoughts**: Couldn't do a huge amount due to time. But I did manage to get another supporter added to the list. Also made some tweaks to the layout to center align the elements vertically.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 23: Saturday, Feb 23, 2019

**Today's Progress**: Developed navbar

**Thoughts**: Sorted out the navbar. It's unstyled, but it's behaving responsively now. Will tackle the styling part later, but for now, it's working.

**Link(s) to work**
1. [Coder Brixton repo (private, but it's there!)](https://github.com/coderdojobrixton/coderdojobrixton.github.io)

### Day 24: Sunday, Feb 24, 2019

**Today's Progress**: Practising APIs

**Thoughts**: Started a new job this week (yay me). The work is very API focused so I decided to start learning Postman as I think it's going to be a pretty useful tool for me moving forward.

### Day 25: Monday, Feb 25, 2019

**Today's Progress**: More practising APIs

**Thoughts**: Covering for someone else at work this week so have to stick with the API work for the next few days. Not a bad thing though!
