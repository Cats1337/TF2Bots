### The Update / Patch Notes can be found here: https://www.teamfortress.com/?tab=updates


* Numerous security and stability improvements
  * Not sure exactly what they are, but they seem important.
* Added a cooldown before a player can create a vote when they join a match already in-progress
  * Helpful for preventing the bots from kicking players, since they're usually kicked faster than the cooldown timer, which is 5 minutes.
* sv_vote_late_join_time controls the grace period after the match starts before the cooldown is applied: default 90 secs
  * Allows people to kick bots at the start of a game? Not sure exactly, but that's what it seems like.
* sv_vote_late_join_cooldown controls the length of the cooldown: default 5 min
  * Kick votes will end early and automatically pass if the vote target leaves the match during the vote
  * Mentioned above, but the auto pass if they leave is good because now if a vote on a bot is started it'll go through, before they could leave to avoid punishment.
* Added a ConVar to control players changing their name during a match
  * tf_allow_player_name_change: default is 1
  * Matchmaking servers will set this to 0
  * Now bots won't be able to join with a fake name, and then change it in game to confuse people!
* Updated the player list in the vote-kick dialog to show the time each player has been connected to the server
  * This kind of makes my how to kick the bots part of the guide moot, but hey it still works, just now the game does it for you.
