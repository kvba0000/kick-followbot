# Kick FollowBot
#### What is this?  
It's a small user-script for [Kick](https://kick.com) that allows you to automate following your channel using bots, I am calling it semi-automatic because you still need to solve captcha yourself. Althrough rest of the process is automatic, even email verifying (because funnily enough you don't have to verify yourself using email to do actions on the website)  
#### How does it work?  
It simply generates random data in fly (username, email etc.), registers account, [if it's required it prompts you to solve captcha] and then on verify screen it does it's magic of following without verifying, after all of that you're being logged out and bot is starting from beginning.  
#### How to set it up?  
1. Download [Tampermonkey](https://www.tampermonkey.net/) or [Greasemonkey](https://www.greasespot.net/) (NOT TESTED BUT IT SHOULD WORK)  
2. Download script and edit it's values (especially - "followTo" which is ID of a channel you want to follow)  
3. Install script  
4. Open [register page](https://kick.com/auth/signup) and look at the results!  
#### Small notes  
- As it is user-script that does not automatically solve captchas it might be slow, if you want to speed this up you can play with some values in script like delay between setting up all fields or just use multiple tabs if you don't care about captcha  
- <b>❗❗ SCRIPT IS USING INTERNAL KICK'S API WHICH MIGHT BE CHANGED ANYTIME, THIS MIGHT RESULT IN SCRIPT BEING BROKEN ANYTIME IN FUTURE</b>
