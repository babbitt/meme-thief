# meme-thief
I really tried to make a sincere hackathon project but I got 10 hours in and hit a roadblock. So here's a meme entry I think it's quite funny.

## The Story
I originally set out to create a PWA that took data from myBinghamton and myCourses to plan out your day based on your schedule and assignments. I spent about 3 hours getting electron, react, and next.js to play nice. Just when I thought I was out of the woods I was hit with the issue of authentication. Binghamton uses a system called "CAS" to have a single sign on for all of their services. After poking around with CAS for about 2 hours I realized I would just have to spoof a real user interaction. Due to the way that cookies are stored and processed by CAS clients I was unable to process user data in electron. This then led me to create another project I dubbed "juulPODS" (because it's PODS authentication but really really bad for you and your security). It used a headless chrome browser to activate the required cookies and then handed api requests down via a web server to clients that used it (such as my original project). I got this all working, but it kinda killed the momentum of the whole project and by the time I was done with all the faff it was too late to make anything productive of the actual app. 

Sorry.

-Joe

Now go steal some memes.
