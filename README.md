# Basic Snake HTML and JavaScript Game

Snake is a fun game to make as it doesn't require a lot of code (less than 100 lines with all comments removed). This is a basic implementation of the snake game, but it's missing a few things intentionally and they're left as further exploration for the reader.

<img width="300" height="300" alt="" src="https://user-images.githubusercontent.com/2433219/94984424-044e0a80-0509-11eb-903a-c114d5b6f061.png">

## Further Exploration

- Score
  - When the snake eats an apple, the score should increase by one. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
- Mobile and touchscreen support
  - Allow the game to be scaled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Better apple spawning
  - Currently the apple spawns in any random grid in the game, even if the snake is already on that spot. Improve it so it only spawns in empty grid locations
  
**Important note:** I will answer questions about the code but will not add more features or answer questions about adding more features. This series is meant to give a basic outline of the game but nothing more.
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.
