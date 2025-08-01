# 📚 ReadMate – AI Book Recommendation Chatbot

## 🔍 Overview

**ReadMate** is an AI-powered conversational chatbot designed to recommend books tailored to user preferences such as genre, mood, favorite authors, and reading level.  
Built using **IBM Watson Assistant**, it simulates human-like interaction and delivers personalized reading suggestions.  
This project demonstrates how conversational AI can enhance user experience in book discovery.

---

## 🎯 Objectives

- Build an intelligent book recommendation chatbot using IBM Watson Assistant  
- Leverage Natural Language Processing (NLP) to understand user input  
- Use **entities** and **slots** to extract user preferences dynamically  
- Handle incomplete or vague queries using fallbacks and slot-filling logic  

---

## 🛠️ Tools & Technologies

- **IBM Watson Assistant** – Dialog flow, NLP, and skill-building  
- **IBM Cloud** – Hosting Watson Assistant and service deployment  
- **CSV Files** – Used for importing entities like genre, mood, etc.  
- **JSON** – Stores chatbot logic (`differentbooks_ai.json`)  
- **Jupyter Notebook** – Project explanation (`readmate summary.ipynb`)  
- **Markdown** – Documentation (`readme.md`)  
- **HTML/CSS/JS** – Basic front-end integration (index page)  

---

## 🤖 Key Watson Assistant Features Used

| Feature           | Description                                                        |
|-------------------|--------------------------------------------------------------------|
| **Intents**       | Interpret user intentions (e.g., ask for recommendations)          |
| **Entities**      | Extract values like genre, feelings, author, reading level         |
| **Dialog Nodes**  | Manage conversational flow based on recognized patterns            |
| **Slots**         | Collect missing data needed to make recommendations                |

---

## 💬 Intents

| Intent Name        | Description                                 |
|--------------------|---------------------------------------------|
| `#Greeting`        | Recognize and respond to greetings          |
| `#Goodbye`         | End the chat with polite farewells          |
| `#Genre_Search`    | Recommend books based on selected genre     |
| `#Mood_Based`      | Suggest books that match user’s mood        |
| `#Author_Search`   | Recommend books by specific authors         |
| `#ReadingLevel`    | Match books to user’s reading level         |
| `#Need_Help`       | Assist indecisive users in finding a book   |
| `#Fallback`        | Handle unrecognized input with helpful tips |

---

## 🏷️ Entities

| Entity File           | Description                                     |
|------------------------|-------------------------------------------------|
| `genre_entity.csv`     | Contains genres like fantasy, thriller, romance |
| `feelings.csv`         | Maps emotions (e.g., happy, anxious)            |
| `authors details.csv`  | Authors commonly referenced by users            |
| `readinglevel.csv`     | Levels like beginner, teen, expert              |

---

## 🧠 Decision Logic Files

| File Name               | Purpose                                            |
|--------------------------|----------------------------------------------------|
| `differentbooks_ai.json` | Main Watson Assistant skill export                 |
| `feelings decider.csv`   | Maps moods to book types or suggestions            |
| `readmate summary.ipynb` | Notebook explaining logic, usage, and setup        |

---

## 🌐 Front-End

| File Name     | Purpose                                 |
|---------------|-----------------------------------------|
| `Index.html`  | Web landing page for embedding chatbot  |

---

## 💡 Example Interactions

| User Says                            | Bot Responds                                           |
|-------------------------------------|--------------------------------------------------------|
| "Suggest a sci-fi book"             | "Try *Dune* by Frank Herbert!"                        |
| "I'm feeling bored"                 | "*The Alchemist* is a great pick to get inspired."    |
| "Any books by Agatha Christie?"     | "Try *Murder on the Orient Express* or *And Then There Were None*." |
| "I'm a beginner reader"             | "*Charlotte’s Web* is a great start!"                 |

---

## 📁 Project Structure

📁 Project Root
├── authors details.csv
├── differentbooks_ai.json
├── feelings.csv
├── genre_entity.csv
├── Index.html
├── feelings decider.csv
├── readinglevel.csv
├── readmate summary.ipynb
└── readme.md

## 🚀 Future Enhancements

- 🔌 Connect with Goodreads or Google Books API for live book data  
- 📊 Add filters for ratings, language, or publication year  
- 📱 Build a mobile version with Flutter or React Native  
- 🎙️ Integrate speech-to-text for hands-free interaction  

---

## 👨‍💻 Developed by

**Mayukh Srivastava**  
Artificial Intelligence & Machine Learning – 3rd Year Student  
📧 [mayukhsrivastav8315@gmail.com]
🔗 [GitHub: mayukh79](https://github.com/mayukh79)

