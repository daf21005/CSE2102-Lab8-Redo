# CSE 2102 Lab 8 - React Quiz With Scoring

In this lab assignment we are creating a quiz website that will score the user knowledge.

The questions are:
- What is the capital of Connecticut?
- What is the square root of 16?
- What type of number is 101?
- The earth is the fifth planet from the sun?

The way this quiz was built is that the user can only answer the questions once, giving them a feedback (a pop-up) telling them if they are correct or incorrect. Then they can click on the ``done`` button which takes them into the results page, as the name implies shows the user their results. 

In this results page, we calculate their score percentage by the score they got and the number of questions they answered. Each percentage giving the user a different message. 

```bash
Percentage = 100% -> "Perfect"
Percentage = 75 -> "Great job"
Percentage = 50 -> "Good effort"
else "Keep practicing"
```

If the user want to try again they can refresh the page. 


### Important Commands:
```bash
# Installing all dependicies 
npm install
```

```bash
# Run the program (which will open the quiz at a tab)
# Press Ctrl+C or Command+C to stop the server
npm start
```

```bash
# Run the test cases
npm test
npm test -- --watchAll=false
# both commands work, I just used the bottom one to catch the false
```

David Flores