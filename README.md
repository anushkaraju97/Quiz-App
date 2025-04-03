# Quiz App in LWC (Lightning Web Components)
A Salesforce-based Quiz App built using Lightning Web Components (LWC) that allows users to answer multiple-choice questions and view their results.

## Overview
This project is a **Quiz Application** built using **Salesforce Lightning Web Components (LWC)**. The app allows users to answer multiple-choice questions and get feedback on their performance after submitting their responses. The quiz includes dynamic question rendering and a result display, showing how many questions were answered correctly.

## Features
- **Dynamic Question Rendering**: The app renders a set of quiz questions with multiple-choice options, making it easy to scale and add more questions.
- **Real-time Answer Selection**: Users can select answers using radio buttons, and their selections are stored dynamically.
- **Scoring System**: After submission, the app displays the total score, showing how many correct answers were selected.
- **Responsive UI**: Built with **Salesforce Lightning Design System (SLDS)**, ensuring a modern, responsive interface that is consistent with Salesforce’s design principles.
- **Reset Functionality**: Users can reset the quiz to start again with all selections cleared.

## How It Works
1. **Dynamic Question List**: The app dynamically generates questions with radio buttons for multiple-choice answers.
2. **Answer Selection**: As the user selects answers, the selected answers are stored in the component state.
3. **Submit**: When the user clicks "Submit", the app compares the selected answers with the correct ones, calculates the score, and displays the result.
4. **Reset**: The user can reset the quiz to its initial state at any time.

