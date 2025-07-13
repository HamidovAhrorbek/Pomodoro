⏱️ Pomodoro Timer

This is a **Pomodoro Timer** built with Python and Tkinter, based on the [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique). It's a productivity tool that helps you stay focused by breaking work into intervals of 25 minutes, separated by short breaks.

Developed as part of the **100 Days of Code: Python Bootcamp** by [Angela Yu](https://www.udemy.com/course/100-days-of-code/).

📸 Screenshot 

Work Time 

<img width="2560" height="1600" alt="Screenshot 2025-07-13 at 2 10 40 PM" src="https://github.com/user-attachments/assets/5dc5112f-19e1-4b6b-9124-42464b7689ea" />

Break Time 

<img width="2560" height="1600" alt="Screenshot 2025-07-13 at 2 11 09 PM" src="https://github.com/user-attachments/assets/123cea19-3d79-47ac-a2ad-6846f699814e" />


🚀 Features

* 25-minute work sessions** followed by:
   * 5-minute short breaks
   * 20-minute long break after every 4 sessions
* Start** and **Reset** buttons
   * Visual progress using ✔️ marks
   * Stylish tomato-themed GUI using `Tkinter`


🛠️ Tech Stack

* Python 3
* Tkinter for GUI
* Math module for timer calculation


🔧 How to Run

1. **Clone the repository**:

   git clone https://github.com/yourusername/pomodoro-timer.git
   cd pomodoro-timer


2. Make sure Python is installed (Python 3.x recommended)

3. Run the script:

python main.py

4. Note: Make sure you have tomato.png in the same directory as main.py.


📁 Project Structure

pomodoro-timer/

*  main.py
*  tomato.png
*  README.md


🧠 How It Works

* The timer starts with a 25-minute work period.

* Every second interval is a 5-minute short break.

* After every 4 work sessions (i.e., 8th interval), a long 20-minute break starts.

* ✔️ symbols are displayed for each completed work session.


📚 Learn More

If you're learning Python, this is a great beginner-friendly project to get familiar with:

 * Event-driven programming (with tkinter)

 * Time manipulation

 * GUI design
