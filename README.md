# Flash-Card
A very basic Flash Card App. In this specific model, it is a French-English Vocabulary flashcard.

## Learn French vocabulary with this interactive flashcard application

### Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Code Structure](#code-structure)
4. [How to Use](#how-to-use)
5. [Dependencies](#dependencies)

### Introduction
This is a Python-based application that helps users learn French vocabulary using flashcards. The app presents French words and their English translations, allowing users to practice and track their progress.

### Features
- Interactive flashcards with French words and English translations
- Automatic card flipping to reveal translations
- Progress tracking by removing known words from the learning set
- Simple and intuitive user interface

### Code Structure
The code is structured as follows:

1. **Imports and Setup**: 
   - Import necessary libraries (random, tkinter, pandas)
   - Set up global variables and constants

2. **Data Loading**:
   - Attempt to load existing learning data
   - If not found, load the original French words dataset

3. **Core Functions**:
   - `next_card()`: Display the next flashcard
   - `flip_card()`: Reveal the English translation
   - `is_known()`: Handle known words and update the learning set

4. **UI Setup**:
   - Create the main window
   - Set up the canvas for displaying flashcards
   - Create and place buttons for user interaction

5. **Application Loop**:
   - Start with the first card
   - Run the main application loop

### How to Use
1. Run the script to start the application
2. A French word will be displayed on the flashcard
3. After 3 seconds, the card will flip to show the English translation
4. Click the ✓ button if you know the word, or the ✗ button to see the next word
5. Known words will be removed from the learning set

### Dependencies
- Python 3.x
- tkinter
- pandas

This application provides an engaging way to learn French vocabulary, with a focus on user interaction and progress tracking. The code is well-structured and commented, making it easy to understand and modify as needed.


