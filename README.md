# Higher-Lower-Game
This is a fun and interactive **Higher or Lower** game where players are tasked with guessing which account from Instagram-like data has more followers. The game is repeatable and keeps track of the player's score until they make an incorrect guess.

## Features

- **Randomized Accounts**: Two random accounts are displayed, and the player guesses which one has more followers.
- **Score Keeping**: The player's score is incremented for each correct guess.
- **Repeatable Gameplay**: The game continues until the player makes an incorrect guess.

## Functions
* **format_data(account):** This function takes the account data and returns a formatted string for display.
* **check_answer(user_guess, a_followers, b_followers):** Compares the follower count of two accounts and checks if the player's guess is correct.
* **Main game loop:** Continually generates new accounts for comparison, checks the guess, updates the score, and either continues the game or ends it based on the player's performance.
