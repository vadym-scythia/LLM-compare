Name: AI vs AI Snake Team Death Match

Interaction type: Zero shot

Prompt:

"Task: Develop an "AI vs AI Snake Team Death Match" game using vanilla HTML, CSS, and JavaScript.

Snake Rules: The game starts with one green-team snake and one blue-team snake, each 1 square long. When a snake eats a food item, its length increases by the food’s value. A snake dies upon colliding with any other snake. Each snake moves toward the nearest food item while trying to evade obstacles. Each snake eats, moves, and collides with its head.

Food Rules: The number of food items on the field is always equal to the number of snakes minus 1. Each food item has a random value between 1 and 5.

Score Rules: Each team starts with a score of 0. When a snake eats food, the food’s value is added to its team’s score. If a snake collides with a teammate, the collided snake’s team loses points equal to the dead snake’s length. If a snake collides with an opponent, the collided snake’s team loses points equal to the dead snake’s length multiplied by 2. A team’s score cannot drop below 0. To spawn a new snake, a team’s score must be at least equal to the number of its snakes multiplied by 5.

Game Rules: The first team to reach a score of 200 wins the game. A team loses the game if it has no snakes left. The user sets the game field size in pixels before the game starts (minimum: 600×800 pixels). The background should be dark. The game field has looped boundaries (if a snake moves past one edge, it reappears on the opposite side).

Output: A fully functional index.html file that runs the game directly in a browser."