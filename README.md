# 🍽️ Recipe Finder App

A simple and responsive web application that helps users discover recipes from around the world. Search for meals by name, explore recipe details, view ingredients and cooking instructions, and watch cooking videos when available.

## ✨ Features

- **Search Recipes:** Find meals by entering a recipe name or keyword.
- **Recipe Cards:** View matching recipes with their images, names, and categories.
- **Recipe Details:** Click a recipe to explore its full details.
- **Ingredients List:** View ingredients along with their required measurements.
- **Cooking Instructions:** Read step-by-step recipe instructions.
- **YouTube Videos:** Open available cooking videos directly from the recipe details.
- **Error Handling:** Displays helpful messages when the search field is empty, no recipes are found, or a request fails.
- **Responsive Layout:** Adapts the recipe grid and search interface to smaller screens.
- **External API Integration:** Retrieves recipe data dynamically from TheMealDB API.

## 🛠️ Technologies Used

- **HTML5** — Application structure and content.
- **CSS3** — Styling, responsive layouts, animations, and visual design.
- **JavaScript (ES6+)** — Search functionality, API requests, and dynamic content rendering.
- **TheMealDB API** — Recipe data, ingredients, instructions, images, and video links.
- **Font Awesome 6** — Icons used throughout the interface.

## 📸 Application Overview

The application provides a straightforward way to discover recipes:

1. Enter a meal name or keyword in the search box.
2. Click **Search** or press **Enter**.
3. Browse the matching recipe cards.
4. Click a recipe to view its ingredients and cooking instructions.
5. Watch the associated YouTube video if one is available.
6. Use **Back to recipes** to return to the recipe results.

## 📂 Project Structure

```text
recipe-finder-app/
│
├── index.html     # Main HTML structure
├── style.css      # Application styling
├── script.js      # Search logic and API integration
└── README.md      # Project documentation
```

## 🚀 Getting Started

### Prerequisites

You only need a modern web browser and an internet connection. No API key or backend server is required for the current implementation.

### Installation

**1. Clone the repository**

Replace `YOUR-USERNAME` with your GitHub username and `YOUR-REPOSITORY` with your repository name.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

**2. Open the project folder**

```bash
cd YOUR-REPOSITORY
```

**3. Run the application**

Open `index.html` in your web browser.

For a smoother development experience, you can also open the folder in Visual Studio Code and run the page using the Live Server extension.

**4. Search for recipes**

Enter a meal name, such as `chicken`, `pasta`, or `cake`, and explore the results.

## 🔌 API Integration

This project uses [TheMealDB API](https://www.themealdb.com/api.php) to retrieve recipe information.

The application uses these endpoints:

**Search for meals**

```text
https://www.themealdb.com/api/json/v1/1/search.php?s=chicken
```

**Retrieve a recipe by its ID**

```text
https://www.themealdb.com/api/json/v1/1/lookup.php?i=52772
```

The application fetches data using JavaScript's `fetch()` API and dynamically renders the results on the page.

## 🎯 Learning Objectives

This project demonstrates practical experience with:

- Structuring web pages using HTML.
- Creating responsive layouts with CSS Grid and Flexbox.
- Manipulating the DOM with JavaScript.
- Handling user input and browser events.
- Making asynchronous API requests using `async` and `await`.
- Working with JSON responses.
- Displaying dynamic data from an external API.
- Implementing basic error handling.
- Organizing a frontend project into separate files.

## 🔮 Future Improvements

Potential enhancements for future versions include:

- Filter recipes by category, cuisine, or ingredients.
- Add recipe favourites and a saved recipes section.
- Add a random recipe generator.
- Improve accessibility and keyboard navigation.
- Add loading indicators and more detailed error messages.
- Allow users to search by available ingredients.
- Improve recipe details presentation on mobile devices.

## 📄 Credits

- Recipe data provided by [TheMealDB](https://www.themealdb.com/api.php).
- Icons provided by [Font Awesome](https://fontawesome.com/).

## 👨‍💻 Author

Developed as a frontend web development project to practise HTML, CSS, JavaScript, DOM manipulation, and external API integration.

---

⭐ If you find this project useful, consider giving the repository a star!
