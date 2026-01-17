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
- Blackjack: An initial Ace and any 10-value card equals a "natural" blackjack, usually paying 3:2. 

### Player Actions (Your Turn)
- Hit: Take another card to increase your total.
- Stand: Keep your current total and end your turn.
- Double Down: Double your initial bet to receive exactly one more card.
- Split: If your first two cards are a pair, you can split them into two separate hands by placing a second bet.
- Surrender: Give up half your bet to fold before playing the hand (if permitted). 

### Dealer Rules
- Reveal: The dealer reveals their hidden card.
- 17 Rule: The dealer must hit on a total of 16 or less and stand on 17 or more.
- Soft 17: In some casinos, the dealer must hit on a "soft 17" (an Ace and a 6). 

### *Key Tips* 
- Never take insurance (a side bet on dealer blackjack).
- Always split Aces and 8s.
- Stand on hard 17 or higher.
- Hit on 11 or lower.


