# World Capital Quiz

This is a simple quiz website built using Node.js, Express, and PostgreSQL. The game tests users on their knowledge of world capitals. For each question, users need to enter the capital city of a randomly selected country. The app tracks the total correct answers until the game ends.

## Features

- Randomly selects a country for each quiz question.
- User submits the capital city name, and the app checks if the answer is correct.
- Displays the user's score after each correct answer.
- Game over when an incorrect answer is submitted, displaying the final score.
- The ability to restart the game with a new country quiz.

## Demo

![image](https://github.com/user-attachments/assets/d7774eef-98a6-463b-b16b-d2fc10f0c83e)


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mhmdfk/World-Capital-Quiz.git
   cd world-capital-quiz

2.Install the dependencies:
   '''bash npm i'''

3.Set up the PostgreSQL database:
  Create a database called world.
  Add a capitals table with columns country and capital.   

4.Run the application:
 '''bash npm nodemon index.js '''

5.Open your browser and navigate to http://localhost:3000 to play the quiz.

## Technologies Used
- **Node.js**: JavaScript runtime.
- **Express**: Web framework for Node.js.
- **EJS**: Templating engine for rendering the frontend.
- **PostgreSQL**: Database to store country and capital information.
- **CSS**: Basic styling.

## Contributing
Feel free to submit pull requests to enhance the features or fix bugs.   
