# Bookby — Your Personalized Book Recommendation Chatbot

*Bookby* is an AI-powered virtual assistant that helps users find their next favorite book based on their mood, genre, or reading preferences. It is built using *IBM Watson Assistant* and integrated into a simple, attractive HTML website with a friendly virtual bear mascot.

---

## Features

- Friendly, mood-based book recommendations.
- Multiple book genres: horror, fantasy, historical, self-help, and more.
- Clean front-end with book covers and reading tips.
- Uses IBM Watson Assistant Intents, Entities, and Dialog Skills.
- Includes curated reading articles to promote reading habits.
- Can be easily embedded in any website.

---

## Technologies Used

- IBM Cloud Watson Assistant (Classic)
- HTML, CSS, JavaScript
- Unsplash/Flaticon (for images and icons)
- Watson Assistant embed script for web integration

---

## How It Works

1. User opens the Bookby webpage.
2. The Watson Assistant chatbot greets the user.
3. The chatbot understands user input using trained Intents.
4. Dialog nodes ask follow-up questions if needed (for example, asking for mood).
5. The chatbot suggests books based on user input.
6. The conversation ends when the user exits or asks for help.

---

## Entities & Intents

- *Intents:* greeting, goodbye, recommend_book, mood_based_request, help.
- *Entities:* genres (horror, fantasy, historical, self-help), moods (happy, sad, bored).
- *Dialog Flow:* Skill contains parent and child nodes to handle various conditions step by step.

---

## Future Enhancements

- Integrate real-time book APIs such as Google Books for dynamic suggestions.
- Add a user login system to save reading history and preferences.
- Include multi-language support.
- Add a voice-based version of the assistant.
- Develop a mobile app version.

---

## How To Run

1. Clone or download this repository.
2. Open index.html in your web browser.
3. Make sure your Watson Assistant integration script in index.html is configured with:
   - integrationID
   - region
   - serviceInstanceID

4. Interact with Bookby and get book recommendations.

---

## Authors

- Developed by: Tanishka Paliwal
- Built using IBM Watson Assistant, HTML, and CSS.

---

## License

This project is for educational and internship purposes only.
