# :wave: 

## This project is a Scrabble word game that allows players to drag and drop letter tiles onto a Scrabble board to form words. The game uses a data structure to randomize the selection of four letter tiles for the player's hand. The game also identifies which letter tile is dropped onto which Scrabble square using an array to slice class names and a dict to store values. The board includes at least two bonus squares, triple letter score, and double letter score, and the score is tallied correctly, including consideration of bonus square multipliers.

## The game allows any number of words to be played until the player wishes to quit or depletes all tiles. After playing a word, only the number of letter tiles needed to bring the player's "hand" back to 7 tiles are selected. The board is cleared after each round so that a new word can be played.

## Tiles can only be dragged from the "rack" to the Scrabble board, and if the user drops them anywhere else, they will be bounced back to the "rack." Except for the first letter, all subsequent letters must be placed directly next to or below another letter with no space; otherwise, they will bounce back to the "rack." The user can always restart the game.

## The project uses JQuery to enable the drag and drop feature and CSS to position the letter tiles on the rack. The project is partially based on embedded code sources and includes some in-depth documentation on what features work, partially work, and don't work at all.
