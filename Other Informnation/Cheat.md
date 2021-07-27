#### I believe all the information is the way the domain seller masks peoples information.

The name of the cheat, [cathook](https://github.com/nullworks/cathook), which I'll refer to as CH.

CH is the cheat that the botters seem to be using, more about this next.
MH is a derivative of CH.

If you google them you'll find websites for them which are below:

cathook.club, contains a link to the github, and to a steam account generator, which is against TOS :), I'm also not checking because you have to download an extension for it to work, which breaks TOS, so fun report time on that one. :)

meowhook.club is a troll site, possibly a phishing site, so don't go there, obviously, you click a button to 'download' the hack, and it just trolls you lol.

Looking up who registered either of the domains we get the following information, of the registrars address and phone number... But it's all fake, the phone number is clearly just someone smacking "12345" on their keyboard. "3544212434"
The domain was bought from "http://namecheap.com" and was $10-12 / year, and was bought on "2021-04-03T00:07:30.22Z" aka, April, 3rd, 7:30.22 UTC
Also, the address is a strip mall of various stores, and a phallic object museum. Sounds about right.

### Source code breakdown

In the src/hacks/aimbot file, there are 1650 lines of scummy code, here's a break down of it.

 Line # | What is does
----- | -----
138 | Keep enemy in range
185 | Backtrack
206 | Hitman's heatmaker
350 | Auto shoot
356 | Huntsman
377 | Loose cannon
404 | Pipe bombs ( grenade launcher)
442 | Burst fire minigun at range, else normal shoot
463 | Just tells it to be a pyro main, and m1 if rapidfiring
514 | Holding Building, deadringer, taunting, cloaked
534 | Hitscan weapon or melee
711 | Checks if player is themselves, dead, teammate, too far away
747 | Check if rage mode is on lmao
773 | Darwin 15% protection
777 | Vaccinator damage
779 | Check if bullet resistant from vaccinator ^
784 | Invis spy 10% protection
795 | >450 health, sniper has to be full charge
807 | Check if ubered, or bonk
804 | Invis spy
833 | Hitbox predictions
860 | Spy won't attack friendly builds even if FF is on
917 | NPC check, won't shoot npc
948 | Stickies check, only hitscan can break them, even checks if sticky is moving.

Another thing I noticed while looking through the code is that the bots will actually not grab health packs while being healed. Meaning they're more civil than scout mains.

After line 1353 the rest is source game checks, CSS, TF, HL2DM, and some other one I think. 
Headshots for CSS
TF copies TF2

Some GUI elements, visuals, etc.


All this does have a GNU, General Public Use License. Which in short, is a license that guarantees the end user, the person(s) using the program, the freedom to run, study, share, and modify the code. As long as they reference the original source code and don't make monetary gains.


Last updated 7/17/2021, to add rocket launcher prediction, pipe detonate time, huntsman & loose cannon charge / timing.


Clearly it's constantly being updated, and since it's public that means Valve should be able to do something about it since the code is open source. Thought it's annoying when you spend so much time on a coding project, but when it's hacks, a large portion of the respect is lost. I hope all 3+ years spent on this hack are lost to one update by Valve. :)

[This article](https://www.vice.com/en/article/n7w87d/meet-the-guy-fixing-team-fortress-2s-bot-problemwith-more-bots) by Vice about Milenko who was the lad who was trying to counter the bots, with bots that targeted bots. Two of the developers who work on CH said they don't plan on changing the code in order to sabotage the anti-bot bots, meaning they're clearly on the cheating side there's other neat little tidbits in the article. 

Valve probably doesn't do what we'd think they do and just go to the github, and write a counter for the code because as mentioned in the article about how the identification works, it's just a game of cat and mouse, Valve updates something, CH updates, Valve updates, etc. and it's an endless loop of back and forth until one of them gives up.

[Milenko](https://milenko.ml), the anti-bot lad, has a website where he talks about hoe he does the anti-bot stuff. TF2DB, TF2 Bot Detector, only temporarily adds them to a list for the user, but doesn't detect all bots, that's where "GLaDOS" which is explained more in depth on their website, but simply bots names are collected, and then 'GLaDOS' scans servers for similar names, and adds them to the list. 
Another cool thing about this 'GLaDOS' database is that it's bot public, and there are [live statistics](https://milenko.ml/livestats.html)! I let the statistics page run for abnout 60 minutes, an hour, to see what TF2 consists of, and it's surprising. 

![9](https://user-images.githubusercontent.com/42129397/127078777-415fb6f8-877f-4253-8bdf-7d705af30792.png)

https://milenko.ml/livestats.html @ 7-8 PM GMT -5 on 20 July 2021

### How the Graph is set-up:
* Numbers on the left are total players
* Bottom is time
* Right side has number of bots, and the percentage (which you can ignore as it confuses a little)

### The Datapoints:
* Grey is total players, including bots
* Green is total human players. Which is around 7.7k ~ 7.5k, until a crash occurred, then the data is sort of skewed. 
* Orange is number of bots
* Yellow is it's own stat, being the percent of bots to humans, which is typically 3.5% ~ 4.0%


For about every 28 players, there's one bot.
