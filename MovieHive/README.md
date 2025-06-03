# 🎬 MovieHive

**MovieHive** is a simple and interactive React web application that allows users to view, add, search, like, and delete movies. Built using React components, it demonstrates the fundamentals of building reusable UI, state management, and user interaction in modern frontend development.

---

## 🚀 Features

* 🔍 **Search** movies by title
* ➕ **Add** a new movie with title, year, and genre
* ❤️ **Like** a movie (toggle like/unlike)
* 🗑️ **Delete** a movie from the list
* 🧩 Reusable **components** for movies and lists
* 💡 Clean and readable layout using basic inline styling

---

## 🛠️ Technologies Used

* **React** (Functional components and Hooks)
* **JavaScript (ES6)**
* **HTML & CSS (inline styling)**

---

## 📁 Project Structure

```
MovieHive/
├── public/
├── src/
│   ├── App.jsx           # Main component
│   ├── MovieList.jsxx      # Component for displaying the movie list
│   ├── Movie.js          # Component for individual movie cards
│   ├── MovieForm.jsx      # Component for adding new movies
└── README.md
```

---

## 🖥️ How to Run the App Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/MovieHive.git
cd MovieHive
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

The app will open in your browser at `http://localhost:3000`.

---

## ✨ Future Improvements

* Add localStorage or backend to persist movies
* Add rating and description fields
* Use a movie API (like OMDb) for real data
