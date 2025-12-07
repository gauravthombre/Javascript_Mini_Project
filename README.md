Here is a **clean, professional, ready-to-paste README.md** for your repository:

---

# 🚀 JavaScript Mini Project – Bulb ON/OFF & Cat Eyes

This is a beginner-friendly **JavaScript DOM Manipulation mini-project** that toggles a bulb ON/OFF and changes the cat image accordingly.
It demonstrates how to update images, text, and button styles dynamically using JavaScript.

Live Demo 👉 **[https://gauravthombre.github.io/Javascript_Mini_Project/](https://gauravthombre.github.io/Javascript_Mini_Project/)**

---

## 🖼️ Preview

The project displays:

* A bulb that turns **ON/OFF**
* A cat image that switches to **glowing eyes** when bulb is OFF
* ON/OFF buttons that dynamically change colors
* Status text that updates in real-time

---

## ✨ Features

* 🔘 ON/OFF toggle for bulb
* 🐱 Cat image changes when lights go off
* 🎨 Tailwind CSS UI
* ⚡ Live DOM manipulation
* 🧩 Clean & beginner-friendly code
* 📱 Fully responsive

---

## 🛠️ Tech Stack

| Technology          | Used For         |
| ------------------- | ---------------- |
| **HTML5**           | Structure        |
| **CSS3 / Tailwind** | Styling          |
| **JavaScript**      | DOM manipulation |

---

## 📂 Folder Structure

```
Javascript_Mini_Project/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

💡 How It Works

1. switchOff()

* Changes bulb to OFF image
* Changes cat to glowing-eyes image
* Updates button colors
* Updates text to “Switched Off”

2. switchON()

* Changes bulb to ON image
* Restores cat image
* Updates status text
* Restores button colors

---

## 🧪 Code Example

### JavaScript

```js
function switchOff() {
    document.getElementById("bulbImage").src =
        "https://d2clawv67efefq.cloudfront.net/ccbp-dynamic-webapps/bulb-go-off-img.png";
    document.getElementById("catImage").src =
        "https://d2clawv67efefq.cloudfront.net/ccbp-dynamic-webapps/cat-eyes-img.png";
    document.getElementById("switchStatus").textContent = "Switched Off";
    document.getElementById("OffSwitch").style.backgroundColor = "#cbd2d9";
    document.getElementById("OnSwitch").style.backgroundColor = "#22c55e";
}

function switchON() {
    document.getElementById("bulbImage").src =
        "https://d2clawv67efefq.cloudfront.net/ccbp-dynamic-webapps/bulb-go-on-img.png";
    document.getElementById("catImage").src =
        "https://d2clawv67efefq.cloudfront.net/ccbp-dynamic-webapps/cat-img.png";
    document.getElementById("switchStatus").textContent = "Switched On";
    document.getElementById("OffSwitch").style.backgroundColor = "#e12d39";
    document.getElementById("OnSwitch").style.backgroundColor = "#cbd2d9";
}
```

---

## 📌 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/gauravthombre/Javascript_Mini_Project
   ```

2. Open the folder

3. Double-click **index.html**

4. Project will open in your browser

---

🌐 Live Demo

🔗 [https://gauravthombre.github.io/Javascript_Mini_Project/](https://gauravthombre.github.io/Javascript_Mini_Project/)

---

🤝 Contribute

Contributions are welcome!
Feel free to open issues or submit PRs.

---
⭐ Show Support

If you like this project, give it a ⭐ on GitHub!


