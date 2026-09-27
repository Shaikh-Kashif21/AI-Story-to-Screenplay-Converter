# 🎬 StoryScreen — AI Story to Screenplay

**StoryScreen** is an AI-powered creative writing web application that transforms a raw story, novel chapter, or short story into a structured screenplay.

Using the **Groq API** and an LLM, StoryScreen converts stories into screenplay-style content with scenes, dialogue, action lines, and professional screenplay formatting. It also provides additional creative and production insights to help users develop their stories for screen.

---

## ✨ Features

* 🎬 **AI Story-to-Screenplay Conversion**

  * Transform a story into a structured screenplay using AI.
  * Generates screenplay elements such as `FADE IN`, scene headings, action lines, character names, dialogue, and `FADE OUT`.

* 🎭 **Genre Selection**

  * Auto-detect the genre.
  * Manually select:

    * Thriller
    * Romance
    * Comedy
    * Drama

* 🎞️ **Three-Act Story Breakdown**

  * Act I — Setup
  * Act II — Confrontation
  * Act III — Resolution
  * Displays scene counts and summaries for each act.

* 📊 **Pacing Analysis**

  * Provides a visual representation of the screenplay's three-act pacing structure.

* 🎵 **Background Score Suggestions**

  * Suggests suitable music based on individual scenes and their moods.

* ⚠️ **Production Flags**

  * Highlights potentially difficult, expensive, or sensitive production elements.

* 📄 **Screenplay Export**

  * Export the generated screenplay through a print-ready format that can be saved as PDF.

* 🌙 **Modern Creative UI**

  * Dark cinematic interface
  * Responsive layout
  * Genre-specific visual styling
  * Story input and screenplay output panels

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Groq API**
* **Llama 3.3 70B Versatile**
* **Google Fonts**

  * Playfair Display
  * DM Sans
  * DM Mono

The application directly sends the story and screenplay-generation prompt to the Groq Chat Completions API.

---

## 🚀 How It Works

```text
User Story
    ↓
Select Genre
    ↓
Enter Groq API Key
    ↓
StoryScreen
    ↓
Groq LLM
    ↓
AI Screenplay Generation
    ↓
┌─────────────────────────────┐
│ Screenplay                  │
│ Genre Detection             │
│ Three-Act Breakdown         │
│ Pacing Analysis             │
│ Music Suggestions           │
│ Production Flags            │
└─────────────────────────────┘
    ↓
Export Screenplay
```

---

## 📋 Requirements

You need:

* A modern web browser
* Internet connection
* A valid **Groq API key**

The API key is entered directly into the StoryScreen interface before generating the screenplay.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/StoryScreen.git
```

### 2. Open the project

```bash
cd StoryScreen
```

### 3. Run the application

Since StoryScreen is a client-side HTML/CSS/JavaScript application, you can open:

```text
StoryScreen.html
```

directly in your browser.

Alternatively, use a local development server such as VS Code Live Server.

---

## 🔑 Groq API Setup

1. Obtain a Groq API key.
2. Open StoryScreen.
3. Paste your API key into the **Groq API Key** field.
4. Enter your story.
5. Select a genre or use **Auto Detect**.
6. Click **Convert to Screenplay**.

The application uses the Groq Chat Completions endpoint and the `llama-3.3-70b-versatile` model.

> **Security Note:** For a production deployment, avoid exposing API keys directly in client-side JavaScript. A backend/server-side API proxy should be used to protect the key.

---

## 🎭 Supported Genres

| Genre         | Available |
| ------------- | --------- |
| ✨ Auto Detect | ✅         |
| 🔪 Thriller   | ✅         |
| 💖 Romance    | ✅         |
| 😂 Comedy     | ✅         |
| 🎭 Drama      | ✅         |

---

## 📖 Example

### Input

```text
Ramu was late for work. He grabbed his lunchbox and ran to his scooter.
The scooter didn't start. He kicked it. It started and immediately stopped.
A dog appeared and stole his lunchbox. He chased the dog.
```

### StoryScreen generates

```text
FADE IN:

EXT. STREET - MORNING

Ramu runs toward his scooter, holding his lunchbox...

...

FADE OUT.
```

Along with additional information such as:

* Detected genre
* Number of scenes
* Act breakdown
* Pacing
* Music suggestions
* Production flags

---

## 📁 Project Structure

```text
StoryScreen/
│
├── StoryScreen.html
└── README.md
```

---

## 🎯 Use Cases

StoryScreen can be useful for:

* 🎬 Aspiring screenwriters
* ✍️ Creative writers
* 🎥 Filmmakers
* 📚 Students learning screenplay writing
* 💡 Story ideation and development
* 🎞️ Converting short stories into screenplay drafts

---

## 🔮 Future Improvements

Possible future improvements include:

* User authentication
* Story/project saving
* Character management
* Scene-by-scene editing
* More genres
* Custom screenplay templates
* DOCX export
* Improved PDF generation
* AI character development
* AI dialogue refinement
* Backend API integration
* Secure server-side API key handling
* Multiple AI model support

---

## ⚠️ Disclaimer

StoryScreen is an AI-assisted writing tool. Generated screenplays should be reviewed and edited by the user before being used for professional or production purposes.

---

## ⭐ Support

If you find StoryScreen useful, consider giving the repository a ⭐ on GitHub.

**StoryScreen — Turn your stories into screenplays with AI.** 🎬
