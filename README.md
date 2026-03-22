# 🂡 Blackjack Game 

## Overview 

A command-line Blackjack simulator written in Python that models core game mechanics including card dealing, score calculation, blackjack detection, and automated dealer behavior. 

The project focuses on clean control flow, modular function design, and handling edge cases such as Ace value adjustments and win condition evaluation. 

## Features

- Randomized card dealing and deck simulation
- Dynamic score calculation with automatic Ace adjustment
- Blackjack detection logic
- Dealer drawing rules (hits until 17)
- Modular functions for game state updates and outcome comparison
- Command-line interaction loop

## Rules of the Game 
### Objective
- Beat the Dealer: Get a hand total closer to 21 than the dealer without exceeding 21.
- Bust: If your hand total exceeds 21, you lose instantly, regardless of the dealer's hand.
- Push: If you and the dealer have the same total, it is a tie (push), and you get your bet back. 

### Card Values
- Numbered Cards (2-10): Face value.
- Face Cards (J, Q, K): Worth 10 points.
- Aces: Worth 1 or 11, whichever helps the hand more. 

### The Game Setup
- Bet: Place your wager before cards are dealt.
- The Deal: Players receive two cards face up; the dealer receives one card face up and one face down (hole card).
- Blackjack: An initial Ace and any 10-value card equals a "natural" blackjack, but you can still choose to continue and the Ace will to count for 1 point. 

### Player Actions (Your Turn)
- Hit: Take another card to increase your total.
- Stand: Keep your current total and end your turn.

### *Key Tips* 
- Never take insurance (a side bet on dealer blackjack).
- Always split Aces and 8s.
- Stand on hard 17 or higher.
- Hit on 11 or lower.


