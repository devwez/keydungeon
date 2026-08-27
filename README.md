# KeyDungeon

a keyboard-only roguelike dungeon crawler. no mouse. no tab key. just you and the arrow keys.

built for [Tabbed](https://tabbed.hackclub.com/) — a YSWS where everything has to be navigated with keyboard only.

## how to play

- arrow keys or WASD to move
- walk into enemies to attack them
- kill everything on a floor then find the 🚪 to go deeper
- 5 floors, gets harder as you go down
- you have 60 HP so dont be reckless

## enemies

| emoji | name | what it does |
|-------|------|-------------|
| 🦠 | slime | wanders around randomly, weak but annoying in groups |
| 🦇 | bat | moves every turn, fast and unpredictable |
| 💀 | skeleton | chases you if it sees you, hits hard |

## controls

- WASD / arrow keys — move
- ENTER — start game / restart
- that's it. literally everything is keyboard

## tech

- single HTML file, no frameworks no dependencies
- canvas rendering
- BSP-ish dungeon generation (random rooms + corridors)
- turn-based — you move, then enemies move
- fog of war — only see whats near you

## running it

just open `index.html` in a browser. thats it.

## made by

bart / devwez — took about 12 hours across 5 days

## ai disclosure

used codebuff to help structure this readme and explain some of the tech. all game code was written by me.
