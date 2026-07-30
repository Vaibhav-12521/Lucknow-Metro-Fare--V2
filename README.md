
# 🚇 Lucknow Metro Fare Calculator

A sleek, modern, and interactive web application for calculating metro fares between any two stations on the Lucknow Metro Red Line. Built with vanilla HTML, CSS, and JavaScript—this tool provides a smooth user experience with animations, gradients, and responsive design.

---

## 🔍 Features

* 🚉 **Select Starting and Destination Stations**
* 💰 **Instant Fare Calculation Based on Distance**
* ⏱ **Estimated Travel Time Calculation** 
* ✨ **Beautiful UI with Animated Backgrounds**
* 📱 **Responsive Design for Mobile Devices**
* ⚡ **Smooth UI Feedback with Loading Spinner**
* ❌ **Error Handling for Invalid Inputs**

---

## 🧮 Fare Calculation Logic

The fare is determined based on the number of stations between the start and destination:

| Number of Stations | Fare (₹) |
| ------------------ | -------- |
| 1                  | ₹10      |
| 2                  | ₹15      |
| 3 - 6              | ₹20      |
| 7 - 9              | ₹30      |
| 10 - 13            | ₹40      |
| 14 - 17            | ₹50      |
| 18+                | ₹60      |

Travel time is estimated at **2 minutes per station**.

---

## 🛠️ Tech Stack

* **HTML5** – Structure and markup
* **CSS3** – Styling and animations
* **JavaScript (ES6)** – Logic for fare calculation and interactivity

---

## 📂 Project Structure

```
/project-root
│
├── index.html         # Main HTML file
├── style.css          # Styling and animations
└── README.md          # This file
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Vaibhav-12521/Lucknow-Metro-Fare--V2.git
```
```bash
cd Lucknow-Metro-Fare--V2
```

### 2. Open in Browser

Simply open `index.html` in your preferred browser:

#### For Windows
```bash
start index.html       
```
#### For macs
```bash
open index.html       
```
#### For linux
```bash
xdg-open index.html    
```

> 💡 No dependencies or server required. It runs completely in the browser!

### 3. Run from GitHub Pages (Default URL)

Open the app directly using the default GitHub Pages URL:

```text
https://vaibhav-12521.github.io/Lucknow-Metro-Fare--V2/
```

---

## 🧪 Example Usage

1. Select **Starting Station** – e.g., *CCS Airport*
2. Select **Destination Station** – e.g., *Hazratganj*
3. Click **"Calculate Fare"**
4. See the **Fare & Travel Time** instantly displayed below the form.

---

## 📸 UI Highlights

* Smooth floating animations
* Particle and orb effects
* Neon-inspired gradients
* Blur effects for glassmorphism feel
* Responsive UI for mobile screens

---

## 📱 Responsive Design

The app is fully responsive and adjusts beautifully across:

* ✅ Mobile devices
* ✅ Tablets
* ✅ Desktop screens

---

## 🙌 Contributing

Want to add more features like route maps, fare history, or multi-line support? Contributions are welcome!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes
4. Push and create a PR

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✨ Credits

Developed with ❤️ by Vaibhav
