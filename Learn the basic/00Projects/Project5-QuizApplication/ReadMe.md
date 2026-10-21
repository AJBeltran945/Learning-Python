Project 5 — Quiz Application 🧠
Difficulty: Intermediate
Concepts: Dictionaries, lists, tuples, sets, functions, loops, conditionals, exceptions.

Build a quiz application that asks questions, checks answers, and calculates a final score.

Unlike the number guessing game, this project will teach you how to manage structured information and separate data from program logic.
Features to implement
- Display multiple-choice questions.
- Allow the user to select an answer.
- Check whether the answer is correct.
- Keep track of the score.
- Display the final result.
- Allow the user to choose a quiz category.
- Shuffle the questions.
- Show the correct answers after the quiz.
Example data structure
questions = [    {        "question": "What is the output of print(2 + 3)?",        "options": ("A. 23", "B. 5", "C. 6", "D. 2"),        "answer": "B",        "category": "Python"    },    {        "question": "Which data structure stores unique values?",        "options": ("A. List", "B. Tuple", "C. Set", "D. String"),        "answer": "C",        "category": "Python"    }]


Here, you're combining lists, dictionaries, and tuples in one application.
Python concepts you'll practise

Concept	Practical application
Lists	                Store all quiz questions.
Dictionaries	        Store each question and its associated information.
Tuples	                Store fixed answer options.
Sets	                Track unique categories.
Functions	            Separate question display, answer validation, and scoring.
Loops	                Iterate through questions.
Conditionals	        Determine whether an answer is correct.
Exceptions	            Handle invalid input.
Built-in functions	    Use len(), sum(), sorted(), and enumerate().


You'll also use the random module to shuffle questions.
Additional challenges
- Add a countdown timer.
- Introduce difficulty levels.
- Save the highest score.
- Track scores across multiple attempts.
- Allow users to create their own questions.
- Add a leaderboard.
GitHub repository
Suggested name: python-quiz-app

Suggested description:
An interactive Python quiz application featuring multiple-choice questions, categories, scoring, and dynamic question selection.