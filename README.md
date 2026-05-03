# Getting Started with Create React App
 An interactive quiz application that helped me go deeper into state management and user experience 

##💡 What I focused on in this project:

• Implementing a timer using useEffect that controls the quiz duration based on the number of questions
• Building a dynamic progress bar that updates as the user moves through the quiz
• Improving UX by showing the “Next” button only after selecting an answer
• Updating the score instantly after answering each question
• Displaying a high score at the end by comparing the current score with the previous best

##📌 The most interesting part of this project was using useReducer — which was truly the hero here.

Instead of managing multiple useState hooks, I used a single reducer to handle different application states and transitions, including:

• Fetching data (dataReceived / dataFailed)
• Starting the quiz and initializing the timer
• Handling new answers and updating points
• Moving between questions
• Finishing the quiz and calculating the high score
• Restarting the quiz while preserving the best score
• Countdown logic using a “tick” action

This approach made the app more scalable, predictable, and easier to manage — especially with multiple states like loading, ready, active, and finished.

##🎯 Key Features:
• Interactive quiz flow
• Real-time score updates
• Timer-based quiz logic
• High score tracking system
• Clean and maintainable state management with useReducer


This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
