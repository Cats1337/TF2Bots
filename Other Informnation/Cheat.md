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


~Last updated 7/17/2021, to add rocket launcher prediction, pipe detonate time, huntsman & loose cannon charge / timing.~

Last Update 3/24/2022, I think to add in a lazy load, so that the map props will load in slowly, before there was only a noload. Though I'm not sure...

Clearly it's constantly being updated, and since it's public that means Valve should be able to do something about it since the code is open source. Thought it's annoying when you spend so much time on a coding project, but when it's hacks, a large portion of the respect is lost. I hope all 3+ years spent on this hack are lost to one update by Valve. :)