# UserAddForm – Dynamic User Card Generator

A simple and elegant frontend project that allows users to add profile details through a form and dynamically display them as responsive user cards using JavaScript DOM manipulation and Tailwind CSS.

live at: https://gireejesh-nilesh.github.io/UserAddForm/

## Project Overview

UserAddForm is a beginner-friendly JavaScript project focused on practicing:

DOM manipulation

Form handling

Object-oriented JavaScript

Dynamic UI rendering

Users can enter details like name, role, bio, and photo URL, and upon submission, a stylish user card is generated instantly on the page.

## Features

📝 Add user details through a form

🖼️ Display user photo using image URL

🎨 Modern UI using Tailwind CSS

⚡ Dynamic card creation without page reload

📱 Fully responsive layout

🧠 Uses object-based architecture for logic handling

## Tech Stack
Technology	Purpose
HTML5	Structure
Tailwind CSS	Styling & responsiveness
JavaScript (ES6)	Logic & DOM manipulation
## Project Structure
UserAddForm/
│
├── index.html     # Main HTML structure
├── script.js      # JavaScript logic
└── README.md      # Project documentation

## How It Works

User fills in the form:

Name

Role

Bio

Photo URL

On clicking Submit:

Form submission is prevented

User data is stored in an array

UI is re-rendered dynamically

A user card is generated and displayed below the form.

## JavaScript Logic Explained
Object-Oriented Structure
const userManager = {
  users: [],
  init() { ... },
  submitForm() { ... },
  addUser() { ... },
  renderUi() { ... }
};

Key Responsibilities

init()
Initializes the app and attaches event listeners.

submitForm()
Prevents page reload and triggers user creation.

addUser()
Stores user data into an array and resets the form.

renderUi()
Dynamically creates and displays user cards using DOM APIs.

## UI Highlights

Gradient background for modern look

Glassmorphism-style cards

Hover animations on user cards

Mobile-first responsive grid layout

## How to Run Locally

Clone the repository:

git clone https://github.com/Gireejesh-Nilesh/UserAddForm.git


Navigate to the folder:

cd UserAddForm


Open index.html in your browser

✅ No additional setup required

## Sample Use Case

Adding team members

Displaying portfolio profiles

Practicing DOM & JS fundamentals

UI/UX experimentation with Tailwind

## Future Enhancements

❌ Delete user card

✏️ Edit user details

💾 Store users using Local Storage

🔍 Search & filter users

🖱️ Drag & reorder cards

👨## Author

Nilesh Shakhya

GitHub: https://github.com/Gireejesh-Nilesh

📜 License

This project is open-source and free to use for learning and practice purposes.