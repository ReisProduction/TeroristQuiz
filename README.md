# TeroristQuiz
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/BayramReisbirligi/TeroristQuiz)

TeroristQuiz is an interactive web-based game that challenges users to identify which organization an individual belongs to based on their photograph. The quiz includes an option to add AI-generated civilian photos to increase the difficulty.

## Live Demo

You can play the quiz live here: **[TeroristQuiz](https://bayramreisbirligi.github.io/TeroristQuiz/)**

## Features

- **Interactive Quiz Interface**: Users are presented with a person's image and four potential organizations to choose from.
- **Score Tracking**: The application keeps track of correct and incorrect answers. Scores are saved in the browser's local storage, so your progress is maintained across sessions.
- **Include Civilians**: A toggle switch allows you to add AI-generated "civilian" photos into the quiz, making it more challenging to distinguish actual targets.
- **Score Reset**: Easily reset your score to start over.
- **Performance Feedback**: After every 20 questions, the game provides a summary of your success rate with a themed message.
- **Responsive Design**: The user interface is designed with a sleek, dark theme and is fully responsive for both desktop and mobile devices.

## How It Works

The application pulls data from two main sources:

- **Wanted Individuals**: The data for wanted individuals is sourced from the publicly available list provided by the [T.C. İçişleri Bakanlığı Terör Arananlar](https://www.terorarananlar.pol.tr/tarananlar/).
- **Civilian Photos**: To provide a "Sivil" (Civilian) option, the quiz dynamically fetches unique, AI-generated human faces from [https://thispersondoesnotexist.com](https://thispersondoesnotexist.com).

The JavaScript logic fetches this data, randomizes the questions, presents the quiz, checks answers, and updates the score.

## Getting Started

To run this project on your local machine, simply follow these steps:

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/bayramreisbirligi/TeroristQuiz.git
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd TeroristQuiz
    ```

3.  **Open the application:**
    Open the `index.html` file in your preferred web browser. No special server or build process is required.

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- [SweetAlert2](https://sweetalert2.github.io/): For clean and responsive pop-up messages.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
