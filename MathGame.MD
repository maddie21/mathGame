# Nouns:

## Name: Players
### Description: 
Contains the information about players such has number of lives.
    State: 
        1. Lives
    Behavior:
        1. Decrease Life

## Name: Question
### Description 
Contains the scope to create and get the questions and evaluate them.
State:
    1. Answer
Behavior:
    1. Create a question
    2. Get the question
    3. Check if the answer being passed is 
    correct

## Name: Game 
### Description
Contains information about the players including the their staus (active/in-active). This noun is also capable of switching turns between players, starting and ending the game, taking input/answer from the user and deciding the winner.
State: 
    1. All Players
    2. Active Player
Behavior:
    1. Switch Turns
    2. Start Game
    3. End Game
    4. Decide a winner
    5. Take Input from User

player1 = Player.new(3);
player1.decreaseLife();

currentQuestion = Question.new();
currentQuestion.getQuestion

currentQuestion.checkIfAnswerIsCorrect("answer")



1. All the nouns have to be created as classes in their own rb files
2. How can you input ruby files into other ruby files
3. Define all the methods (behaviours), eg: when you create a class for a player, what property should you mention? lives?
4. Method to decrease life and spend some time on the question class 
5. 