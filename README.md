# GST Calculator Web App 💜

A modern, precision-engineered Goods and Services Tax (GST) calculator designed for professional environments. Experience lightning-fast computations wrapped in a stunning glassmorphism interface with intelligent dark/light mode switching.

## ✨ Features

- **Precision Calculation**: Flawlessly compute inclusive and exclusive GST amounts.
- **Smart History**: Automatically tracks and persists your recent calculations using LocalStorage.
- **Dynamic Theming**: True Material 3 Dark/Light mode integration that remembers your preference.
- **Bento Grid Layout**: Visually parsed breakdown of Base Value, CGST, SGST, IGST, and Total amounts.
- **Educational Guide**: Built-in reference for GST slabs and Input Tax Credit (ITC) mechanisms.
- **Copy & Save**: Instantly copy calculation results to your clipboard or save them to your active session history.

## 📖 How to Use

The GST Calculator is designed to be intuitive and fast. Follow these steps to perform your calculations:

### 1. Enter the Amount
Type your base or total amount into the **NET AMOUNT** field. The calculator updates in real-time as you type, so there's no need to hit a "calculate" button.

### 2. Select Calculation Type
Choose how the tax should be applied:
- **Inclusive**: Select this if your entered amount *already includes* GST. The calculator will extract the tax amount to show you the original base value.
- **Exclusive**: Select this if your entered amount *does not include* GST. The calculator will add the tax on top of your entered amount.

### 3. Choose the GST Rate
Click on one of the standard Indian GST slabs: **5%**, **12%**, **18%**, or **28%**. 

### 4. Review the Breakdown
The Bento Grid instantly displays the computed values:
- **Base Value**: The price of the goods/services without tax.
- **CGST & SGST**: The Intra-state tax split (Central and State GST), each taking exactly half of the selected rate.
- **IGST**: The Inter-state tax, taking the full selected rate.
- **Total Amount**: The final price including all taxes.

### 5. Save and Export
- **Copy Results**: Click this button to instantly copy a formatted text summary of your calculation to your clipboard (perfect for pasting into invoices, chats, or emails).
- **Save Calculation**: Click this button to save the current calculation to your **History** log below. It will be stored securely in your browser so you won't lose it if you close or refresh the tab.

## 🚀 Quick Start

Since this is a standalone web application, there is no build process or complex setup required! 

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gst-calc.git
   ```
2. Open `index.html` in any modern web browser.
3. Start calculating!

## 🛠️ Technology Stack

- **HTML5**: Semantic structure.
- **Tailwind CSS (via CDN)**: Utility-first styling with custom Material Design 3 variables.
- **Vanilla JavaScript**: Lightweight and zero-dependency DOM manipulation and logic.

## 📐 Design Philosophy

The application prioritizes **Aesthetics and Usability**. Leveraging high-contrast typography (Space Grotesk & Geist), neon accents against deep dark surfaces, and subtle micro-animations (bouncy interactions) to create a premium feel that wows the user on every click. 

## 📝 License

Distributed under the MIT License.
