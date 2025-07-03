## 🖮 Typing Speed Calculator 🧠⌨️

This is a simple **Typing Speed Calculator** built using Python. It allows users to test their typing speed and accuracy by comparing their input against randomly selected sentences.

## 📋 Features

Measures typing speed in words per second

Calculates typing accuracy by counting character-level errors

Includes random test sentences for variety

Allows repeated tests until the user chooses to exit

## 🛠️ Requirements

Python 3.x

No external libraries required

## 🧪 How It Works

## Run the Python script:
1) python type.py
2) Type yes to begin a typing test
3) A sentence will appear; type it as accurately and quickly as possible
4) After submission, the program displays:
   i) Your typing speed in words per second
   ii) The number of errors compared to the original sentence

5) Type no to exit the program

## 🧩 Code Breakdown

1) mistake(partest, usertest):
Compares the original sentence (partest) and user input (usertest) to count character-level mistakes.

2) speed_time(time_s, time_e, userinput):
Calculates the time taken and derives typing speed based on the number of characters typed.

## 🚀 Sample Output

ready to test: yes/no :yes
***** typing speed *****
Modern education blends technology and traditional learning, fostering skill development and critical thinking in students.

Enter: Modern education blends technology and traditional
Speed : 2 w/sec
Error : 73
## 📚 Future Improvements

1) Display WPM (Words Per Minute) instead of characters/second
2) Add a GUI using Tkinter or PyQt
3) Highlight mistakes in real time
4) Save results to a file or maintain a leaderboard
