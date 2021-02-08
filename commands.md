# Runebot Commands

## __**How-to Runebot**__:

@Rune#8621 is a RuneInfo replacement, hopefully with less downtime. All relevant @RuneInfo#5879 commands can be invoked the same way, using `.` instead of `!`.

e.g, `.stats <RSN>`, `.gains <RSN>`, `.vstats <RSN>` etc.

## __Additionally__:
* `.stalk <RSN>` generates a mobile-friendly list of skills, xp, and rank.
* `.99s <RSN>` generates a list of skills you have that are not yet 99, and how much XP you have until they are.
* `.120s <RSN>` does the same for skills under 120,
* `.200m <RSN>` does the same for skills under the 200m exp cap.

To run these commands without putting in your `RSN` every time, you will need to `.setrsn <YOUR RSN>`. To change your `RSN`, set it again, or remove it with `.removersn`.

## __**Additional Commands**__:

## __**Clue Scrolls**__:
For those of us who work on a *nix machine and thus cannot access Alt-1, the following clue commands are provided.

* `.clue anagram <query>` returns the anagram answer for the clue `query`. `query` can be any part of the anagram, Runebot will return the closest fuzzy match to your `query`.
* `.clue cryptics <query>` does the same for cryptics,
* `.clue riddles <query>` does the same for riddles,
* `.clue coordinates <degrees north or south>` gives you a map of the location for coordinate clues. You can put any of the four coordinate values in `degrees`, if there are multiple possible locations Runebot will show them all individually.
* `.clue score <RSN>` gets you your clue scrolls score and ranking

## __**Archaeology**__:
`.artifact <artifact-name>` gives you the closest archaeology artifact, the level required to restore it, the amount of XP you get, the collections the artifact belongs in, and the materials and values required to restore it. The GE price of the materials are updated once a day.

* `.materials` will give you an interactable embed of materials by their faction and prices.
* `.materials <material-name>` gives you the current price of the material and the locations of material caches where the material can be obtained.
* `.collection <collection-name>` gives you information about the collection. Search without spaces and with roman numerals instead of numbers if you don't get the result you want.

## __**Invention**__:
* `.perks` gives you a list of perks we currently track
* `.perks <perk name>` gives you some details about what the perk does, as well as recipes and probabilities of obtaining the perk.
