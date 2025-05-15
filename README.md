# 🎙️ Speech-to-Text Application

A user-friendly and customizable Speech-to-Text transcription tool with support for multiple models, Voice Activity Detection (VAD), and optional OpenAI API integration for text proofreading.

---

## 📦 Installation

### ✅ Standard Installation

```bash
pip install .
```

### 🪟 Windows Setup

Simply run the `run.bat` file to automatically perform the following:

1. Create a Python virtual environment
2. Install required pip packages
3. Launch the Speech-to-Text application

---

## 🚀 Usage

### Run the Application

```bash
python -m speech_to_text
```

### Configuration Steps

1. Open the application and navigate to **App Settings** to configure general options.
2. Go to **Model Settings** and choose your desired speech recognition model.
3. Adjust **Transcribe Settings** for input/output preferences.
4. Set up **VAD (Voice Activity Detection) Settings** to manage silence detection and segmentation.
5. Click **Start Transcription** to begin!

---

## 🔑 API Integration (Optional)

If you'd like to enable **text proofreading** using the OpenAI API:

* Set your API key as an environment variable:

```bash
export OPENAI_API_KEY=your_openai_key_here
```

For Windows PowerShell:

```powershell
$env:OPENAI_API_KEY="your_openai_key_here"
```

---

## 📌 Notes

* If you select `local_model` under **Model size or path**, the application will use a model with the same name located in your local directory.

---

## 🧠 Features

* 🎧 Real-time speech transcription
* 🗣️ Local and cloud-based model support
* ✨ OpenAI integration for grammar and clarity improvements
* 🎛️ Flexible configuration UI for advanced control
* 🧩 Voice Activity Detection (VAD) for automatic segmentation

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open a pull request or issue.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you'd like to include images, badges (e.g., version, license, Python compatibility), or demo videos.
