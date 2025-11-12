🧩 Abstract:

This project aims to develop an interactive FAQ chatbot inside a Unity environment.
The chatbot allows users to type their questions, and it responds with predefined answers using natural language understanding logic.
The goal is to make information access simple and engaging, simulating a real-time support system that can be integrated into websites, mobile apps, or VR environments.
This project demonstrates Unity’s UI system, scripting in C#, and basic AI integration.

🧾 Procedure:

Create a new Unity project

Open Unity Hub → New 3D Project → Name: FAQ_Chatbot_AI.

Design the UI

Create a Canvas → Add:

Input Field → for typing user questions

Button → “Send”

Scroll View / Text Area → to display chat history

Add TextMeshPro

Import TextMeshPro essentials.

Replace default UI Text components with TMP Text for better visuals.
Write logic for FAQs

Store common questions and their answers in a dictionary.

Compare the user input with stored keywords.

Display chatbot responses on the screen.

Connect UI and Script

Link input field, button, and text output area in the Unity Inspector.

Test the conversation by pressing Play.

Build the Project

File → Build Settings → Platform → WebGL or Windows → Build & Run.

Create a Script

Create a C# script named ChatbotAI.cs and attach it to an empty GameObject named “ChatManager”.
Step 1: Create the Script

In Unity, go to Assets → Right-click → Create → C# Script.

Name it OpenAIManager.

Double-click it to open in Visual Studio or your code editor.
Step 2: Add the OpenAI Request Code
Step 3: Add Your API Key

Go to OpenAI Platform
 → API Keys.

Copy your secret API key.

In Unity, select the GameObject with OpenAIManager.

Paste your API key into the apiKey field in the Inspector.

⚠️ Do not share this key publicly.
Connect Chatbot to OpenAIManager
