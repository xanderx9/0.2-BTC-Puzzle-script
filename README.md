# 0.2 BTC Puzzle

![0.2 BTC Puzzle](https://privatekeys.pw/images/puzzles/0.2-btc-puzzle.png)

This puzzle was created to challenge the community to identify the correct 12-word seed phrase from an image. The solution will unlock a Bitcoin wallet containing 0.2 BTC. The goal is to analyze the image, identify potential seed words, and test them against the targeted Bitcoin address: **1KfZGvwZxsvSmemoCmEV75uqcNzYBHjkHZ**.

## Purpose
This script helps users by allowing them to test only the words they identify from the image instead of testing against the entire BIP39 word list. This significantly increases the search speed by focusing only on the potential words.

## Instructions

Follow these steps to run the script:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/panchpasha/0.2-BTC-Puzzle-script.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd 0.2-BTC-Puzzle-script
    ```

3. **Install Python and pip (if not already installed):**

    Ensure that Python 3.x and pip (Python package installer) are installed on your system. You can check this by running:

    ```bash
    python3 --version
    pip --version
    ```

    If Python or pip is not installed, you can download and install Python from [python.org](https://www.python.org/downloads/).

4. **Create a Python virtual environment:**
    ```bash
    python3 -m venv venv
    ```

5. **Activate the virtual environment:**
    ```bash
    source venv/bin/activate
    ```

6. **Install the required Python packages:**
    ```bash
    pip install bip-utils bit
    ```

7. **Create a text file named `seedwords.txt` in the project directory and add your identified seed words, separated by commas. For example:**
    ```bash
    moon,tower,food,real,black
    ```

8. **Run the script:**
    ```bash
    python3 check_seed_phrases.py
    ```

9. **Follow the on-screen instructions as the script processes the seed words and checks against the Bitcoin address.**

## Hints

- **'Moon'** and **'Tower'** can be found on the clock's hands.
- **'Food'** can be found on the Seattle Space Needle.
- **'Breathe'** can be found on George Floyd's chest as well as the Statue's Neck.
- Rune 1 (Top Left) is in Russian: **"Я нaдeюcь чтo cюдa бyдyт пpиcылaть мнoгo биткoинoв"** and translates to **"I hope that many bitcoins will be sent here."**
- Rune 2 (Bottom Left) is in Russian: **"Cyммa двyx чиceл"** and translates to **"Sum of two numbers."**
- Rune 3 (Above Trump) is in Bill's Cipher and translates to **"Tuesday."**
- Rune 4 (Long on Right) is in Russian: **"Здecь зaшифpoвaны биткoины нa чёpный дeнь нoмep X"** and translates to **"Here are encrypted bitcoins for a rainy day number X."**
- **'This'** is likely a seed word, as it's repeated in **"This is the first prediction," "Fuck this shit,"** and **"Find the seed phrase in this picture."**
- **'Subject'** is underlined on the statue to the right.
- Using Forensically, or Photoshop, the base of the Statue of Liberty reveals **"Only Bitcoin"** under **"Only real Bitcoin,"** which likely means **'Real'** is a seed word.
- The Latin to the bottom left refers to **"The Pot Calling The Kettle Black,"** with **'Black'** also being repeated in references to the Black Lives Matter movement, so it's likely another word.

## Donations

Donations are greatly appreciated and will help enhance the script further and assist others in solving this puzzle.

- **BTC:** 14cxycAfEb3JuFjETXMcyyk56YkDA8DHgT
- **ETH:** 0xc040ddc63d621cfe9f539f4758cd0d805581e24e
- **TRX:** TKojsCqXzdqsLPAMcAiA5gfQSrfGBREwvV
- **SOL:** 6bBrtq9PCBwbofFcofLaehPvMZ3bQFuoRzkmjXfANq7V
