# StockBot

:

🧠 Project Title: StockBot – Voice-Based Stock Management System
🔍 Description:

VoiceVend is an intelligent stock management system designed for small retail stores selling bottled soft drinks. It uses speech recognition to take input about sold items and updates the stock accordingly. The system also gives real-time voice-based feedback to confirm item removal and total cost.

This solution simplifies inventory tracking and makes operations hands-free and efficient.

🛠️ Key Features:
🎤 Voice Input: Speak the sold item and quantity (e.g., “Sprite 200 2”).

📦 Stock Update: Automatically removes the sold quantity from current stock.

🔈 Voice Output: Confirms the transaction and announces the total price.

📊 CSV Integration: Reads and updates data from a CSV file representing current stock.

🧠 Speech-to-Text & Text-to-Speech: Built using Google Speech Recognition and pyttsx3.

🧪 Test Case Example:
If the voice input is:

arduino
Copy
Edit
"Sprite 200 2"
The system will:

Decrease 2 units from Sprite 200 ml stock.

Announce: "2 bottle(s) of Sprite 200 ml removed from stock. Total cost is 40 rupees."

