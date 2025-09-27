# Puzzle Grove

A collection of word games and puzzles inspired by popular games from The New York Times and other sources.

## Games

### Wordle
Guess the 5-letter word in 6 tries. After each guess, the color of the tiles will change to show how close your guess was to the word.
- Uses an external word list from `wordle_words.txt`
- Tracks statistics across sessions using local storage
- Features a responsive design with centered header

### Connections
Find groups of four items that share a common theme. Select four items and submit your answer to see if they belong together.
- Based on NYT's Connections game
- Uses puzzle data from `connections_words.json`
- Features color-coded groups with difficulty levels
- Tracks statistics and streak

### Word Strands
Connect letters in a grid to discover themed words. Letters can connect in any direction (horizontal, vertical, or diagonal).
- Inspired by NYT's Strands game
- Features themed puzzles with letter-by-letter selection
- Includes a hint system for discovering words
- Tracks discovered words and completion progress

### Anagrams
Unscramble letters to form words related to a theme. Progress through five increasingly difficult anagrams.
- Uses themed word sets from `anagram_puzzles.json`
- Features themed word sets organized by difficulty
- Includes a hint system if you get stuck
- Tracks score, streak, and time
- Allows sharing results with friends

## Technologies Used
- HTML5
- CSS3 with responsive design
- JavaScript (ES6+)
- Local Storage API for game state persistence
- Fetch API for loading external word lists and puzzle data

## Setup
Simply open `index.html` in your web browser to start playing.
