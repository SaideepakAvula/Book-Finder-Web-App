# Book-Finder-Web-App

📚 Book Finder Web App
A dynamic book recommendation app using LLMs (Large Language Models) and API integration.

🚀 Project Overview

The Book Finder Web App allows users to search for books based on genre, author, mood, or theme and provides unique, fresh recommendations using a Large Language Model (LLM). Each search delivers a new set of book recommendations, ensuring variety and avoiding repetition.

🛠️ Features

✅ Dynamic Book Search – Find books by genre, author, or theme.

✅ Unique Recommendations – No repetitive book suggestions.

✅ Smart Filtering – Avoids showing the same books in back-to-back searches.

✅ API Integration – Option to fetch real-time book data from Google Books API or Open Library API.

✅ Responsive UI – Works on both desktop and mobile devices.

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript (Vanilla JS / React.js)

Backend (Optional): Node.js / Express.js (for API calls)

API: Google Books API / Open Library API

AI: Bolt.ai (LLM for recommendations)


🔧 Setup & Installation

1️⃣ Clone the Repository

git clone https://github.com/yourusername/book-finder-app.git
cd book-finder-app

2️⃣ Install Dependencies (If using a backend or React)

npm install

3️⃣ Run the Application

If using a simple HTML/JS file, just open index.html in a browser.

If using Node.js/React, start the server:
   npm start

📝 Usage Guide

1️⃣ Enter a genre, author, or theme in the search bar.

2️⃣ Click Search, and the app will suggest books.

3️⃣ Repeat with different queries to see fresh recommendations.

4️⃣ Click on a book to get more details (if API integration is enabled).

🛠️ API Integration (Optional)

To fetch live book data, integrate the Google Books API:

Get an API key from: Google Books API

Add this to your JavaScript:

fetch(`https://www.googleapis.com/books/v1/volumes?q=${userQuery}`)
  .then(response => response.json())
  .then(data => console.log(data.items));

  ![Screenshot 2025-03-05 064340](https://github.com/user-attachments/assets/090d15f7-c09c-4751-a829-3b3fa76f1276)

  




