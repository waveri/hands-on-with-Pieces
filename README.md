```markdown
# 🕌 Taj Mahal Fun Facts

A beautifully designed, interactive web app that displays random **fun facts** about the Taj Mahal with options to share them on **Twitter** and **LinkedIn**.  
Built using **HTML**, **CSS**, and **JavaScript**, with a glassmorphism effect over a stunning background.

---

## ✨ Features

- 🎨 **Modern Glassmorphism UI** with background image & text overlay
- 📜 **Random fact generator** (no immediate repeats)
- 📱 **Responsive design** for all devices
- 🔄 **Social media sharing** for **Twitter** and **LinkedIn**
- 🧠 Pre-filled **Taj Mahal facts** stored in a JavaScript array
- 🎯 Maintains readability with a **dark gradient overlay**
- ⚡ Instant fact display on page load

---

## 📸 Preview

![Taj Mahal Fun Facts Screenshot](https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1200&q=80)

---

## 📂 Project Structure

```
.
├── index.html    # Main HTML file – contains markup, styles, and scripts
└── README.md     # Project documentation
```

---

## 🚀 Getting Started

### 1️⃣ Clone or Download
```
git clone https://github.com/waveri/taj-mahal-fun-facts.git
cd taj-mahal-fun-facts
```

### 2️⃣ Open in Browser
Simply double-click `index.html`  
*(No server required)*

---

## 🛠 Customization

### ✏ Change Facts
Facts are stored in the `facts` array in the `` tag of **index.html**:
```
const facts = [
  { fact: "The Taj Mahal changes color..." },
  { fact: "The minarets are slightly tilted..." }
];
```
Add, edit, or remove facts as needed.

### 🎨 Change Background
In the `` section, update the `background` URL in the `body` selector:
```
background:
  linear-gradient(rgba(30,30,30,0.6), rgba(30,30,30,0.6)),
  url('YOUR_NEW_IMAGE_URL') center/cover no-repeat;
```

---

## 📤 Social Media Sharing

- **Twitter** → Shares the selected fact with hashtags `#TajMahal #FunFact`
- **LinkedIn** → Shares the page link & fact as the title

---

## 📱 Responsive Design

- Fully supports **mobiles**, **tablets**, and desktops
- Uses `@media` queries for font & spacing adjustments

---

## 📜 License
This project is open source under the [MIT License](LICENSE).

---

## 💡 Inspiration
The Taj Mahal is one of the **Seven Wonders of the World**, and this project is a fun way to learn more about it while appreciating a clean, modern UI.

---

> 🖌 Designed with love using **HTML + CSS + JavaScript** and a touch of **glassmorphism magic**.
```
