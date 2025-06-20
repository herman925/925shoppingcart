# 🏪 925's Shopping Cart System

This is a multilingual shopping cart application. It is a static HTML file. It was made by Herman925. It helps you manage shopping lists. It supports English, Chinese, and Indonesian.

## 🚀 Quick Start

### Option 1: Use Pre-generated Sample Data
1.  Open `sample-excel-generator.html` in your web browser.
2.  Click "Generate MasterDatabase.xlsx" to download the sample database.
3.  Open `shopping-cart.html` in your web browser.
4.  Load the downloaded Excel file using the "Load Excel Database" button or by dragging and dropping the file onto the designated area.

### Option 2: Use Your Own Excel Data
1.  Create an Excel file with the required 11-column structure (see below).
2.  Open `shopping-cart.html` in your web browser.
3.  Load your Excel file.

### Option 3: Load from Google Sheets
1. Open `shopping-cart.html`.
2. Click the "Load from Google Sheet" button.
3. Enter the URL of your public Google Sheet when prompted. The sheet must follow the 11-column structure.

## 📊 Excel File & Google Sheet Structure

Your data source must have exactly 10 columns in this order:

| Column | Name         | Description                               |
|--------|--------------|-------------------------------------------|
| A      | Item_EN      | Item name in English                      |
| B      | Item_CN      | Item name in Traditional Chinese          |
| C      | Item_ID      | Item name in Indonesian                   |
| D      | Category     | The category of the item (e.g., "Food & Grocery", "Household") |
| E      | Store_EN     | Store name in English                     |
| F      | Store_CN     | Store name in Traditional Chinese         |
| G      | Store_ID     | Store name in Indonesian                  |
| H      | Address_EN   | Store address in English                  |
| I      | Address_CN   | Store address in Traditional Chinese      |
| J      | Address_ID   | Store address in Indonesian               |

## ✨ Features

### 🌍 Multilingual Support
-   **English**: Full interface and data display.
-   **Traditional Chinese (中文)**: Complete Chinese localization.
-   **Indonesian (Bahasa Indonesia)**: Full Indonesian translation.

### 🛒 Shopping Cart Management
-   Add items to the cart with quantity controls.
-   Edit quantities using +/- buttons or by direct input.
-   Remove individual items from the cart.
-   View a clear cart summary with items grouped by store.
-   Clear the entire cart with a single click.

### 🔍 Search & Filter
-   **Real-time Search**: Instantly search across item names, store names, and addresses in any of the supported languages.
-   **Category & Shop Filtering**: Filter the item list by specific categories or shops to quickly find what you need.

### 💾 Data Persistence
-   **Auto-save**: The cart is automatically saved to the browser's local storage.
-   **Manual Save/Load**: Manually save your current cart to a file and load it back later.
-   **Session Persistence**: Your cart data persists even after closing the browser.

### 🖨️ Print-Ready Shopping Lists
-   **Bilingual Printing**: Select any two languages to display side-by-side on your printed list.
-   **Organized Layout**: Generates a clean, print-optimized shopping list with items grouped by store.
-   **Store Addresses Included**: The list includes store addresses for easy navigation.

### 📁 Flexible Data Loading
-   **Excel File Upload**: Load data from `.xlsx` or `.xls` files using a file picker.
-   **Drag & Drop**: Easily drag and drop your Excel file into the application.
-   **Google Sheets Integration**: Load your shopping database directly from a public Google Sheet.
-   **Error Handling**: The system provides feedback for invalid file formats or data structures.

### 📱 Responsive Design
-   The application has a responsive interface. It is mobile-friendly and works on desktops, tablets, and smartphones.

## 🏪 Sample Stores & Items

The sample database includes items from authentic locations in Tai Po, Hong Kong:

### Supermarkets
-   **PARKnSHOP (百佳超級市場)** - Uptown Plaza
-   **Wellcome (惠康超級市場)** - Tai Wo Estate

### Pharmacies
-   **Watsons (屈臣氏)** - Uptown Plaza
-   **Guardian Pharmacy (屈臣氏藥房)** - Uptown Plaza

### Markets & Specialty Stores
-   **Tai Po Market (大埔墟街市)** - Traditional wet market
-   **Fresh Fruit Shop (新鮮水果店)** - Kwong Fuk Road
-   **ManHing Hong Grocery (萬興行雜貨店)** - Traditional grocery

### Convenience Stores
-   **7-Eleven** - Tai Wing Lane
-   **Circle K (OK便利店)** - On Tai Road

### Bakeries
-   **Maxim's Bakery (美心西餅)** - Uptown Plaza

### Hardware
-   **Tai Po Hardware Store (大埔五金店)** - Plover Cove Road

## 🛠️ Technical Requirements

- **No Installation Required**: Just double-click the HTML file
- **Modern Web Browser**: Chrome, Firefox, Safari, or Edge
- **JavaScript Enabled**: Required for functionality
- **Local Storage**: For cart persistence (enabled by default)

## 📋 Typical Household Items Included

The sample database includes items a typical housewife would buy:

### Food & Groceries
- Rice, noodles, bread, milk
- Fresh vegetables (bok choy, cabbage, ginger)
- Fresh meat and fish
- Cooking essentials (oil, soy sauce, herbs)

### Household Supplies
- Cleaning products (dish soap, detergent)
- Paper products (toilet paper, kitchen towels)
- Storage (garbage bags)

### Personal Care
- Health items (shampoo, toothpaste, medicine)
- Basic medical supplies (band-aids, vitamins)

### Convenience Items
- Snacks, drinks, ready-to-eat meals
- Bakery items (bread, pastries, cakes)

## 🎯 Perfect For

- **Housewives** planning shopping trips in Tai Po
- **Multilingual families** needing multiple language support
- **Organized shoppers** who want to group purchases by store
- **Mobile users** shopping on-the-go
- **Anyone** wanting a simple, effective shopping list tool

## 💡 Usage Tips

1. **Load Sample Data First**: Use the sample Excel generator to get familiar with the system
2. **Search is Powerful**: Use the search box to quickly find items across all languages
3. **Group by Store**: The print function automatically organizes your list by store location
4. **Save Your Cart**: Use the save function to preserve your shopping list between sessions
5. **Language Switching**: Switch languages anytime - your cart data is preserved

## 🔧 Customization

To add your own stores and items:
1. Follow the exact 10-column Excel structure
2. Include accurate translations for all three languages
3. Use real store addresses for better navigation
4. Keep item names concise but descriptive

## 📄 File Structure

```
shopping-cart-app/
├── shopping-cart.html          # Main application
├── sample-excel-generator.html # Sample data generator
└── README.md                   # This documentation
```

## 🆘 Troubleshooting

**Excel file won't load?**
- Check that your file has exactly 10 columns
- Ensure the file is in .xlsx or .xls format
- Verify that column A (Item_EN) has data in all rows

**Cart not saving?**
- Check that your browser allows local storage
- Try clearing browser cache and reload

**Search not working?**
- Make sure you've loaded an Excel file first
- Try searching in different languages

**Print layout issues?**
- Use Print Preview to check formatting
- Ensure your browser's print settings are correct

## 🌟 Why This System?

This system is for the multilingual community in Tai Po, Hong Kong. People there speak many languages. This app helps them shop by bridging language barriers.

**Made with ❤️ for the Tai Po community**
