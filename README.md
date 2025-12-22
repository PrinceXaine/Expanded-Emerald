# Expanded-Emerald
A ROM hack designed with vanilla Emerald in mind.

# What isn't Expanded Emerald?
  1. This ROM does not add new generational content, such as: Pokémon, abilities, moves, held items, etc.
  2. This ROM does not include the physical/special split.
  3. Besides the intro, this game does not change the vanilla story.

# What **is** Expanded Emerald?
  1. Expanded Emerald is a decomp ROM hack designed to revamp the original game without changing the core experience.
  2. Expanded Emerald contains many difficulty/nuzlocke knobs and several expansions to existing content to flesh out the game further.
  3. Expanded Emerald offers a chance for the player to obtain any of the original 386 Pokémon in the cartridge, without trading.
  4. Expanded Emerald also allows most of these Pokémon to be transferred LEGALLY to future generations.
  

# EXPANSIONS
  1. **Safari Zone Start**: Player catches their first Pokémon from the Safari Zone instead of getting it as a gift.
  2. **Prof. Birch Research:** Each day, Prof. Birch's assistant requests a new Pokémon to be submitted. Rewards scale with Pokémon requested.
  3. **Capt. Stern's Expeditions (POST-Game):** Fund expeditions to locate the event islands tied to Legendary Pokémon.
  4. **Legendary Rumors:** Each day, a Legendary is rumored to appear in specific locations.
  5. **Expanded Outbreaks (GYM 5):** Outbreaks are fixed to occur more than once. Additionally, has a chance to make 1% encounters on routes appear in the outbreak.
  6. **Natural Evolution:** All wild Pokémon have a chance to be replaced with their evolved counter-part. Even smaller chance for a stage 2 Pokémon instead.
  7. **Rydel:** Utilizes the existing bike time trial on the seaside bicycle path for a chance of PROTO-BIKE.
  8. **Fishing:** Reduces chance of 'nothing' and offers a chance of finding items.
  9. **Rock Smash:** Reduces chance of 'nothing' and offers a chance of finding items.
  10. **Universal Rematches:** All trainers can be rematched at any time. PokéNAV trainer teams advance when they are ready for a rematch via the Match Call system.
  11. **Shiny Symbols:** Each Battle Frontier Gold Symbol increases shiny odds. This stacks until 1/1024 (from 1/8192).
  12. **Pickup:** Expanded Pickup to also include a friendship table, which is rarely called instead of the RNG tables.
  13. **Wonder Corner** Removed TM prizes from Game Corner and instead placed 5 Wonder Pokémon that reset each day with dynamic prices determined by final stage base stats. Can contain any basic pokémon in-game.
  14. **Wonder Egg** Located at the daycare, the Wonder Egg vendor sells the player an egg for 10,000 each day. This egg is guaranteed to have 15 IVs in each stat at minimum. Can contain any basic pokémon in-game.
  15. **Wonder Traders** Located in several locations around Hoenn, several unique "trainers" with differing personalities will trade you Pokémon that are thematic. These are guaranteed to have at LEAST the IVs of the traded Pokémon and will also share the nature.

# QOL
  Note: These are "always ON" mechanics, not toggles available in the OPTIONS section of this document.
  1. **Bag Sorting**: Press START while in the main items pocket to sort by: NAME, TYPE, VALUE.
  2. **PC Sorting**: Press A while on the BOX NAME to sort by: DEX NO., NAME, TYPE, LEVEL, BASE STATS.
  3. **Registered Items**: Can register up to 4 items. SELECT for item 1, START for item 2, "L" for item 3, "R" for item 4.
  4. **Run at Start + Run Indoors:** Run from the moment you start the game and run indoors.
  5. **Catch EXP:** Gain EXP when catching Pokémon too.
  6. **Text Adjustments:** Removes a lot of extra text from actions such as accessing the PC, Healing, Saving, Berry Picking and more.
  7. **BW Repel System:** Allows the user to use another repel when the the active repel runs out.
  8. **Pokémon Summary Screen:** EV Display = START, IV Display = SELECT, Red Stat = Nature increased, Blue Stat = Nature decreased.
  9. **Reusable TMs:** TMs can be used any number of times.
  10. **Erasable HMs:** HMs can be erased without a move deleter.
  11. **Use HMs without Learning:** Allows Pokémon to use HM in overworld if the Pokémon can learn the HM, instead of requiring the Pokémon to know the HM.
  12. **Premier Balls Fixed:** Receive a Premier Ball for each stack of 10 Pokéballs bought.

