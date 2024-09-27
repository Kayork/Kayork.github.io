## **Guessing Game**
### Below is the sequence in which the guessing game will flow
- First the software will pick a random number
- Next, the software will ask for a guess
- The Software will then determine if the guess is higher or lower than the random number by subtracting the guess from the random number 
-- ```mermaid
flowchart TD
Start([User Guess]) --> End([Random Number - User Guess])
```
- If the answer is negative, the software will return "**lower**" to the user
- If the answer is positive, the software will return "**higher**" to the user 