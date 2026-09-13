## WordPiece Tokenizer
### Project Description

#### This project implements a simple WordPiece Tokenizer from scratch using Python.

#### The program reads words from a text dataset, calculates word frequencies, performs character-level splitting, calculates token and pair frequencies, finds the best token pairs using WordPiece scores, and merges the pairs to build the final vocabulary.

### Dataset

#### The dataset contains words with common patterns and repeated word forms.
### Example:

* play
* player
* playing
* played
* play
* player
* read
* reader
* reading
* read
* write
* writer
* writing
* write

### Project Structure

Wordpiece_Tokenizer

│
├── dataset

│   └── rawdata.txt

│
├── wordtokenizer.py

│
└── README.md

### Technologies Used

* Python
* WordPiece Tokenization
* Python Collections Counter

### Output Screenshots
#### Screenshot 1 – Word Frequencies

<img width="712" height="282" alt="Screenshot 2026-09-13 231031" src="https://github.com/user-attachments/assets/566e32c6-9293-4884-83d0-6fd18a5c6e53" />

#### Shows the word frequency count of the input dataset.

### Screenshot 2 – Initial Word Splits

<img width="562" height="273" alt="Screenshot 2026-09-13 231042" src="https://github.com/user-attachments/assets/59b6c8d0-79b1-4703-bf70-4c3bf04ce7c8" />

#### Shows how each word is split into individual characters before WordPiece training.

### Screenshot 3 – WordPiece Training

<img width="467" height="324" alt="Screenshot 2026-09-13 231053" src="https://github.com/user-attachments/assets/ce9fbf9c-0124-46b1-ab01-7a964809f1e1" />

#### Shows the pair frequency, score, selected pair, and token merging process.

### Screenshot 4 – Final Vocabulary

<img width="493" height="268" alt="Screenshot 2026-09-13 231109" src="https://github.com/user-attachments/assets/90e9da67-2fcd-45da-85ec-9b705fd3c1e0" />

#### Shows the final WordPiece vocabulary and vocabulary size after training.

### Screenshot 5 – Tokenization and Token IDs

<img width="575" height="141" alt="Screenshot 2026-09-13 231128" src="https://github.com/user-attachments/assets/63c460c6-a629-4069-ba32-ccabf5e4c2fb" />

#### Shows the input word, generated tokens, and corresponding token IDs, followed by successful program completion.

