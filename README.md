# neonsnaky
An immersive, modern take on the classic Snake game featuring a vibrant neon aesthetic, progressive difficulty levels, responsive mobile controls, and high-performance HTML5 Canvas rendering. Built with Vanilla JavaScript and Tailwind CSS.

# Neon Snaky - Infinite & Progressive Levels

Neon Snaky is a modern, visually striking interpretation of the classic arcade game. Built from scratch using Vanilla JavaScript and HTML5 Canvas, this version enhances the core gameplay with a mesmerizing neon aesthetic, a challenging level-based progression system, unique food mechanics, and fully responsive controls designed for both desktop and mobile web browsers.

**🎮 [LIVE DEMO LINK]**
*(Replace this with your live link, e.g., https://yourusername.github.io/neon-snake/)*

---

## ✨ Key Features

### 🌌 Immersive Visuals & Audio
* **Neon Aesthetic:** High-contrast glowing graphics rendered in dynamic teal, green, and red hues, creating a futuristic retro feel.
* **Dynamic Particles:** Interactive particle effects spawn upon eating food, enhancing visual feedback.
* **Retro Sound Effects:** Custom 8-bit style audio feedback for actions (eating, special food, game over) with a mute toggle functionality.

### 🕹️ Advanced Gameplay Mechanics
* **Progressive Difficulty (Levels 1-8):** As the player progresses through levels by reaching score milestones, the snake's speed increases automatically, escalating the challenge.
* **Normal & Special Food:**
  * **Normal Food (Neon Red):** Standard score and growth. Eating 7 spawns the Special Food.
  * **Special Big Food (Neon Teal/Gold):** High-reward food that appears temporarily. Its lifetime is dynamically calculated based on the current level speed, ensuring a balanced challenge across all levels.
* **Score Tracking:** Real-time display of Current Score, Current Level, and persistent High Score (using browser LocalStorage).

### 📱 Full Cross-Platform Compatibility
* **Responsive Layout:** The game canvas and UI elements adapt seamlessly to different screen sizes.
* **Hybrid Controls:** Play with **Arrow Keys** on desktop or use the dedicated, stylized **Mobile D-Pad** (touch controls) on phones and tablets.
* **Pause/Resume:** Instantly pause the game using the **Spacebar** (desktop) or the **Center Button** on the Mobile D-Pad.

---

## 🛠️ Technologies Used

This project is built using a minimal and efficient stack, ensuring maximum performance and zero external dependencies (other than a utility CSS framework).

* **JavaScript (ES6+):** Pure object-oriented logic for game state management, input handling, and rendering.
* **HTML5 Canvas API:** Used for high-performance 2D rendering and animations.
* **Tailwind CSS:** Utilized via CDN for rapid UI styling, layout responsiveness, and glassmorphism effects.

---

## 🚀 Installation & Running Locally

Since this is a client-side only application, running it locally is extremely simple.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/neon-snake.git](https://github.com/yourusername/neon-snake.git)
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd neon-snake
    ```
3.  **Open the game:**
    Simply double-click the `index.html` file to open it in your preferred web browser. Alternatively, use an extension like "Live Server" in VS Code for a more streamlined development experience.

## 👨‍💻 Developed By

**Anwar Iqbal Dawar**
* [GitHub Profile](https://github.com/ANWARDAWAR)

---

## 📂 Project Structure

```text
neonsnaky/
│
├── index.html        # The main application file (HTML, CSS, JavaScript)
├── snake_icon.svg       # The browser tab icon
└── README.md         # Project documentation and details

---



