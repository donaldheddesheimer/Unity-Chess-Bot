# Unity Chess Bot - [Work in Progress]
A simple 2d chess clone that has an AI (bot) that plays moves against the player. The bot is still a work in progress.

![Chess](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/c04dcc5f-bd8a-47f7-bcf7-835afc347ce8)

## How it works
The cloned game follows typically chess rules on an 8x8 grid. You can play white or black and can play Player vs Player or Player vs AI or AI vs AI. The bot looks for moves in the future to decide the best move. 

## Depth of Search
The bot searches for moves up to a certain depth in the game tree. A deeper search allows for a more thorough evaluation of potential moves but also requires more computational resources.

![chess-shannon-type-a](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/64f2de0d-30b9-4b2b-aaa3-95b18e75dbc8)

## Alpha-Beta Pruning
To optimize the search process, the bot uses alpha-beta pruning. This technique reduces the number of nodes evaluated in the search tree by eliminating branches that are unlikely to affect the final decision.

![1_96QEzhnsOkNqz7swB0qx8w](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/7d7b8684-0956-476d-b3c5-0b8cfa4862ef)

## Chess Rules
The algorithm ensures that all generated moves adhere to standard chess rules, including legal piece movements, castling, en passant captures, and pawn promotions.

![Ajedrez_captura_al_paso_del_peon](https://github.com/donaldheddesheimer/Unity-Chess-Bot/assets/119540065/29e61f3f-a39f-4677-a112-96e8cccfc71a)

