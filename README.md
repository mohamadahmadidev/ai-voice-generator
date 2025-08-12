# AI Text-to-Speech Generator

A simple, easy-to-use web interface for generating high-quality audio from text using OpenAI's Text-to-Speech (TTS) API. This tool allows you to input text, provide optional instructions for tone and cadence, select a voice, and download the resulting audio in various formats.

![Screenshot of the AI Text-to-Speech Generator](https://i.imgur.com/your-screenshot.png) <!-- Replace with a real screenshot URL -->

## ✨ Features

* **Simple Interface**: Clean and intuitive UI built with Tailwind CSS.
* **Custom Instructions**: Provide guidance on tone, cadence, and style for the generated speech.
* **Voice Selection**: Choose from a variety of OpenAI's built-in voices.
* **Multiple Formats**: Download the generated audio in WAV, MP3, AAC, OPUS, or FLAC.
* **API Key Management**: Your API key is saved locally in your browser's `localStorage` for convenience.
* **File Loading**: Easily load your API key, instructions, and text from local files (`.env`, `instraction.txt`, `text.txt`).
* **Audio Preview**: Listen to the generated audio directly in the browser before downloading.
* **Responsive Design**: Works on both desktop and mobile devices.

## 🚀 How to Use

### 1. Prerequisites

You need a modern web browser and an API key from OpenAI.

### 2. Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd your-repo-name
    ```
3.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser. There are no build steps or dependencies to install.

### 3. Configuration (Optional)

To make setup even easier, you can create the following files in the root of the project directory:

* **.env**: To automatically load your API key.
    ```
    OPENAI_KEY=your-openai-api-key-goes-here
    ```
* **instraction.txt**: To automatically load custom instructions.
    ```
    Speak in a calm and clear voice.
    ```
* **text.txt**: To automatically load the text you want to convert.
    ```
    This is the text that will be converted to speech.
    ```

### 4. Running the App

1.  Open `index.html` in your browser.
2.  If you haven't created a `.env` file, enter your OpenAI API Key in the input field.
3.  (Optional) Enter any instructions for the voice model.
4.  Enter the text you want to convert to speech.
5.  Select the desired output format and voice.
6.  Click "Generate & Download".
7.  The audio will be generated, played for preview, and automatically downloaded.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/your-repo-name/issues).

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
