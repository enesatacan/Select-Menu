💻 Daily JavaScript App - Day 22: Select Menu

🌟 Part of my Daily JavaScript Coding Challenge, where I create a new JavaScript project every day! The aim? Sharpening my skills 🧠 and staying consistent in coding. 🚀

---
🎉 **Welcome to the Select Menu Project!**  
This interactive and dynamic project creates a dropdown select menu using JavaScript, HTML, and CSS. It's a great demonstration of working with the DOM, event listeners, and animations for modern web design.
---

## 🌟 **Features**

✅ **Dynamic Dropdown Menu:** Click to toggle a dropdown list of social media options.  
✅ **Customizable Selection:** Choose an option, and it updates the display dynamically.  
✅ **Smooth Animations:** Includes a rotating arrow icon for a polished look.  
✅ **User-Friendly Design:** Simple and clean interface for seamless interaction.  

---

## 🛠 **How It Works**

### **JavaScript Logic**

- **Dropdown Toggle:**  
  The dropdown menu is toggled using `.classList.toggle()` to add or remove the `hide` class.  
  ```javascript
  selectField.onclick = function () {
    list.classList.toggle("hide");
    arrowIcon.classList.toggle("rotate");
  };
  ```

- **Option Selection:**  
  When an option is clicked, the displayed text updates to match the selected item.  
  ```javascript
  for (option of options) {
    option.onclick = function () {
      selectText.innerHTML = this.textContent;
      list.classList.toggle("hide");
      arrowIcon.classList.toggle("rotate");
    };
  }
  ```

### **HTML Structure**

- **Selector:**  
  The selector contains a `div` with a dropdown field and an arrow icon. Clicking the field shows/hides the list of options.  
- **List Items:**  
  Each list item represents a social media platform with an icon and name.

### **CSS Animations**

- **Arrow Rotation:**  
  The arrow rotates 180° when the dropdown is toggled using the `rotate` class.

---

## 🚀 **Technologies Used**

- **HTML5:** Builds the structure of the dropdown menu.  
- **CSS3:** Styles the project and adds animations for a smooth user experience.  
- **JavaScript:** Provides dynamic functionality and user interaction.

---

## 📖 **How to Use**

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/enesatacan/Select-Menu.git
```

2️⃣ **Open the Project**  
Open the `index.html` file in your favorite browser.

3️⃣ **Interact with the Menu**  
Click the "Select Social Media" field, choose an option, and watch the selection update dynamically.

4️⃣ **Customize as You Like**  
- Edit the `style.css` file to change the appearance.  
- Add or modify the list items in `index.html` to include more options.  

---

## 📁 **Project Files**

- `index.html` – The structure of the Select Menu.  
- `style.css` – Styles the dropdown, icons, and animations.  
- `app.js` – Adds interactivity to the menu.

---

## 💡 **What I Learned**

This project enhanced my skills in:  
- Manipulating the DOM with JavaScript.  
- Adding interactivity through event listeners.  
- Creating reusable, user-friendly UI components.  

---


![image](https://github.com/user-attachments/assets/196d238e-ede1-40e9-8864-4edc33f407d6)
