# 📡 Morse Code Translator Web App

**Convert text to Morse code instantly!**  
A simple yet powerful Flask web application that transforms your messages into Morse code.

## ✨ Features

- 🆎 Convert any alphanumeric text to Morse code
- ⚡ Real-time conversion
- 🎨 Clean, minimalist interface
- 📱 Responsive design
- 🔠 Supports A-Z and 0-9 characters

## 🛠️ Installation

1. **Clone the repo**  
```bash
git clone https://github.com/yourusername/morse-code-converter.git
cd morse-code-converter
```

2. **Install dependencies**  
```bash
pip install flask
```

3. **Run the app**  
```bash
python app.py
```

4. **Open in browser**  
```
http://localhost:5000
```

## 🎮 How to Use

1. Type your message in the input box
2. Click the "Convert" button
3. See your message transformed into Morse code!  
*(Example: "HELLO" becomes ".... . .-.. .-.. ---")*

## 🏗️ Project Structure

```
morse-code-converter/
├── 📄 app.py                # Main Flask application
├── 📂 static/
│   └── 🎨 style.css         # Stylish CSS
├── 📂 templates/
│   └── 🖥️ index.html       # Beautiful HTML template
└── 📄 README.md             # This awesome guide!
```

## 🚀 Quick Example

Try converting "SOS":
```python
from morse import text_to_morse
print(text_to_morse("SOS"))  # Output: ... --- ...
```

## 💡 Fun Fact

The first Morse code message was sent in 1844 saying:  
*"What hath God wrought!"*

## 📜 License

MIT License - feel free to use and modify!

---

**Happy coding!** 👨‍💻👩‍💻  
*".... . .-.. .-.. --- / .-- --- .-. .-.. -.."*  
*(That's "HELLO WORLD" in Morse!)*
