# coding-project-template
🌿 Paradise Nursery – Online Plant Shopping Cart

Welcome to Paradise Nursery, an online plant shopping application where customers can explore and purchase a variety of beautiful indoor and outdoor plants.

The application provides a simple and interactive shopping experience, allowing users to browse plants by category, add plants to their shopping cart, manage quantities, and calculate their total purchases.

🌐 Live Demo: Visit Paradise Nursery

✨ Features
Browse Plants: Explore a variety of plants organized into different categories.
Plant Information: View plant images, descriptions, and prices.
Add to Cart: Add selected plants to your shopping cart.
Cart Notifications: See the total number of items displayed on the shopping cart icon.
Quantity Management: Increase or decrease the quantity of plants.
Subtotal Calculation: Automatically calculate the subtotal for each plant.
Total Price Calculation: Automatically calculate the overall shopping cart amount.
Remove Items: Delete plants from the shopping cart.
Add to Cart Feedback: The button changes to "Added to Cart" after adding a plant.
Continue Shopping: Return to the plant listing page from the shopping cart.
🛠️ Technologies Used
React.js
JavaScript (ES6+)
Redux Toolkit
React Redux
HTML5
CSS3
Vite
Git and GitHub
GitHub Pages
📂 Project Structure
text
e-plantShopping/
│
├── public/
│
├── src/
│   ├── components/
│   ├── App.jsx
│   ├── main.jsx
│   ├── ProductList.jsx
│   ├── ProductList.css
│   ├── CartItem.jsx
│   ├── CartItem.css
│   ├── CartSlice.jsx
│   ├── store.js
│   └── index.css
│
├── index.html
├── package.json
├── vite.config.js
└── README.md


Note: The project structure may vary depending on how the components are organized.

🚀 Getting Started

Follow these instructions to run the project locally.

1. Clone the repository
bash
git clone https://github.com/whitebeardpirates439-netizen/e-plantShopping.git

2. Navigate to the project directory
bash
cd e-plantShopping

3. Install dependencies
bash
npm install

4. Start the development server
bash
npm run dev


Open the local URL displayed in your terminal to view the application.

🛒 Shopping Cart Functionality

The shopping cart uses Redux Toolkit to manage application state.

The Redux slice includes the following actions:

Action	Description
addItem	Adds a plant to the cart
incrementItem	Increases plant quantity
decrementItem	Decreases plant quantity
removeItem	Removes a plant from the cart
updateQuantity	Updates the quantity of a plant

The application automatically updates item quantities, individual subtotals, the overall cart total, and the shopping cart count whenever the cart changes.

🌍 Deployment

This project is deployed using GitHub Pages.

To create a production build:

bash
npm run build


To deploy the application:

bash
npm run deploy


The Vite configuration uses the following base path:

javascript
base: '/e-plantShopping/'

📸 Application Preview

Visit the live application:

🌱 Paradise Nursery – Live Website

🎯 Project Objective

The main objective of this project is to demonstrate practical knowledge of React development, component-based architecture, Redux state management, event handling, and deployment using GitHub Pages.

👨‍💻 Author

GitHub: whitebeardpirates439-netizen

📄 License

This project is created for educational and learning purposes.
