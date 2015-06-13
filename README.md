pokemon_zero.py
A text-based Pokemon game.

In this game, the player will travel from Pallet Town to Viridian City.
Along the way, he or she will encounter 3 different pokemon.
These pokemon will be randomly drawn from an imported list.

In battle, the player will have 3 options:
Throw a rock, damaging the Pokemon and making it easier to catch.
Throw a pokeball, possibly catching the Pokemon.
Run away, going to the next scene.

Each battle will have 4 different possible outcomes:
The player will catch the Pokemon.
The player will k/o the Pokemon.
The player will run away from the battle.
The Pokemon will k/o the player.

The player will start with 50 hp.
Pokemon attacks will do 3-5 damage per move.
Pokemon will have 20-30 hp.
Rocks will do 5-10 damage.

Depending on the Pokemon's health, the odds of catching it will be:
 hp >= 66%       = 10% chance to catch
 66% > hp >= 33% = 50% chance to catch
 hp < 33%        = 90% chance to catch

There will be a number of scripts for each outcome.
Again, these scripts will be randomly drawn from an imported list.
The beginning and ending scene scripts will not be random.
However, they will vary depending on the number of Pokemon caught / killed.

Planned features:
-All Kanto cities, leading to more Pokemon encounters.
	-Possibly a unique region. Or maybe just Skryim :D
-In-game map.
-An in-game working Pokedex.
-Add a pretty box around Pokemon and player's hp in battles.
	-This means players will be limited in their name length.
-The ability to travel freely around the region.
-Each route will be unique (no more random scripts).
-Player will be healed at each new city.
-Player can level up by capturing Pokemon.
-Rare Pokemon will be predetermined events.
-Pokemon will only appear on certain Routes.
-Pokemon will have independent HP and damage-dealing ranges.
	-Movesets?
-Player will be able to save progress.
-Player will receive money for defeating Pokemon.
-Money will go towards Pokeballs and potions.

Basically, this will eventually be a full-on Pokemon game.
Just without, you know, graphics. Or Pokemon battles.


# Planned 1.1 features:
# New locations:
#	Route 2 / Viridian Forest
#	Pewter City
# Ability to travel back and forth between current cities
# New sub-list for Rare Pokemon
# Player name limit, pretty battle box
