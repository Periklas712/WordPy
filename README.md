# WordPy
WordPy is a Python program that processes text files to analyze words and build a directed weighted graph based on word sequences.  
It allows users to:
- Find the top-K most probable next words.
- Generate a sequence of the most probable words.
- Generate a random sequence based on word transition probabilities.

## How it works
- Reads all `.txt` files from the current directory.
- Cleans and processes the text into words.
- Builds a graph where edges represent the frequency of consecutive words.
- Provides a menu for interactive usage.
