# e-plantShopping - Paradise Nursery

A modern, responsive React-based shopping cart application for Paradise Nursery, a boutique store specializing in aromatic, medicinal, and air-purifying plants.

## Features

- **Landing Page**: Engaging introduction with a 'Get Started' button.
- **Product Listing**: Categorized display of plants (Air Purifying, Aromatic, Medicinal, etc.).
- **Dynamic Shopping Cart**:
  - Add items to the cart with real-time budget tracking.
  - Cart quantity display in the navigation bar.
  - Increase/Decrease quantity with automatic total calculation.
  - Remove items from the cart.
  - "Continue Shopping" and mock "Checkout" functionality.
- **State Management**: Built using **Redux Toolkit** for robust and predictable state handling.
- **Responsive Design**: Elegant UI that adapts to various screen sizes.

## Tech Stack

- **Framework**: React 18
- **Build Tool**: Vite
- **State Management**: Redux Toolkit
- **Styling**: Vanilla CSS

## Installation and Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/[your-username]/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Run the development server**:

   ```bash
   npm run dev
   ```

4. **Open in browser**:
   Navigate to `http://localhost:5173` to view the application.

## Project Structure

- `src/App.jsx`: Main entry point handling navigation between landing and product pages.
- `src/ProductList.jsx`: Displays the categorized grid of plants.
- `src/CartItem.jsx`: Detailed cart view with item controls and totals.
- `src/CartSlice.jsx`: Redux logic for shopping cart state.
- `src/store.js`: Redux store configuration.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
