# Black Ops 6 Zombies - Terminus Calculator
 
A tiny Python script that solves the combination lock puzzle on the **Terminus** map in *Call of Duty: Black Ops 6 Zombies* — instantly, and for free.
 
## Why this exists
 
The Terminus combination puzzle normally means either:
1. Doing the math yourself under pressure while hordes close in, or
2. Paying Dr. William Peck an outrageous amount of essence to crack it for you.
This script picks option 3: do the math for you, in about half a second, so you can keep your essence for things that actually matter (like staying alive).
 
## How it works
 
You provide three numbers — `x`, `y`, `z` — and the script runs them through the puzzle's underlying equations:
 
```
eq1 = 2x + 11
eq2 = (2z + y) - 5
eq3 = (y + z) - x
```
 
Each result is reduced to its last two digits and concatenated together to produce the final combination code.
 
## Usage
 
Requires Python 3.
 
```
python3 xyz
```
 
You'll be prompted for `x`, `y`, and `z`. Enter them, hit enter, and the combination prints out immediately.
 
**Example:**
```
x: 12
y: 8
z: 15
 
351138
```
 
## Disclaimer
 
Not affiliated with Activision, Treyarch, or Dr. Peck. Use at your own risk — he may still find a way to charge you for something.