# BALANCE
  1. **Ability - Traunt:** Allows Pokémon with Traunt to use Slack Off on Traunt turns.
  2. **Ability - Sturdy:** Allows Pokémon with Sturdy to survive any hit from Max HP.
  3. **Ability - Synchronize:** Guarantees wild Pokémon with matching Natures.
  4. **Move - Slack Off:** Reduced to 5 PP, 25% HP recovery.
  5. **Learning Move PP:** New moves retain current PP from previous move, or clamps current PP to new move's max PP, whichever is lower.
  6. **Premier Balls:** Adjusted to catch at 1.25x the normal rate instead of 1x.


# Settings - Difficulty
  1. Battle Style: _Set_ prevents the player from switching when an opponent's Pokemon fiants. _Switch_ allows the player to switch when an opponent's Pokemon faints.
  2. Level Cap: _On_ prevents the player from leveling past the gym trainers of each gym & the E4. 8, 15, 22, 29, 36, 43, 50, 57, 70, 100
  3. Wild EVs: _Off_ prevents the player from gaining effort values from all wild encounters.
  4. Unevolved EVs: _Off_ prevents the player from gaining effort values from basic Pokemon with a stage 1 or higher evolution.
  5. Rematch Lock: _On_ prevents the player from spamming trainers with rematches.
  6. Economy: _'value: x'_ increases the buy price of items and decreases the sell price of items by the same amount.
  7. Daycare Price: _'value: x'_ increases the cost of buying a Pokémon back from the daycare by the same amount.
  8. Trainer Items: _XItems_ disables the opponent's use of heal items but allows battle items. _Off_ disables all opponent items in battle. This does not affect hold items.
  9. EXP/Catch Scaling: Pokémon IVs and Base Stats affect EXP and catch rate. Level difference between player and opponent Pokémon affects EXP earned.
  10. Poison Survival: _Off_ allows Pokémon to faint from poison in the overworld. _On_ prevents the Pokémon from fainting but leaves the status on the Pokémon. _On+Heal_ prevents the Pokémon from fainting and removes the status when at 1 HP.
  11. Enhanced Wild AI: _On_ allows wild Pokémon to make intelligent decisions instead of random.
  12. Trainer EVs: _Off_ use vanilla values. _Scale_ increases EVs depending on badge count. _Half_ places trainers at 128 EVs. _Full_ places trainers at 252 EVs.
  13. Trainer IVs: _Off_ use vanilla values. _Scale_ increases IVs depending on badge count. _Half_ places trainers at 15 IVs. _Full_ places trainers at 31 IVs.
  14. Trainer IV/EV: For Trainer EVs and Trainer IVs settings, _Challenge_ edits only leaders, rivals, admins, etc. _All_ edits all trainers in-game.
  15. Gym Lock: _On_, prevents the player from leaving a gym once entered.
  16. Gym Trainers: _On_ all trainers must be defeated before challenging the leader. _Endurance_ All trainers must be defeated consecutively, without leaving the gym.
  17. No Heal Gym/E4: _On_ Player cannot use overworld healing items in gyms or E4.

# Settings - Nuzlocke
  1. Options Restriction: _Home_ prevents the player from accessing Difficulty/Nuzlocke settings unless they are home.
  2. Save Restrictions: _Centers_ prevents the player from saving anywhere but at a Pokémon Center.
  3. Item Ban: _XItems_ allows the player to use only battle items, but not healing items in trainer matches. _On_ prevents all player usage of items in trainer battles.
  4. Permadeath: _Protect_ allows the player to retry if party gets wiped. _On_ deletes the save when wiped. In both, Pokémon are erased when less than party count after battles.
  5. 1st Encounter: _On_ is a capture rule. Can only catch the first encounter on each location. If missed, fainted, fleeing, etc, no more chances in that location.
  6. Species Clause: _On_ works in partnership with 1st encounter. A failsafe to prevent a captured species (or its evolution line) from counting as the 1st encounter.
  7. No EV Gain: _On_ Overwrites other player EV settings. No EVs are gained, at all.
  8. Disable Switch: _Once_ allows the player to swtitch out their Pokémon once per battle. _On_ disallows all switching by the player. Does not affect moves/abilities.
  9. Roster Order: _On_ prevents the player from choosing a replacement Pokémon from their party when one faints. Instead, the next in line is automatically sent out.
  10. Disable Running: _On_ prevents the player from using the run command to escape from battles. Abilities, moves and items are unaffected. _All_ prevents any escaping whatsoever.
  11. Opp Battle Style: _On_ allows the opponent to switch in a replacement Pokémon when fainting a player's Pokémon.
