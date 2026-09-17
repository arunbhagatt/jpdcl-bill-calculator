# ⚡ JPDCL Bill Calculator

A modern, mobile-friendly electricity bill estimator for JPDCL consumers.

The calculator supports both **Residential** and **Commercial** connections and automatically applies the corresponding tariff structure.

---

## 🌐 Live Website

https://arunbhagatt.github.io/jpdcl-bill-calculator/

---

## ✨ Features

- 🏠 Residential bill calculation
- 🏢 Commercial bill calculation
- ⚡ Slab-wise energy charge calculation
- 🧾 Fixed charge calculation based on sanctioned load
- 📊 Electricity Duty (ED) calculation
- 💰 Detailed bill breakdown
- 📱 Mobile-friendly responsive design
- 📲 Installable as an Android app (PWA)
- 🚀 Fast and lightweight
- 🌐 Works directly in the browser
- 🔄 Switch between Residential and Commercial connections

---

## 🧮 How It Works

The calculator first asks the user to select the **Connection Type**:

- 🏠 Residential
- 🏢 Commercial

After selecting the connection type, the user enters:

- Units consumed
- Sanctioned load in kW

The calculator then automatically applies the relevant tariff structure and displays the estimated bill.

---

# 🏠 Residential Tariff

## Energy Charges

| Units | Rate |
|-------|------|
| 0 – 200 | ₹2.45/unit |
| 201 – 400 | ₹4.20/unit |
| Above 400 | ₹4.60/unit |

## Fixed Charges

```text
Sanctioned Load × ₹10
```

Default sanctioned load:

```text
2 kW
```

## Electricity Duty

```text
15% of Total Energy Charges
```

## Total Bill

```text
Energy Charges
+ Fixed Charges
+ Electricity Duty
```

---

# 🏢 Commercial Tariff

## Energy Charges

| Units | Rate |
|-------|------|
| 0 – 200 | ₹3.75/unit |
| Above 200 | ₹5.70/unit |

## Fixed Charges

```text
Sanctioned Load × ₹75
```

Default sanctioned load:

```text
2 kW
```

## Electricity Duty

```text
15% of Total Energy Charges
```

## Total Bill

```text
Energy Charges
+ Fixed Charges
+ Electricity Duty
```

---

## 📊 Commercial Calculation Example

For a commercial connection consuming:

```text
Units: 450
Sanctioned Load: 2 kW
```

The calculation is:

| Component | Calculation | Amount |
|-----------|-------------|--------|
| Slab 1 | 200 × ₹3.75 | ₹750.00 |
| Slab 2 | 250 × ₹5.70 | ₹1,425.00 |
| Total Energy Charges (A) | ₹750 + ₹1,425 | ₹2,175.00 |
| Fixed Charges (B) | 2 kW × ₹75 | ₹150.00 |
| Electricity Duty (C) | 15% of ₹2,175 | ₹326.25 |
| **Total Estimated Bill** | **A + B + C** | **₹2,651.25** |

---

## 📱 Install as an App

Open the website in **Google Chrome** and select:

```text
⋮ → Add to Home Screen
```

or:

```text
Install App
```

The calculator is built as a **Progressive Web App (PWA)** and can be used like an app on supported devices.

---

## ⚠️ Disclaimer

This is an **unofficial electricity bill estimator** and is not affiliated with JPDCL or the Government of Jammu & Kashmir.

The tariff rates used in the calculator are based on the tariff structure currently configured in this project.

Actual electricity bills may vary due to:

- Arrears
- Adjustments
- Tariff revisions
- Taxes or duties
- Subsidies
- Billing corrections
- Other applicable charges

Users should refer to their official electricity bill and applicable JPDCL tariff orders for the actual payable amount.

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- Progressive Web App (PWA)
- GitHub Pages

---

## 📁 Project Structure

```text
jpdcl-bill-calculator/
│
├── index.html
├── manifest.json
├── service-worker.js
└── README.md
```

---

## 👨‍💻 Developer

**Arun Bhagat**

📧 bhagat.arun702@gmail.com

---

## 📄 License

This project is created for **educational and utility purposes only**.

---

## ⭐ Support

If you find this calculator useful, consider giving the project a ⭐ on GitHub.
