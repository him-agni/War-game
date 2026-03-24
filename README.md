# War Card Game

A simple browser-based card game built with vanilla JavaScript where you compete against the computer in a game of War.

## Description

This is a digital implementation of the classic card game "War" where players draw cards and compare their values. The player with the higher card wins the round and earns a point. The game continues until all cards in the deck are drawn, and the player with the most points wins.

## Features

**New Deck**: Shuffle a fresh deck of cards to start a new game
**Draw Cards**: Draw two cards (one for you, one for the computer) and compare values
**Score Tracking**: Real-time score updates for both players
**Remaining Cards Counter**: See how many cards are left in the deck
**End Game Detection**: Automatically determines the winner when all cards are drawn
**War Ties**: Handles tie situations when both cards have equal value

## Technologies Used

**HTML** - Structure
**CSS** - Styling (not included in snippet)
**JavaScript** - Game logic and interactivity
**Deck of Cards API** - Card data and images from `apis.scrimba.com`

## How to Play

1. Click **"New Deck"** to shuffle a fresh deck of 52 cards
2. Click **"Draw Cards"** to draw two cards - one for you and one for the computer
3. The card with the higher value wins the round:
   - Ace is highest
   - King, Queen, Jack follow in descending order
   - Number cards rank by their face value
4. Points are awarded to the round winner
5. Continue drawing until all 52 cards are used
6. The player with the most points at the end wins the game!

## Game Logic

The game uses the Deck of Cards API to:
- Create and shuffle a new deck
- Draw cards from the deck
- Display card images


## API Reference

**New Deck**: https://deckofcardsapi.com/api/deck/new/shuffle/?deck_count=1
**Draw Cards**: https://deckofcardsapi.com/api/deck/<<deck_id>>/draw/?count=2



Built as part of the Scrimba JavaScript course.
