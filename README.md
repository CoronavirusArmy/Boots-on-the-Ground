# Boots-on-the-Ground

## PROBLEM
We love Helpboards/FacebookGroups/invisibleshandsdeliver.com, but we anticipate a huge scaling problem. In 2 weeks, the number of need requests is going to increase by 100 to 1000X. We believe most matching systems will grind to a halt.

#### Want a pretty use case:
go here
https://docs.google.com/document/d/1S5gBb9bhvUBl6A48BGt_E1CYXtvXI8J8TrOw9u-tSIQ/edit

#### Want a tech problem definition with variables and algorithms use case:
go here
https://docs.google.com/document/d/1KDrYs5sh1cv2Vuaxl3hnzMtLEIW97as1dl65wCSX_-8/edit#heading=h.1evn3bmx9vt9

#### Convinced and have tech skills
Fill this out.
https://docs.google.com/spreadsheets/d/1AZ3U3cR3w4SLJeSaqg7lSz74RQ8JETRlWFaXlju3DiE/edit#gid=0


## SOLUTION
We don't want to make a new app.  We want simple matching services. 

An API and a simple front end (and allowing others to use the frontend). 
Once people are matched, they are taken off the board of looking for matches. This deals with reposting and "database-like race condition issues".
Another thing: Match each 1 PersonWithNeeds with 3Caretakers. 3 caretakers is more redundant and hasself-policing aspects.

 We hope (stretch goal) to get text integration so people cansignup via text. This vastly lowers the barrier (tech and expense) touse it.

## HOWTO GET STARTED WITH US

The best way to get started is to go here (Discord https://discord.gg/vuNVr8H) and look at the #boots channels. 

Sorry... We are changing every 12 hours, so hard to keep the documentation up.

3 divisions
1) Logistics / Field Operations (non-tech: answer phones, help people sign up, deal with complaints)
2) Research / Outreach (non-tech: how to get volunteers, what the service should do, etc)
3) Tech/Programming/Infrastructure (non-tech: building a bulletproof API that scales to 100,000 to 1,000,000 users per day, and avoids the communication-match breakdown when people try to post to 1000's of facebook groups 1000s of posts per day.
)

* Tech Team is about 8. Non Tech team about 8-15.
* Juniors
* Midlevel front end (angular, or bootstrap, or whatever/agnostic; some flutter and React; we don't care, we just want fast)
* Backend (this we do slowly, since we're focusing on the scaling issue)
  * ("babyAPI" with no security to get the front end mocked up), and
  * bulletproof API with google realtime Database for 100,000-10,000,000 users.
  
## Authored by Howard Chong, Technical Coordinator, Boots on the Ground 3/21
Contact us:
I'm "hocho" on the discord server. (Discord https://discord.gg/vuNVr8H). *** highly preferred, checked almost hourly.
chongare@gmail.com *** slow, checked 2x a day usually.
Or you can text me at this number (24/7, not checked when sleeping) 3 × 3 × 13 × 19 × 19 × 143779. (that's my cell number)

Or contact Jenny (@ChinpokomonGo#8548 on the Discord server)

For tech, check out the `#web-app-tech` channel on the discord. Look at the pinned message and do the Daily Checkin which has instructions for new people looking into the project. Links to our repos there.

### This repo (CoronavirusArmy/Boots-on-the-Ground) is empty (zero code) and just points you to our main repo. Our main repos are here:
https://github.com/orgs/BootsOnTheGround-3Caretakers/

front end: https://github.com/BootsOnTheGround-3Caretakers/ --> front-end-angular

