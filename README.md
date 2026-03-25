# 🕵️‍♂️ Investigation Report: The Titanic Passenger Puzzle

# 1. Overview of the Mission
This project is a digital investigation into a famous historical event: the sinking of the **Titanic**. Our mission was to use computer "detective work" (called Data Science) to see if we could predict which passengers were likely to survive the journey based on information about them.

# 2. The Evidence (Our Data)
To solve this puzzle, we looked at three main lists of information:
* **The Training List (train.csv)**: A list of passengers where we already knew who survived. We used this to teach the computer how to find patterns.
* **The Mystery List (test.csv)**: A list of passengers where the survival outcome was hidden. This is where the computer had to make its best "guesses."
* **The Answer Key (gender_submission.csv)**: A file used to check if our computer's guesses were correct.

# 3. The Detective Work (Methodology)
Just like a real detective, we couldn't just look at messy clues. We had to prepare them first:
* **Organizing the Files**: We used a tool called **Pandas** to turn the lists into neat tables that the computer can read easily.
* **Cleaning the Clues**: Some information was missing, like people's room numbers (the "Cabin" column). We removed the messy or empty parts so the computer wouldn't get confused.
* **Checking the Details**: We looked at specific clues for each person, such as:
    * **Class**: Were they in a fancy 1st-class room or a 3rd-class room?
    * **Gender**: Were they male or female?
    * **Age**: How old were they?

# 4. The Detective's Tool Kit
We used several special digital tools to help us:
* **Pandas & NumPy**: For sorting through thousands of names and numbers.
* **Matplotlib & Seaborn**: For drawing colorful charts and graphs so we could "see" the patterns with our eyes.

# 5. Summary of Findings
By looking at the data, we can start to see "rules" that the computer learns. For example, in many cases, passengers in higher-class rooms or women and children had a better chance of reaching the lifeboats. 

# 6. How to Read the Investigation
If you want to see exactly how the detective work was done:
1.  Open the file named 'solution.ipynb'.
2.  Follow the steps from top to bottom to see how we loaded the data, cleaned the mess, and prepared the computer to solve the mystery.

#💡 Why we do this
By practicing on the Titanic story, we learn how to use data to solve real-world problems today, like predicting the weather or helping doctors find the best medicine for patients!
  


# 🕵️‍♂️ Final Investigation Report: Titanic Data

## Step 1: Gathering the Detective Tools
First, I brought in my special digital tools (called libraries) to help me look at the information and draw pictures of what I find.
* **Pandas & NumPy**: These are like super-fast calculators that help me organize thousands of names.
* **Matplotlib & Seaborn**: These help me create colorful charts so we can "see" the patterns.

# Step 2: Reading the Passenger Lists
I opened three main lists of information about the people on the ship:
1.  **The Training List**: This had the names and details of passengers where we already knew if they were safe.
2.  **The Test List**: This was a new list where we had to practice guessing who survived.
3.  **The Submission List**: A simple file used to record our final guesses.

# Step 3: Inspecting the Evidence
I looked at the first 10 people on each list to understand what kind of clues we had.
* **Clues included**: Their names, their ages, whether they were male or female, and what kind of room (Class) they had.
* **The Problem**: I noticed that many people didn't have a room number listed (it said "NaN," which means "Not a Number" or "Missing").

# Step 4: Fixing the Messy Clues (Data Cleaning)
A good detective doesn't use broken clues! I decided to clean up the list:
* **The Big Cleanup**: I removed any passengers from my list who were missing important information like their **Room Number (Cabin)**, their **Gender (Sex)**, or their **Ticket Type (Pclass)**.
* **Why?**: By removing the "mysterious" or empty parts, the computer can learn from the clear information without getting confused.

# Step 5: Checking the New List
After the cleanup, I looked at the list again. Now, every person on my list has clear information about their room and who they were. This makes it much easier for the computer to start finding patterns—like seeing if people in 1st Class had a better chance of finding a lifeboat!

# Conclusion
We have successfully prepared our evidence. The next step in a project like this would be to let the computer "study" these patterns so it can become an expert at predicting who might have survived the journey!


