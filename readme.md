# Flashy - Flash Cards Project

## Description
- Implementation of the simple Flash Card App using latest technologies of <strong>Tkinter GUI Framework, OOP concepts, Python, and Pandas Data Analysis Library</strong>.
- The app helps users to practice different questions, and in this case, it is French words.
- The app displays a question and gives 3 seconds to answer it before flipping the card to show answer.
- If the user's answer was correct, they can press check mark button and the app will remove that question from the list (will not be repeated and saved in `*to_learn.csv` file).
- If the user's answer was wrong, the question will remain in the list and repeated until answered right.
- After every correct answer, the app updates `*_to_learn.csv` file where will be listed list of questions that user couldn't answer.
- Exception Handlers are implemented to ensure file existence, otherwise it will open `french_words.csv` by default.

## How to Setup the Project
1. Create an empty folder
2. Add the folder to workplace area in your VS Code and open terminal OR navigate to the created folder using terminal
3. Download the project .zip file OR Enter to the terminal:
   `git clone https://github.com/ZhenyaChan/flash_cards_project.git`
4. Run the code by entering `python -u "./main.py`