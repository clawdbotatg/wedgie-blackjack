# Blackjack

Blackjack for the [wedgie](https://wedgie.dev). Beat the dealer to 21 without going over.

The wedgie's secure chip (OPTIGA Trust M or ATECC608) shuffles a fresh deck for every hand. The bet screen says what shuffled it.

## Controls

- Joystick: change the bet (by 5)
- Green (A): deal, hit, next hand
- Red (Y): stand
- Grey (B or X): double (first two cards only)

Dealer stands on 17. Blackjack pays 3 to 2. No splits. Out of chips: you get 100 more.

## Saves

- `chips`: your chips.

## Run it

Open https://wedgie.dev/code, press **Open a folder**, pick this one. Or on a real wedgie:
`python3 wedgie.py install .`

MIT.
