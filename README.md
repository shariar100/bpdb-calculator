# BPDB LT-A Electricity Cost Calculator

A modern, responsive, and bilingual (EN/BN) electricity bill calculator for BPDB Residential Prepaid Meter users.  
Supports slab editing, bill history, export, and official tariff updates.

---

## ✨ Features

- **EN/BN Language Toggle**  
  Switch seamlessly between English and Bangla. All labels, notes, tables, and buttons are translated instantly.

- **Official Tariff Slab Support**  
  Default slabs reflect the BPDB official rates as of February 2024.  
  _You can edit, add, or reset slabs as needed._

- **Customizable Extra Charges**  
  - VAT (%)
  - Rebate (%)
  - Meter Rent (Tk)
  - Demand Charge (Tk)
  - Enable/disable and set custom values for each

- **Clear Cost Breakdown**  
  Displays:  
  - Energy Cost
  - VAT
  - Rebate
  - Meter Rent
  - Demand Charge
  - Total, per-day, and per-unit averages

- **Calculation History**  
  Saves your last 20 calculations (in your browser).  
  Clear history with one click.

- **Export & Share**  
  - Download as PDF or Image
  - Print-friendly
  - Share to Facebook, Twitter, WhatsApp, or Email

- **Responsive Design**  
  Looks great on desktop and mobile.

---

## 🚀 Live Demo

[Try it now &rarr;](https://shariar100.github.io/bpdb-calculator/)

---

## 🛠 Usage

1. **Clone or Download**
    ```sh
    git clone https://github.com/shariar100/bpdb-calculator.git
    cd bpdb-calculator
    ```

2. **Open `index.html`**  
   Double-click to use locally, or deploy to GitHub Pages/Netlify/etc.

---

## 📝 How to Use

- **Select Language:**  
  Use the EN/BN toggle at the top right.

- **Input Units & Days:**  
  - Enter _total units consumed (kWh)_.
  - Enter _number of days in billing period_.

- **Customize Extra Charges:**  
  Toggle and set VAT, Rebate, Meter Rent, and Demand Charge as needed.

- **Edit Slabs:**  
  - Click **Edit Slabs** to add/remove/customize tariff slabs.
  - **Reset** returns to official defaults.

- **View Results:**  
  Cost summary and full breakdown appear after calculation.

- **Export & History:**  
  - Use the PDF, Image, and Print buttons below the results.
  - Your recent calculations are listed and can be cleared.

---

## 📦 File Structure

```
bpdb-calculator/
├── index.html      # Main application file (EN/BN bilingual, all logic in one file)
├── README.md       # This file
```

---

## 📣 Notes

- This tool is for **BPDB Residential Prepaid Meter** users.
- Rates are based on the **official February 2024 BPDB tariff**.
- Always verify the latest rates from [BPDB official sources](https://bpdb.gov.bd/).

---

## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

[MIT](LICENSE)