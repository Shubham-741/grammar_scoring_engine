# Grammar Scoring Engine 🗣️📊

This project transcribes speech from MP3 audio files using OpenAI's Whisper model and evaluates the grammar quality of the resulting text using LanguageTool.

## 🔧 Features

- 🎙️ Transcribes MP3 files to text using Whisper  
- 📝 Detects grammar issues using LanguageTool  
- 📈 Calculates a grammar score (out of 100)  
- ✅ Outputs suggestions for improvements  

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/Shubham-741/grammar-scoring-engine.git
cd grammar-scoring-engine
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Make sure you have `ffmpeg` installed and added to your system PATH or correctly configured in the notebook/code.

### 3. Run the Notebook

Open `grammar_scoring_engine.ipynb` in Jupyter Notebook or VSCode and run it step-by-step.

---

## 🧠 Sample Output

```vbnet
Original Transcription: He go to school every days.
Number of grammar issues found: 2
Issue: "go" -> "goes"
Issue: "days" -> "day"
Grammar Score: 80/100
```

---

## 📂 Dataset

You can use Mozilla Common Voice MP3 samples for testing.

---

## 🤖 Tech Stack

- OpenAI Whisper  
- LanguageTool  
- PyDub  
- Torch  

---

## 📜 License

MIT License. Feel free to fork and enhance.

---

### 📄 `.gitignore`

```gitignore
__pycache__/
*.pyc
.env
*.zip
*.wav
*.mp3
*.log
.cache/
.ipynb_checkpoints/
```
