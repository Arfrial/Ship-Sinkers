## Ship Sinkers ##

## Iteration 1 ##
The initial version I had made of Ship Sinkers was implemented entirely on the client side using HTML, CSS, and JavaScript. All of my game logic, ship placement, hit detection, and win/loss conditions were handled locally in the browser, and I still have that version listed in another repo.

## Iteration 2 ##
Another iteration I had added introduced a difficulty-based enemy AI that uses a hunt logic. I have 4 different difficulty settings, ranging from choosing the shots randomly, all the way up to never missing a shot. It does this by analyzing the previous hit to search the adjacent cells and locking the orientation if needed, and will finish off ships on greater difficulties. This iteration significantly improved gameplay in my opinion and added a more fun experience for the user.

## Limitations ##

- The game is only currently single-player and does not have support for multiplayer.
- The project was initially designed to run locally and is not configured for public use.
- Refreshing the browser while in-game resets the game.
- The enemy AI logic runs on the client and does not have memory of past games.
