---
{"dg-publish":true,"permalink":"/tiny-thinks/18-cards/flip-four/","dg-note-properties":{}}
---


A two-player game of hidden information, shifting alliances, and chaotic chain reactions.

Create a line of four flipped cards of your color before your opponent does.

---

# Components

Each player has:

- 9 cards of their color
- The same card backs
- Different card faces

Each card face has a unique effect.

At the start of the game, players cannot see the faces of any face-down cards.

---

# Objective

Win by creating a connected line of four **flipped** cards of your color.

A connected line may be:

- A row
- A column
- A corner-to-corner diagonal

If both players achieve a winning line simultaneously, the game ends in a draw.

---

# Terminology

## Color

Every card belongs to a player and has that player's color.

Normally a card contributes its owner's color to the board.

Some card effects may change this.

## Flipped Card

A card whose face has been revealed.

Flipped cards remain flipped for the rest of the game unless an effect says otherwise.

## Roaming Card

Once a player has placed all of their cards onto the board, their final card becomes a roaming card.

A roaming card is placed on top of another card.

The roaming card determines the color and effect of that space.

## Space

One position in the 4×4 grid.

A space may contain:

- One card
- One card with a roaming card on top

A space can never contain more than two cards.

## Adjacent

Adjacent spaces include all neighboring spaces:

- Horizontally
- Vertically
- Diagonally

A space therefore has between 3 and 8 adjacent spaces.

---

# Setup

Create a 4×4 grid.

Players take turns placing face-down cards into empty spaces until all 16 spaces are filled.

Each player should have exactly one card remaining. This card is kept in hand and will later become that player's roaming card.

Choose a starting player.

### Fast Setup Variant

Each player sets aside one card.

Shuffle the remaining 16 cards together and deal them randomly into a 4×4 grid face down.

Each player keeps their remaining card as their roaming card.

---

# Turn Sequence

On your turn, perform exactly one action.

## Place a Card

If there is an empty space on the board, place a face-down card into that space.

## Create Your Roaming Card

If there are no empty spaces and you still have a card in hand, place that card on top of any space that does not already contain a roaming card.

This card is now your roaming card.

## Move Your Roaming Card

If you have no cards remaining in hand, move your roaming card to any space that does not already contain a roaming card.

When the roaming card leaves a space, the card underneath immediately becomes active again.

---

# Connected Lines

A connected line is a row, column, or diagonal where all four spaces currently belong to the same color.

A line is considered **newly connected** if:

- It is connected now, and
- It was not connected immediately before the most recent board change

Board changes include:

- Placing a card
- Creating a roaming card
- Moving a roaming card
- Resolving a card effect

A line that remains connected does not trigger additional flips.

To trigger another flip, the line must first become disconnected and later become connected again.

---

# Triggering Flips

After every board change, check for newly connected lines.

Follow these steps:

1. Check whether the active player has any newly connected lines.
2. If they do, choose one of those lines.
3. Trigger a flip.
4. Resolve the flip and all resulting effects.
5. Check the board again.

If the active player has no newly connected lines, repeat the process for the other player.

Continue until neither player has a newly connected line.

---

# Resolving a Flip

When a flip is triggered:

1. The owner of the triggering line chooses any unflipped card on the board.
2. Reveal that card.
3. Resolve its effect completely.
4. Check the board for newly connected lines.

If the chosen card is currently a roaming card, reveal and resolve the roaming card.

The card underneath is ignored.

---

# Winning the Game

After all flips and effects have been resolved:

- If one player has a connected line consisting entirely of flipped cards of their color, that player wins.
- If both players satisfy this condition at the same time, the game is a draw.

---

# Card Effects

## Slide Row

Choose a row.

Move every card in that row one space left or right.

Cards pushed off one edge wrap around to the opposite side.

---

## Slide Column

Choose a column.

Move every card in that column one space up or down.

Cards pushed off one edge wrap around to the opposite side.

---

## Swap Adjacent

Choose two adjacent spaces.

Swap their contents.

If one space contains a roaming card, move the entire stack.

---

## Move This Card

Move this card to an adjacent space.

If the destination contains a roaming card, swap positions with that entire stack.

---

## Scout

Look at one adjacent face-down card.

Return it face down.

---

## Wild

This card belongs to both players.

It may contribute to connected lines and winning lines for either player.

---

## Traitor

This card belongs to your opponent instead of you.

---

## Poison

This card is colorless.

It does not belong to either player.

It cannot contribute to connected lines or winning lines.

If Poison is revealed while acting as a roaming card, ignore its effect.

---

## Bomb

Turn all adjacent flipped cards face down.

Cards turned face down do not resolve their effects again.

Only their flipped state changes.

---

# Rules Clarifications

### Roaming Card Priority

A space containing a roaming card always uses the roaming card's color and effect.

The card underneath is ignored until the roaming card moves away.

### Moving Stacks

Whenever a card effect moves or swaps a space containing a roaming card, move the entire stack.

### Multiple Connected Lines

If multiple newly connected lines exist, the player resolving the flip chooses which line triggers.

After the flip is resolved, the board is checked again.

### Poison and Winning

A line containing a Poison card can never be a winning line.

### Existing Lines

A line only triggers a flip when it becomes newly connected.

Replacing one card in an already connected line with another card of the same color does not create a new flip.

The line never became disconnected.

---

# Example

A Blue roaming card sits on top of a Red card.

The space currently counts as Blue.

The Blue roaming card is moved elsewhere.

The Red card underneath immediately becomes active and the space now counts as Red.

The board is then checked for newly connected lines.