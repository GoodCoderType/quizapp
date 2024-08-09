# Quiz Bot 🧠

Welcome to **Quiz Bot**! This is a simple and interactive quiz application built using Python and Tkinter. The app presents a series of questions to the user and allows them to answer True or False. At the end of the quiz, the user’s score is displayed.

## Features
This App Have 50 Questions In Total
- **Dynamic Questions**: The app fetches questions from a data file and displays them one by one.
- **Interactive UI**: Built using Tkinter, the app has a user-friendly interface with buttons to submit answers.
- **Score Tracking**: The app keeps track of the user’s score throughout the quiz.
- **Immediate Feedback**: After each answer, the app provides immediate feedback and changes the background color to indicate if the answer was correct or incorrect.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/quiz-bot.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd quiz-bot
   pip install thinter
   ```

3. **Ensure you have Python installed.**

   You can check this by running:

   ```bash
   python --version
   ```

4. **Install the required dependencies:**

   This project requires the `tkinter` package, which should come pre-installed with Python. If not, you can install it using:

   ```bash
   sudo apt-get install python3-tk
   ```

5. **Run the application:**

   ```bash
   python main.py
   ```

## Usage

- Once you run the application, a window will pop up displaying the quiz.
- Answer each question by clicking the **True** or **False** button.
- Your score will be updated and displayed at the top of the window.
- Once you’ve answered all the questions, the app will display your final score.

## File Structure

- **main.py**: The entry point of the application where the quiz starts.
- **question_model.py**: Contains the `Question` class, which handles the question text and correct answer.
- **data.py**: Contains the question data used in the quiz.
- **quiz_brain.py**: Manages the quiz logic, including tracking the current question, checking answers, and keeping score.
- **ui.py**: Contains the `App` class that handles the user interface and interactions with the user.

## Example

![Quiz Bot Screenshot](https://media.discordapp.net/attachments/1269913053529505836/1271383561790029896/image.png?ex=66b723b6&is=66b5d236&hm=9d5d4dae57591b5a632e7ab28e4aca185e8a320ce3e209c0d7dfdc32b078704d&=&format=webp&quality=lossless&width=444&height=578)

## Contributing

If you’d like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, feel free to reach out at discord goodgamerback
