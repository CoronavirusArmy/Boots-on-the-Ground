# Boots-on-the-Ground

## PROBLEM
We love Helpboards/FacebookGroups/invisibleshandsdeliver.com, but we anticipate a huge scaling problem. In 2 weeks, the number of need requests is going to increase by 100 to 1000X. We believe most matching systems will grind to a halt.

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
* Midlevel front end (angular, or bootstrap, or whatever/agnostic)
* Backend 
  * ("babyAPI" with no security to get the front end mocked up), and
  * bulletproof API with google realtime Database for 100,000-10,000,000 users.
