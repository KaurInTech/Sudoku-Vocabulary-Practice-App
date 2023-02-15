## Different Devices:
**User Story:** As a vocabulary learner practicing at home, I want to use my tablet for Sudoku vocabulary practice, so that the words will be conveniently displayed in larger, easier to read fonts.

**TDD Example:** Given that the user wanted to display these menus and the game board within the app in a larger device: 
>> <img src="../Images/beforeTablet.png" alt="Before Tablet" width="400"/>
>> <img src="../Images/beforeTablet2.png" alt="Before Tablet 2" width="400"/>
The user can open the app on a tablet size device.
>> <img src="../Images/afterTablet.png" alt="After Tablet" width="400"/>
>> <img src="../Images/afterTablet2.png" alt="After Tablet 2" width="400"/>
Then when used on tablet devices the app will make use of space by enlarging the font and the game board. The placements and size of UI elements will also change based on the new aspect ratio of the tablet device. 

**User Story:** As a vocabulary learner taking the bus, I want to use my phone in landscape mode for Sudoku vocabulary practice, so that longer words are displayed in a larger font than standard mode.

**TDD Example:** Given that the user wanted to display these menus and game board in a landscape mode perspective:
>> <img src="../Images/beforeLandscape.png" alt="Before Landscape" width="400"/>
>> <img src="../Images/beforeLandscape2.png" alt="Before Landscape 2" width="400"/>
The user can rotate their device - either phone or tablet - to the orientation they wish.
>> <img src="../Images/afterLandscape.png" alt="After Landscape" width="700"/>
>> <img src="../Images/afterLandscape2.png" alt="After Landscape 2" width="700"/>
This will switch to landscape mode within the app and change the orientation of the game board and the word bank. The game board will make use of the entire height of the screen, while the word bank will be moved to one side where there is space. This will also affect any other menus within the app.  

## Vocabulary Lists:
**User Story:** As a teacher, I want to specify a list of word pairs for my students to practice this week.

**User Story:** As a student working with a textbook, I want to load pairs of words to practice from each chapter of the book.

**TDD Example:** After selecting the play button, the user will be able to go to the "Word Pair Menu", which will then allow the user to manually enter the Spanish and English words into two text boxes. Each of these word pairs will be saved into a list which can then be accessed by tapping "Manage Pairs".
Extra functionality within the "Manage Pairs" menu would include being able to delete words and edit spelling.
During a game, these stored words can then be accessed and used on the game board, allowing the user to practice with them without knowing exactly when they will appear.
>> <img src="../Images/addPair.png" alt="Add Pair" width="400"/>
>> <img src="../Images/WordPairs.png" alt="Word Pairs" width="400"/>

**User Story:** As a student, I want the Sudoku app to keep track of the vocabulary words that I am having difficulty recognizing so that they will be used more often in my practice puzzles.

**TDD Example:** When a user is playing a game the app will track any words which they have consistently made mistakes with and likely need more practice, words within this list will be given a higher probability to show up on the game board in any games played thereafter.

## Different Sized Grids:
**User Story:** As a teacher of elementary and junior high school children, I want scaled versions of Sudoku that use 4x4 and 6x6 grids. In the 6x6 grid version, the overall grid should be divided into rectangles of six cells each (2x3).

**TDD Example:** From the main menu after clicking the play button, the user will be shown a menu with multiple board sizes displayed by text detailing their dimensions. This menu also contains the "Word Pair Menu" button. The user can then select which size of game board they want before clicking the play button once more. 
>> <img src="../Images/boardSize_menu.png" alt="Board Size Menu" width="400"/>
The appropriate grid size will be used during a game, and the total number of words will be equal to the amount of cells in one sub-grid (4 words for 4x4, 6 words for 6x6, etc.). Font size will be scaled depending on the size of board, making smaller board sizes easier to read.
>> <img src="../Images/tablet_gameboard4x4.png" alt="4x4 Board" width="400"/>
>> <img src="../Images/tablet_gameboard6x6.png" alt="6x6 Board" width="400"/>

**User Story:** As a vocabulary learner who wants an extra challenging mode, I want a 12x12 version of Sudoku to play on my tablet. The overall grid should be divided into rectangles of 12 cells each (3x4).

**TDD Example:** Given that the user was at the menu detailed above:
>> <img src="../Images/before12x12.png" alt="Before 12x12" width="400"/>
 The user can select a scaled 12x12 size from the menu showing 4 different board sizes, then click "Play" to begin the game. 
 >> <img src="../Images/after12x12.png" alt="After 12x12" width="400"/>
 The game board will be scaled accordingly, with 9 sub-grids containing 12 cells each. This new size of game board will present a more challenging difficulty requiring expert knowledge of game logic.

## Convenience:

**User Story:** As someone who has played sudoku using pen and paper many times I would like this app to highlight other instances of the same word within the grid while I have a word selected. This would make the experience more enjoyable for me, removing some of the laborious parts of solving sudoku puzzles, and it allows for something I could never have on paper.

**TDD Example:** Given that the user wanted to select Frio (Fr) in this grid:
>> <img src="../Images/beforeHighlight.png" alt="Before Highlight" width="400"/>
When the user selects any filled cell within the grid, other cells containing the same word will be highlighted, making them clearly visible.
>> <img src="../Images/afterHighlight.png" alt="After Highlight" width="400"/>

**User Story:** As a person who has spent many hours checking if I solved a sudoku puzzle correctly, I would love to have a clear win screen that appears within the app when you successfully solve a board.

**TDD Example:** Given that the user wanted to solve this board:
>> <img src="../Images/beforeSolve.png" alt="Before Solve" width="400"/>
The user can go through and successfully solve this board, maintaining the game rules and filling every cell.
>> <img src="../Images/afterSolve.png" alt="After Solve" width="400"/>
Then a large win screen will appear signaling that you have solved the board.


## Listening Comprehension:

**User Story:** As a student who wants to practice my understanding of spoken words in the language that I am learning, I want a listening comprehension mode. In this mode, numbers will appear in the prefilled cells. When I press the number, the corresponding word in the language that I am learning will be read out to me. I can then test my listening comprehension by selecting from the menu the correct English translation of the word.

**TDD Example:** Within the new game menu (also containing board sizes) there will be a button labeled: "Listening Comprehension". When this option is selected the game board will be changed so that only numbers appear in the filled cells. 
When the cells are clicked, instead of displaying the word in text, an audio clip will play pronouncing the word meant to fill that place. Additionally there will be a volume control slider at the top for if the voice is too quiet or loud. 
>> <img src="../Images/listeningComp.png" alt="Listening Comprehension" width="400"/>
The English words will still be text in the selection menu, this is so the user can practice listening to Spanish words and choosing the correct English translation.

