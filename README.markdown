# A History of Preascendant Humanity

A game for two to four players, plays in about an hour.

    And on the pedestal these words appear:
    'My name is Ozymandias, king of kings:
    Look on my works, ye Mighty, and despair!'
    Nothing beside remains. Round the decay
    Of that colossal wreck, boundless and bare
    The lone and level sands stretch far away.
    -- Percy Bysshe Shelley. Ozymandias.

----

## Overview
You are immortal puppet-masters, managing a coalition of factions to ensure
they control the galaxy through exploration, expansion, exploitation, and
extermination of rival factions.  Not even the most powerful faction survives
forever, and the loyalty of currently-weak factions is cheap.  You must take
the long view.

## Objective
Have the most influence at the end of the game.

Colors are worth influence equal to the value of all sectors they control.
Each card is worth influence equal to its color.

## Components
- This rulebook.
- A deck of event cards.
- A collection of influence tokens.
- 24 control disks, six in each of four colors.
- 20 hexagonal sector tiles.

## Setup
- Shuffle the event deck.
- Draw four cards to make the *market*.
- Deal each player three cards and nine influence.
  - Players may discard any number of cards and redraw once, as a mulligan.
- Decide which player is closest to immortality.  That player starts.

TODO(#3): A diagram of play.

## Play
Play proceeds in turns.  At the beginning of your turn, if you have no cards
left, recover your discard pile.  Take one of the following actions:

- Auction a market card or any active card.
- Reap a card from your hand for influence.
- Play a card for expansion.
- Play a card for its event.

If there are no disks left in the pool at the end of your turn, *the game
ends.*

### Auction
Put a card up for auction, either from the market ("seeding") or another
player's active card ("salting"). Place it in front of you during this process.
Everyone secretly bids influence and simultaneously reveals their bids.

The high bidder takes the card and:

- If from the market: pay the active player (if the active player would pay
  themselves, they pay the bank instead).
- If from a player: pays the former owner (if the card's owner would pay
  themselves, they pay the active player instead).

Caveats:

- The active player breaks all ties.
- If nobody bids anything, the card is put on the bottom of the event deck.

### Reap
Sell a card for influence; place it in front of you during this process.

1. Determine the value of its color by counting up sector values.
2. Collect that much influence from the bank.
3. Bid for preservation of that color.
4. Place the reaped card on the bottom of the market deck.

#### Preservation and Collapse

1. Everyone secretly bids influence and simultaneously reveals their bids.
2. Counter-clockwise from the active player, each bidder chooses which sectors
   to save.  Players can choose one sector for each influence they bid.
3. In sectors not saved, destroy the top disk.

### Expand
Play a card to place a disk.

1. Put the card on your discard pile.  It's now active.
2. Take a disk of its color and place it on the map adjacent to another sector
   controlled by its color.  If no such sectors exist, place the disk in any
   unoccupied sector.
   - If you placed in an unexplored sector, draw a new sector to put there.
3. Collect influence equal to the sector's value.
4. If you drew a new sector, reveal and execute the top card of the event deck.
   (Leave it on top afterwards.)

### Event
Play a card to execute its event.

1. Put the card on your discard pile.  It's now active.
2. Follow its instructions.