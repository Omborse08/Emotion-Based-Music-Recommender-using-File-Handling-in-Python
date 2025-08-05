# 🎵 Emotion-Based Music Recommender

Welcome to the **Emotion-Based Music Recommender**, a beginner-friendly yet powerful Python project that uses **file handling** techniques to recommend songs based on your mood.

> 🔥 This project makes use of `seek()`, `tell()`, `readline()`, and dynamic file reading based on user input – making it a great mini-project for learning **file I/O in Python**.

---

## 📌 Features

- 🎧 Asks the user how they’re feeling (e.g., sad, happy, angry)
- 📂 Reads songs from separate text files stored in a `Songs/` folder
- 📜 Displays 2 songs at a time from the respective mood file
- 💾 Uses `seek()` and `tell()` to track the position inside the file
- 🔁 Prompts the user if they want more recommendations
- 🔄 Offers a "Restart Playlist" feature when the end is reached
- 🛡️ Handles invalid moods and inputs gracefully

---

## 📂 Folder Structure

Emotion-Based-Music-Recommender/
│
├── Songs/
│ ├── sad.txt
│ ├── happy.txt
│ ├── angry.txt
│ ├── motivated.txt
│ └── romantic.txt
│
└── recommender.py


---

## 🧠 Concepts Used

- `open()`, `seek()`, `tell()`, `readline()`
- File paths and dynamic file access
- Loops and conditional logic
- Match-case control structure (Python 3.10+)
- String normalization using `.lower()`
- User input and flow control

---

## 🛠️ Requirements

- Python 3.10 or higher (for `match-case`)
- A folder named `Songs/` in the same directory as your Python file
- Each `.txt` file should have multiple song names, each on a new line

Example `sad.txt`:
Let Her Go - Passenger
Someone Like You - Adele
Fix You - Coldplay
Too Good at Goodbyes - Sam Smith

---

## ▶️ How to Run

1. Clone the repository or download the code
2. Create a `Songs/` folder and add `.txt` files for each emotion
3. Open your terminal and run:

```bash
python recommender.py

🎧 Welcome to Emotion-Based Music Recommender 🎧

How are you feeling today? → sad
📝 Reading songs from: Songs/sad.txt

📍 Reading at Byte Position: 0

> Songs: Let Her Go - Passenger
> Songs: Someone Like You - Adele

Want more recommendations? (y/n): y
```

---

## 💡Tips
You can add more emotions by updating the name list and adding new .txt files.
This is a great project to learn how to handle large files, manage file pointers, and build real-world logic using Python basics.

---

## 📬Contribution
Pull requests and feedback are welcome! This is a beginner-friendly project to explore how powerful file I/O in Python can be.

---

## 📃License
This project is open-source and free to use for learning and personal projects.
