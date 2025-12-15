# Embodied Interaction Chatbot

A research-oriented chatbot built with **object-oriented PHP** and the **ChatGPT API**, exploring how conversational agents can influence users’ emotional states (moods).

---

## Project Overview

With the growing presence of conversational AI systems—such as ChatGPT, Gemini, and other chat assistants—this project investigates how a chatbot’s tone and interaction style can affect a user’s mood.

The system detects a user’s initial emotional state, adapts the chatbot’s conversational behavior accordingly, and evaluates whether the interaction leads to a measurable mood change.

---

## Team

- **Project Manager:** Dr.-Ing. Robert Porzel  
- **Graphic Designer / Tester:** Elnaz Mohammadi Asl  
- **Academic Report Writer:** Timo Schuhmann  
- **Tester:** Metasit Getrak  
- **Developer (Me):** Designed and implemented the interactive system using PHP and managed ChatGPT API prompts  

---

## My Role

- Proposed the use of the **ChatGPT API** for the interactive chatbot component  
- Implemented **prompt engineering** strategies to test different chatbot tones  
- Designed the data collection pipeline  
- Stored experimental results in **JSON**, **SQLite**, and **MySQL**  

---

## System Workflow

1. **User Input**  
   The user completes an initial form, and the system identifies their current mood:
   - Happy  
   - Sad  
   - Neutral  

2. **Chatbot Tone Adjustment**  
   Based on the detected mood, the chatbot randomly adjusts its tone and interaction style to either:
   - Match the user’s mood, or  
   - Deliberately unmatch the user’s mood  

   This behavior is implemented using the **ChatGPT API**.

3. **Mood Evaluation**  
   After the conversation, the user completes a questionnaire to assess whether the chatbot interaction influenced their mood.

---

## Key Features

- Object-oriented PHP architecture  
- Interactive chatbot powered by the **ChatGPT API**  
- Prompt management system for experimenting with different conversational tones  
- Multi-format data storage: **JSON**, **SQLite**, and **MySQL**  

---

## Results

Initial observations suggest that users tend to feel happier when the chatbot’s emotional tone aligns with their own—whether both are happy or both are sad.

---

## Video Demo

A demonstration video of the project is available, showcasing:

- User mood input  
- Real-time chatbot interaction  
- Tone adaptation behavior  
- Post-interaction mood evaluation  

🎥 **Demo Video:**  
`video/Embodied-Interaction-Chatbot-Demo.m4v`

---

## Screenshots

Screenshots of the application and example user interactions are available in the `screenshots/` folder.

---

## Notes

- This is a **simplified version** of the project created for **portfolio purposes**.