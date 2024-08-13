# Python-Project--Cricket-Quiz-game



# Welcome message for the quiz game
print("Welcome to the Cricket Quiz Game created by Aanjenay Pandey")

# Ask the user if they want to play the game
playing = input("Do you want to play the game? ")

# If the user's response is not 'yes', exit the game
if playing.lower() != "yes":
    quit()

# Inform the user that the game is starting
print("Okay, let's play!")
score = 0

# Question 1: Highest run scorer in ODI
answer = input("Who is the highest run scorer in ODI? ")

# Check if the answer is correct and update the score accordingly
if answer.lower() == "sachin tendulkar":
    print("Congratulations! Your answer is correct.")
    score += 1
else:
    print("Sorry, your answer is incorrect & unfortunately, the game is over.")
    quit()

# Question 2: Winner of ICC ODI World Cup 2023
answer = input("Who is the winner of ICC ODI World Cup 2023? ")

# Check if the answer is correct and update the score accordingly
if answer.lower() == "australia":
    print("Congratulations, you're doing good!")
    score += 1
else:
    print("Sorry, your answer is wrong, so unfortunately your game is over.")
    quit()

# Question 3: Current captain of the Indian Test cricket team
answer = input("Who is the current captain of the Indian Test cricket team? ")

# Check if the answer is correct and update the score accordingly
if answer.lower() == "rohit sharma":
    print("Congratulations, Champ! Correct answer.")
    score += 1
else:
    print("Sorry, your answer is incorrect. Better luck next time.")
    quit()

# Question 4: Location of Wankhede Stadium
answer = input("Where is Wankhede Stadium located? ")

# Check if the answer is correct and update the score accordingly
if answer.lower() == "mumbai":
    print("Congratulations! Your answer is correct, Champ.")
    score += 1
else:
    print("Sorry, your game is over, but be proud of yourself because you answered all previous questions correctly.")
    quit()

# Question 5: Team that won IPL 2024
answer = input("Which team won IPL 2024? ")

# Check if the answer is correct and update the score accordingly
if answer.lower() == "kkr":
    print("Congratulations! Your answer is correct.")
    score += 1
else:
    print("Sorry, your game is over.")
    quit()

# Question 6: Winner of ICC Champions Trophy 2013
answer = input("Who was the winner of ICC Champions Trophy 2013? ")

# Check if the answer is correct and update the score accordingly
if answer.lower() == "india":
    print("Congratulations! Your answer is correct, and you are qualified for the final round of our game.")
    score += 1
else:
    print("Sorry, your game is over. But be proud of yourself because you played well.")
    quit()

# Question 7: Winner of ICC T20 World Cup Final 2024
answer = input("Which team won the ICC T20 World Cup Final 2024? ")

# Check if the answer is correct and update the score accordingly
if answer.lower() == "india":
    print("Congratulations! You are the winner of our game.")
    score += 1
else:
    print("Sorry, your game is over. But be proud of yourself because you were disqualified in the final round.")
    quit()

# Final score announcement
print("You got " + str(score) + " question(s) correct.")
