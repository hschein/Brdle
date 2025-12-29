# Brdle - Broadway Song Guessing Game 🎭

Brdle is a locally hosted web game inspired by *Heardle*, built for Broadway musical fans. It plays short audio snippets of songs, and the player must guess the correct title. The snippets increase in duration with every incorrect guess.

**⚠️ Note on Audio Files:**
This repository contains the **source code only**. Due to copyright laws, no audio files are included. To play this game, you must provide your own legally owned musical tracks.

## 🚀 Features
- **Progressive Hints:** Hints start at 1 second and increase (2s, 4s, 7s...) with each attempt.
- **Local Parsing:** The game automatically parses song titles and sources from filenames.
- **Filtering:** Users can filter the game to include only specific musicals.

## 🛠️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hschein/brdle.git
   cd brdle
   ```

2. **Add Your Music:**
* Create a folder named `songs` in the root directory.
* Add your `.mp3` files to this folder
* **Important:** Files must be named in this format: `Musical Name - Song Title.mp3`
    * *Example:* `Hamilton - My Shot.mp3`
    * *Example:* `Wicked - Defying Gravity.mp3`

3. **Start a Local Server:** Browsers restrict local file access for security, so you must run a simple server.
If you have Python installed (Mac/Linux default):
    ```bash
    python3 -m http.server
    ```
    Or if you use Node.js:
    ```bash
    npx http-server
    ```

4. **Play:** Open your browser to `http://localhost:8000`.

### Acknowledgments
* **Development Partner:** This project was built with the assistance of **Google Gemini**.
