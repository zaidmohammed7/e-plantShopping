# Paradise Nursery Shopping Application

## Project Overview

In this project, I developed a **Paradise Nursery Shopping Application**. The application allows users to browse and purchase plants from different categories, such as Aromatic and Medicinal Plants. It features an interactive shopping cart and demonstrates state management using **Redux**.

This project highlights modern front-end development techniques, including component-based architecture, state management, and event handling, providing a real-world example of creating dynamic and responsive web applications.

### Key Features:
- **Landing Page:** A welcome page with navigation links to explore plants and view the shopping cart.
- **Product Listing Page:** 
  - Displays plant cards with images, descriptions, and costs.
  - Categorizes plants into sections (e.g., Aromatic and Medicinal Plants).
  - "Add to Cart" functionality for each plant.
- **Shopping Cart Page:** 
  - Displays a summary of all items added to the cart.
  - Allows users to adjust quantities, view subtotals, remove items, and calculate the total cost.
  - Features "Continue Shopping" and "Checkout" buttons for improved user flow.
- **State Management:** Managed global state with **Redux** for adding, updating, and removing items in the shopping cart.

---

## Skills Demonstrated

- **React Development:**
  - Built reusable and functional React components.
  - Utilized **React Hooks** (`useState`, `useEffect`) for managing component-level state.
- **Redux Integration:**
  - Implemented global state management using **Redux Toolkit**.
  - Created reducers and actions for handling cart operations like adding, removing, and updating items.
- **Dynamic Data Rendering:**
  - Mapped over an array of plant objects to dynamically render product cards and cart items.
- **Event Handling:** 
  - Developed functions to handle "Add to Cart," increment/decrement item quantities, and remove items.
- **GitHub & Version Control:** Managed the entire project through Git and GitHub for version control and deployment.

---

## Project Setup and Installation

You can view the application [here](https://zaidmohammed7.github.io/e-plantShopping/)

Alternatively, if you want to modify the code and run the app locally, follow these steps:
### Clone the Repository
To set up this project locally, follow these steps:

1. **Clone this repository:**

    ```bash
    git clone https://github.com/zaidmohammed7/e-plantShopping.git
    cd e-plantShopping
    ```

2. **Install required dependencies:**

    ```bash
    npm install
    ```

3. **Run the Application:**

    To start the application locally, run:

    ```bash
    npm run preview
    ```

    The application will be accessible at the provided localhost port (`http://localhost:4173`).

---

## Application Pages

### Landing Page
A welcoming page featuring a "Get Started" button to explore plants and a navigation bar with links to:
- **Home:** Redirects to the landing page.
- **Plants:** Navigates to the product listing page.
- **Cart:** Displays items in the shopping cart.

### Product Listing Page
Displays a grid of plant cards, each containing:
- Image, name, description, and cost.
- "Add to Cart" button to add plants to the shopping cart.

### Shopping Cart Page
Displays all items added to the cart with:
- Subtotals for each item based on quantity.
- Buttons to increment/decrement quantities and remove items.
- Total cost of all items in the cart.
- "Continue Shopping" and "Checkout" buttons.

---

## Acknowledgements

- The course *"Developing Front-End Apps with React"*, offered by **IBM** through **Coursera**.
  You can find more details about the course [here](https://www.coursera.org/learn/developing-frontend-apps-with-react).
- Special thanks to the **IBM Developer Skills Network** for providing the foundational project structure and guidance.

---
