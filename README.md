# Alien-Dictionary

## Description
Determines the character order of an alien language from a sorted list of words using topological sorting.

## Requirements
- Python 3.x
- No external dependencies

## Algorithm
1. **Graph Construction**: Builds a directed graph by comparing adjacent words
2. **Topological Sort**: Uses Kahn's algorithm to determine character order
3. **Cycle Detection**: Returns empty string if a cycle is found (invalid ordering)

## Usage
```python
from alien_alphabet import find_alien_alphabet

words = ["wrt", "wrf", "er", "ett", "rftt"]
alphabet = find_alien_alphabet(words)
