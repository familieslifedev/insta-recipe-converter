# Insta-Recipe Converter 🍴

**Insta-Recipe Converter** is a dynamic and user-friendly app designed to simplify cooking and grocery shopping. Scale recipes effortlessly, toggle between metric and imperial units, and generate shopping lists—all in one place!

---

## Features ✨
- **Serving Size Selector**: Adjust the number of servings and watch the ingredients scale automatically.
- **Shopping List Generator**: Convert your recipe ingredients into a grocery-friendly format with an export option (PDF or text).
- **Unit Conversion**: Toggle between metric and imperial units for your recipes, with accurate conversions.
- **Clean UI**: Simple, modern interface for a smooth user experience.

---

## Tech Stack 🛠️

- **Frontend**:
  - React (via Create React App)
  - CSS (or your preferred styling approach)
- **Libraries**:
  - [jsPDF](https://github.com/parallax/jsPDF) for generating shopping list PDFs.
  - Fraction.js (for handling fractions in measurements).
- **Optional Backend**:
  - Node.js with Express (if you need an API for additional features).

---

## Installation & Setup 🚀

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/insta-recipe-converter.git
   cd insta-recipe-converter
   ```

2. **Install Dependencies**:
   Make sure you have [Node.js](https://nodejs.org/) installed. Then run:
   ```bash
   npm install
   ```

3. **Start the Development Server**:
   ```bash
   npm start
   ```
   This will launch the app in your browser at `http://localhost:3000`.

4. **Build for Production** (optional):
   If you’re ready to deploy:
   ```bash
   npm run build
   ```

---

## Usage 👩‍🍳

1. **Adjust Servings**:
   - Use the serving size input to scale your recipe.
   - Watch ingredient quantities update dynamically.

2. **Generate a Shopping List**:
   - Click the "Generate Shopping List" button to see your ingredients in a clean, easy-to-read format.
   - Export the list as a PDF or plain text.

3. **Switch Units**:
   - Toggle between metric and imperial units based on your region or preference.

---

## Project Structure 📂

```plaintext
src/
├── components/          # Reusable UI components
│   ├── ServingSizeSelector.js
│   ├── IngredientList.js
│   ├── ShoppingList.js
│   └── UnitToggle.js
├── utils/               # Helper functions
│   ├── unitConversions.js
│   ├── ingredientScaler.js
│   └── pdfGenerator.js
├── App.js               # Main app component
└── index.js             # Entry point
```

---

## Roadmap 🗺️

### Planned Features:
- **Recipe Importer**: Upload recipes from popular cooking sites.
- **Ingredient Categorization**: Group ingredients by sections (e.g., produce, dairy).
- **User Accounts**: Save and manage your favorite recipes.

---

## Contributing 💡

We love contributions! If you’d like to add a feature or improve the app, feel free to fork the repo and submit a pull request. Be sure to follow these steps:

1. Fork the project.
2. Create your feature branch:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some amazing feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a pull request.

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements ❤️
- Inspired by the joy of cooking and simplifying meal prep.
- Built with love by me. 🥰
