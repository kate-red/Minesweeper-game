# Minesweeper-game
## Minesweeper game: rules
Minesweeper has very simple rules. The playing field is divided into cells, some of which are mined. To win, you need to open all the cells without hitting the mines. Digits are displayed in open cells, each digit is the number of mines in neighboring cells. With this information, you can determine which cells contain mines.

The game has 3 difficulty levels: easy, medium and hard. They are differ by the amount of mines placed on the field and by the field size.

## Functions of the game:
- start_game: initiates the playing process: print rules and collect information from other functions;
- create_field: the function creates a playnig field m by n cells, depending on the chosen difficulty level;
- get_mines_position: the function randomy select place for k mines on the playing field, depending on the chosen difficulty level;
- place_mines: the functions insertes mines to the playing field;
- add_mines_number, is_mine: depending on the cells where mines were plased, add_mines_number function adds the number of mines in the neighboring cells. is_mine is a helping function to determine weather there is a mine in the neighbouring cells;
- check_user_level_input, check_user_field_input, : checks whether the user input difficulty level or cell coordinates correctly;
- user_input_new_game: afrer the game finishes, ask user if he would like to play one more time;
- open_zeros_cells: if the player uncovers "0" cell, all the adjacent zero cells must also be uncovered;
- game_status: if the user manages to reveal all the cells without touching the mines;
