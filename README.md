
# 🏪 Multilingual Shopping Cart System - Tai Po

A complete static HTML application for multilingual shopping cart management designed for Tai Po, Hong Kong residents. This system supports English, Traditional Chinese, and Indonesian languages.

## 🚀 Quick Start

### Option 1: Use Pre-generated Sample Data
1. Open `sample-excel-generator.html` in your web browser
2. Click "Generate MasterDatabase.xlsx" to download the sample database
3. Open `shopping-cart.html` in your web browser
4. Load the downloaded Excel file using the file upload or drag & drop

### Option 2: Use Your Own Excel Data
1. Create an Excel file with the required 10-column structure (see below)
2. Open `shopping-cart.html` in your web browser
3. Load your Excel file using the file upload or drag & drop

## 📊 Excel File Structure

Your Excel file must have exactly 10 columns in this order:

| Column | Name | Description |
|--------|------|-------------|
| A | Toggle | Y/N - User's selection if item is needed |
| B | Item_EN | Item name in English |
| C | Item_CN | Item name in Traditional Chinese |
| D | Item_ID | Item name in Indonesian |
| E | Store_EN | Store name in English |
| F | Store_CN | Store name in Traditional Chinese |
| G | Store_ID | Store name in Indonesian |
| H | Address_EN | Store address in English |
| I | Address_CN | Store address in Traditional Chinese |
| J | Address_ID | Store address in Indonesian |

## ✨ Features

### 🌍 Multilingual Support
- **English**: Full interface and data display
- **Traditional Chinese (中文)**: Complete Chinese localization
- **Indonesian (Bahasa)**: Full Indonesian translation

### 🛒 Shopping Cart Management
- Add items to cart with quantity controls
- Edit quantities using +/- buttons or direct input
- Remove individual items from cart
- View cart summary with store grouping

### 🔍 Search & Filter
- Real-time search across item names, store names, and addresses
- Instant filtering as you type
- Search works in all three languages

### 💾 Data Persistence
- Auto-save cart to browser's local storage
- Manual save/load cart functionality
- Cart data persists between browser sessions

### 🖨️ Print-Ready Shopping Lists
- Generate organized shopping lists grouped by store
- Include store addresses for easy navigation
- Print-optimized layout with clean formatting

### 📱 Responsive Design
- Mobile-friendly interface
- Works on tablets and desktop computers
- Touch-friendly controls for mobile devices

### 📁 File Handling
- Excel file upload via file picker
- Drag & drop Excel file support
- Error handling for invalid file formats
- Support for .xlsx and .xls formats

## 🏪 Sample Stores & Items

The sample database includes authentic Tai Po, Hong Kong locations:

### Supermarkets
- **PARKnSHOP (百佳超級市場)** - Uptown Plaza
- **Wellcome (惠康超級市場)** - Tai Wo Estate

### Pharmacies
- **Watsons (屈臣氏)** - Uptown Plaza
- **Guardian Pharmacy (屈臣氏藥房)** - Uptown Plaza

### Markets & Specialty Stores
- **Tai Po Market (大埔墟街市)** - Traditional wet market
- **Fresh Fruit Shop (新鮮水果店)** - Kwong Fuk Road
- **ManHing Hong Grocery (萬興行雜貨店)** - Traditional grocery

### Convenience Stores
- **7-Eleven** - Tai Wing Lane
- **Circle K (OK便利店)** - On Tai Road

### Bakeries
- **Maxim's Bakery (美心西餅)** - Uptown Plaza

### Hardware
- **Tai Po Hardware Store (大埔五金店)** - Plover Cove Road

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
- Verify that column B (Item_EN) has data in all rows

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

This shopping cart system was specifically designed for the multilingual community in Tai Po, Hong Kong, where residents often speak Cantonese, English, and various Southeast Asian languages. The system bridges language barriers while providing practical functionality for everyday shopping needs.

**Made with ❤️ for the Tai Po community**
