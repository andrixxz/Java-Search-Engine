# Java Search Engine Tool

## Overview
This Java program allows users to search for a word or phrase in multiple files through a user-friendly GUI. After entering the search term, users can select files from their file system, and the program will search through each file line by line, displaying the lines where the term is found in the GUI. 

The program calculates a ranking for each file based on relevance, considering the frequency of the search term and the length of the file. Results are displayed in order of relevance, showing the file paths, number of occurrences, and the percentage of matches in each file.

Users can choose to save this information to a file or clear the output panel for a fresh search.

## Features
- **Multi-file Search**: Search for terms or exact phrases across multiple text files.
- **Relevance-based Ranking**: Results are ranked based on how frequently the term appears in each file, with the most relevant files appearing first.
- **Line-by-line Search**: The program processes each file line by line, ensuring efficient memory usage even for large files.
- **Detailed Output**: Displays the number of occurrences, file path, and percentage of matches for each file.
- **Save/Reset Options**: Users can save the search results to a file or clear the output panel for new searches.
- **User-friendly GUI**: Built using Java Swing, the interface is simple and intuitive.

## Usage
1. After running the program, a GUI window will open.
2. Enter a word or phrase in the search bar.
3. Click the "Click Me To Access Files" button to select one or more `.txt` files.
4. The program will search through each file and display:
   - The file paths where matches are found.
   - The lines containing the search term.
   - The number of occurrences.
   - The percentage of matches in each file.
5. To save the results, click the "Save Output" button. You can also clear the output panel by clicking "Clear Output."
