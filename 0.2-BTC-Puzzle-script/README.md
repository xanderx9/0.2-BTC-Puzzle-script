# 0.2-BTC-Puzzle-script
A Python script to help solve the 0.2 BTC Puzzle by testing custom identified seed words against a target address


## Purpose

This repository contains a Python script specifically designed to help users solve the 0.2-BTC-Puzzle (https://privatekeys.pw/puzzles/0.2-btc-puzzle) by testing custom seed words against a target Bitcoin address. The puzzle involves identifying seed words hidden within an image created by the puzzle's creator. Instead of testing all 2048 BIP39 seed words, this script allows users to focus only on the words they've identified, significantly increasing the search speed.

The target address for this puzzle is: **1KfZGvwZxsvSmemoCmEV75uqcNzYBHjkHZ**

## How It Works

- Users manually identify possible seed words from the puzzle image.
- These identified words are added to a `seedwords.txt` file.
- The script generates all possible 12-word combinations from the provided words and checks each combination against the target Bitcoin address.
- If a match is found, the script displays the correct seed phrase and stops.

## Features

- **Custom Seed Word List:** Instead of brute-forcing all possible seed words, this script lets you provide your own list of words based on clues from the puzzle image.
- **Progress Updates:** The script will provide progress updates every 10 seconds, showing how many combinations have been tested so far.
- **Stop on Match:** When the correct seed phrase is found, the script will display it and stop automatically.

## Prerequisites

Before running the script, make sure you have the following installed:

- **Python 3.x**
- The following Python libraries:
  - `bip-utils`
  - `bit`

### Install Dependencies

Install the required libraries using pip:

```bash
pip install bip-utils bit