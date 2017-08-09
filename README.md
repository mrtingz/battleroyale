# Change Log for Gaben's Unknown Battlegrounds

#### August 9th, 2017

###### Additions
- Now able to toggle the minimap using the 'M' key.

###### Modifications
- Changed how the safe zone looks to make it look nicer (thank you @Leafdroid).

---

#### August 8th, 2017

###### Fixes
- Fixed bug where safe zone did not appear properly from the outside.
- Fixed extra safe zone being shown in sky box.

---

#### August 6th, 2017

###### Fixes
- Fixed leaderboard not changing user nickname on win.
- Fixed party members unable to hurt eachother.
- Made crate drops not suck as much.
- Fixed prone not displaying properly for clients.
- Fixed client not coming back alive while waiting for round to start (again).
- Changed location of country in scoreboard to make it look cleaner.
- Fixed being unable to hurt player when inside a vehicle.

###### Additions
- Scoreboard now shows which country the player is from.
- Added chat tags for various ranks.
- Added party system. Set maximum party size to 2.
- Added more loot spawning spots near castle.
- Added unstuck command for clients to get themselves free.

###### Modifications
- Reset Pointshop2 database due to corruption from hardware move. Set starting points to 2000 temporarily for compensation.
- Removed ammo counter that was hidden behind minimap.
- Water will now damage you if you are at least partially submerged.
- Removed Pointshop2 until I can figure out why it keeps killing itself on server start.
- Organized server round speech into "phrases" for multi-language support.

---

#### August 5th, 2017

###### Fixes
- Fixed not being able to talk with other dead people while round is running.
- Fixed chat sometimes not being displayed by dead people to other dead people.
- Fixed "safe zone is shrinking" message after round ending.
- Fixed round starting with only 1 person if second person leaves.

###### Additions
- Added command to force start the round (mostly for testing).
- Added prone mode.
- Minimap shows amount of seconds until safe zone shrinks.
- Added 2 more zones for the safe zones to spawn at.

###### Modifications
- Winning points are now rewarded based on how many people participated in the round.
- HUD now shows how many players are left alive even when dead.

---

#### August 4th, 2017

###### Additions
- Points are rewarded for winning a match.
- Spawns will now not be completely random for loot. Guns will spawn with their specific ammo type and a random attathcment.
- Added more loot spawns in dry areas.

###### Fixes
- Fixed issue with the safe zone not shrinking.
- Fixed loot not spawning properly at all locations.
- Fixed spectator mode not moving from one player.
- Fixed dead people being able to interact with alive players.

###### Mofidications
- Changed shrink time from 90 to 60 seconds.
