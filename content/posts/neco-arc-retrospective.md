+++
title = 'My first Fedi Bot'
date = 2023-11-30T00:47:15-06:00
tags = ['fedi', 'bot', 'neco arc']
+++
A short retrospective on a bot that I made on a whim, only 3 days after joining fedi no less


So yeah, I made a fedi bot that just posted random Neco Arc pictures.
But why though?
that's a great question. when I joined fedi, I was still a regular user of twitter, and I enjoyed [NecoBot](https://twitter.com/necoposting), an account that posted random neco arc pictures every hour.

So, on the 26th of June, 2022, the account [@necoposting@botsin.space](https://botsin.space/@necoposting) was created, only 3 days after my main account was created on mastodon.lol, on the 23rd. I'll probably make a post about my beginnings on fedi one of these days.

For the bot, I used a Python library called mastodon.py to interface with the mastodon API, which worked well enough. I cobbled together a script that sent a random post every hour. It would load a JSON file that had a manifest of all the pre-set posts (yeah I know, JSON is most likely a bad choice but whatever). Images were stored locally and would be uploaded every time, I wonder if this caused alot of server storage usage due to many duplicate images, I dont think mastodon has a drive like *key and such though so there probably wasn't an alternative. Another thing is that i loaded the bot as a systemd service on my own PC. This is mainly why it went down when it did.

As for obtaining the images, I just scrolled down the twitter bot's feed for any new images, and added them to my own. also not the most optimal choice. I also wasn't great at writing alt text, so the descriptions were sometimes suboptimal. 

The main issue that ended up happening, is that I got busy with other things and stopped adding new images, so the bot kept repeating the same posts repeatedly. this is the main reason why I didn't want to revive it after it went down, it just became repetitive. I also never caught up with the bot's replies and DMs, which there were surprisingly a decent amount. I appreciated the support, but I wasnt able to keep it going. So I guess this is the end of it. Thanks to everyone who followed and enjoyed my bot, it was pretty fun and interesting while it lasted.

also as of writing this, i discovered that the original twitter bot is now no longer active, with the last post being November 11th, and (coincidentally) my own bot going down only 3 days after, on the 14th.

Rest in Peace, you will be remembered.