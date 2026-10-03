# 🍞 Toast Notification Website

A simple and interactive **Toast Notification Website** built using **HTML, CSS, and JavaScript**. The project demonstrates how to create dynamic toast messages that appear on the screen, display different notification types, animate into view, and automatically disappear after a fixed duration.

The project uses **Font Awesome** icons to visually distinguish different notification messages.

---

## 📌 Overview

Toast notifications provide quick, non-blocking feedback to users after an action.

This project demonstrates a lightweight custom toast notification system where users can trigger different notification messages using buttons:

* ✅ Success
* ❌ Error
* ⚠️ Invalid Input

Each notification is dynamically created with JavaScript and automatically removed after **6 seconds**.

---

## ✨ Features

* **Success Notification** — Displays a successful submission message.
* **Error Notification** — Displays an error message.
* **Invalid Input Notification** — Displays an invalid-input message.
* **Dynamic Toast Creation** — Toast elements are created dynamically using JavaScript.
* **Automatic Dismissal** — Notifications are automatically removed after 6 seconds.
* **Animated Entrance** — Toasts slide into the screen using a CSS animation.
* **Font Awesome Icons** — Uses icons to visually represent notification types.
* **Multiple Notifications** — Toast messages are displayed inside a dedicated notification container.
* **Simple UI** — Minimal interface focused on demonstrating toast functionality.

---

## 🛠️ Technologies Used

| Technology       | Purpose                                          |
| ---------------- | ------------------------------------------------ |
| **HTML5**        | Page structure and notification buttons          |
| **CSS3**         | Styling, layout, animation, and toast appearance |
| **JavaScript**   | Dynamic toast creation and automatic removal     |
| **Font Awesome** | Notification icons                               |

---

## 📂 Project Structure

```text
Toast-Notification-Website/
│
├── index.html
├── script.js
├── style.css
└── README.md
```

---

## ⚙️ How It Works

### 1. User selects a notification type

The interface provides three buttons:

```text
Success
Error
Invalid
```

Each button calls the JavaScript `showToast()` function with the corresponding notification message.

### 2. JavaScript creates the toast

The `showToast()` function:

1. Creates a new `<div>` element.
2. Adds the `toast` CSS class.
3. Inserts the notification message and Font Awesome icon.
4. Adds the toast to the `#toastBox` container.
5. Applies additional styling based on the notification type.

### 3. Toast appears with animation

CSS applies an entrance animation that moves the toast from outside the right side of the screen into its visible position.

### 4. Toast is automatically removed

JavaScript uses `setTimeout()` to remove the notification after **6 seconds**:

```javascript
setTimeout(() => {
    toast.remove();
}, 6000);
```

This keeps the notification area clean without requiring the user to close each message manually.

---

## 🧠 JavaScript Concepts Practiced

This project provides practice with several important JavaScript concepts:

* DOM selection using `getElementById()`
* Creating elements with `createElement()`
* Adding CSS classes using `classList`
* Updating HTML using `innerHTML`
* Adding elements using `appendChild()`
* Conditional logic with `if`
* String checking using `includes()`
* Timers using `setTimeout()`
* Removing DOM elements dynamically
* JavaScript functions
* Inline event handling

---

## 🎨 UI & Animation

The toast notification container is positioned in the **bottom-right corner** of the page.

Each toast:

* Has a fixed width and height.
* Uses a white background.
* Includes a shadow for visual separation.
* Contains an icon and message.
* Starts outside the visible area.
* Slides into view using a CSS `@keyframes` animation.

The project also uses different CSS classes for notification types such as:

```text
.toast
.error
.invalid
```

---

## 🔔 Notification Types

### Success

Displays:

> Successfully submitted

Uses a success/check icon.

### Error

Displays:

> Please fix the error!

Uses an error/cross icon.

### Invalid

Displays:

> Invalid input, check again

Uses an exclamation icon.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/KhushiChaubey-493/Toast-Notification-Website.git
```

### 2. Open the project

Navigate into the project directory:

```bash
cd Toast-Notification-Website
```

### 3. Run the project

Open:

```text
index.html
```

in your web browser.

No build tools or backend server are required.

---

## 📸 Project Preview

You can add a screenshot of the project here once you have a screenshot available in the repository:

```markdown
![Toast Notification Website Screenshot](screenshot.png)
```

---

## 🔮 Possible Future Improvements

The current project focuses on the basic toast notification functionality. Some possible improvements include:

* Add a close button to each toast.
* Add customizable notification duration.
* Add more notification types such as Warning and Information.
* Add progress bars showing remaining notification time.
* Add responsive styling for smaller screens.
* Support multiple toast positions.
* Add smooth exit animations.
* Prevent excessive toast notifications from overlapping.
* Convert the toast functionality into a reusable JavaScript component.

---

## 🎯 Learning Objectives

This project was created to practice:

* DOM manipulation
* JavaScript event handling
* Dynamic HTML element creation
* CSS animations
* Timers and delayed execution
* Conditional styling
* Third-party icon integration
* Building interactive frontend components

---

## 📌 Project Status

**Status:** Completed

This project is a frontend practice project focused on implementing a custom toast notification interface using vanilla JavaScript.

---

## 👩‍💻 Author

**Khushi Chaubey**

GitHub:
https://github.com/KhushiChaubey-493

---

## 📄 License

This project is available for educational and personal use.
