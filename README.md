# Blackjack

A command-line Blackjack game written in Go.

## Features

- Uses a shuffled three-deck shoe.
- Deals two cards to the player and dealer.
- Hides one of the dealer's cards during the player's turn.
- Lets the player choose to hit or stand.
- Automatically plays the dealer's hand according to the game's rules.
- Calculates hand scores, including the flexible value of aces.
- Announces wins, losses, draws, and busts.
- Plays ten hands in one run.

## Requirements

- Go 1.27 or newer

## Run the game

From the project directory, run the application with `go run .`.

During the player's turn, enter `h` to draw another card or `s` to stand. Results are displayed after each hand.
