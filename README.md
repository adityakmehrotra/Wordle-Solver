# Wordle-Solver

## Overview
The Wordle Solver is an advanced Python-based tool designed to optimize guesses in the popular Wordle game. By analyzing letter frequencies and positions within five-letter words, this algorithm achieves an impressive average of 3.67 guesses per game. Utilizing a recursive strategy, the solver systematically refines and eliminates word options, efficiently honing in on correct answers.

## Features
- **Optimal Guess Computation:** Calculates the most strategic guesses based on letter frequency and positional data.
- **Recursive Solution Narrowing:** Implements a recursive method to progressively eliminate non-viable word options after each guess.
- **Performance Metrics:** Tracks and displays performance statistics, including average guesses per game.

## Getting Started

### Prerequisites
Ensure you have Python installed on your machine. Python 3.8 or later is recommended.

### Installation

#### Clone the Repository

```bash
git clone https://github.com/adityakmehrotra/wordle-solver.git
cd wordle-solver
```

#### Install Required Libraries

```bash
pip install -r requirements.txt
```

#### Usage
To use the Wordle Solver, run the main script from the command line:

```bash
python wordle_solver.py
```

##### Follow the on-screen prompts to input letters and receive the next suggested guess.

### Last Updated
06/24/2024
