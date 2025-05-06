
# 🔤 G2Prosody

**G2Prosody** is a Python-based mini-project that implements core components of a Text-to-Speech (TTS) system. It performs Grapheme-to-Phoneme (G2P) conversion using a rule-based approach and models basic prosodic features by assigning durations to phonemes.

---

## 📌 Features

* ✅ **Rule-Based G2P Conversion**
  Converts English words to a sequence of ARPAbet-like phonemes based on simplified phonological rules.

* ✅ **Prosodic Duration Modeling**
  Assigns duration (in milliseconds) to each phoneme depending on its type (vowel/consonant) and position (e.g., final syllable emphasis).

* ✅ **No Dependencies Required**
  Runs with standard Python — no external libraries needed.

---

## 🧠 Concepts Demonstrated

* Grapheme-to-Phoneme mapping
* Simplified phonological rules (e.g., soft ‘c’, 'th', double consonants)
* Duration assignment based on phoneme class
* Basics of prosody in speech synthesis

---

## 📁 Project Structure

```
G2Prosody/
├── g2p_converter.py             # Rule-based phoneme converter
├── g2p_with_duration.py         # G2P + prosodic duration modeling
├── test_words.py                # Example test cases
└── README.md                    # You're reading it!
```

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/G2Prosody.git
   cd G2Prosody
   ```

2. Run a test script:

   ```bash
   python g2p_with_duration.py
   ```

*No external packages required.*

---

## 🧪 Example Output

```
Word: cat -> Phonemes: ['K', 'AE', 'T'] -> Durations: [50, 100, 70]
Word: the -> Phonemes: ['DH', 'AH'] -> Durations: [50, 120]
Word: apple -> Phonemes: ['AE', 'P', 'L', 'E'] -> Durations: [100, 50, 50, 120]
```

---

## 🎯 Use Cases

* Educational demonstrations of TTS pipelines
* Rule-based NLP and speech processing prototypes
* Foundations for statistical or neural G2P modeling

---

## 👨‍💻 Author

**Muhammad Ibtesaam Aslam**
BSAI Final Year Student
[LinkedIn](https://www.linkedin.com/in/ibtesaamaslam) | [GitHub](https://github.com/ibtesaamaslam)

> “From graphemes to prosody — building blocks of synthetic speech.” 🎤

---

## 📚 Future Enhancements

* Integrate syllable detection
* Expand rule set and handle exceptions
* Move toward data-driven (ML/DL) G2P models
* Add pitch and stress modeling for advanced prosody

---

## 🗂 License

MIT License — free to use, modify, and distribute.
