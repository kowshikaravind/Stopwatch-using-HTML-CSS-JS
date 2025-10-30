⏱️ Stylish Stopwatch Web App

📘 Project Overview

-> The Stopwatch Web App is a simple yet elegant time-tracking tool built using HTML, CSS, and JavaScript.
It allows users to start, stop, and reset time with a visually appealing gradient design.

-> This project demonstrates the use of JavaScript timing functions (setInterval, clearInterval) along with dynamic DOM updates and modern UI styling using CSS animations.

🚀 Features

-> 🕒 Start, Stop, and Reset functionality

-> ⏰ Real-time time tracking (HH:MM:SS format)

-> 🎨 Modern and responsive UI with gradient background

-> 🌈 Smooth hover animations and glowing button effects

-> 💡 Uses JavaScript’s setInterval() and clearInterval()

-> 🛠️ Technologies Used

-> HTML – Page structure and content

-> CSS – Styling and animations

-> JavaScript – Stopwatch logic and interactivity

⚙️ How It Works

-> The Start button begins the timer using setInterval(), updating every second.

-> The Stop button pauses the timer by calling clearInterval().

-> The Reset button clears all values (hours, minutes, seconds) and resets the display to 00:00:00.

-> The time display updates dynamically using the updateDisplay() function.

-> The layout and buttons are enhanced with smooth gradients, shadows, and animations for a modern look.

💻 How to Run the Project

-> Download or clone the project:

-> git clone https://github.com/your-username/stopwatch-app.git


-> Open the folder and locate the file index.html.

-> Double-click the file or open it in any browser:

-> Google Chrome / Edge / Firefox


-> Click Start to begin timing, Stop to pause, and Reset to clear.

🧩 Example Output

-> When you open the stopwatch, you’ll see:

-> 00:00:00
-> [Start] [Stop] [Reset]


After clicking Start:

-> 00:00:10

🧠 Concepts Used

-> setInterval() → Executes a function at specified time intervals (1 second).

-> clearInterval() → Stops the interval when the stopwatch is paused or reset.

-> String Formatting → Uses padStart(2, '0') to maintain two-digit display.

-> DOM Manipulation → Dynamically updates time using JavaScript functions.

🎨 UI Design Highlights

-> Animated gradient background (@keyframes gradientShift)

-> Rounded container with glass-like blur effect

-> Circular glowing buttons with hover and click animations

-> Center-aligned responsive layout

👨‍💻 Author

Kowshik Aravind
Frontend developer passionate about creating stylish, interactive, and user-friendly web applications.
