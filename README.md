# 🧹 NLP Text Preprocessing using Python & Regular Expressions

## 📌 Project Overview
This project demonstrates the basic steps of **Natural Language Processing (NLP)** using **Python**, **Pandas**, and **Regular Expressions (Regex)**. It creates a raw text dataset, performs text preprocessing, extracts useful information using regex, and saves the cleaned dataset for further NLP tasks.

---

## 🚀 Features

- Create a sample raw text dataset
- Save and read CSV files using Pandas
- Convert text to lowercase and uppercase
- Extract URLs using Regex
- Extract hashtags using Regex
- Search keywords using Regex
- Split text into words
- Clean text by removing:
  - URLs
  - Email addresses
  - User mentions (@username)
  - Hashtags
  - Numbers
  - Special characters
  - Emojis
  - Extra spaces
- Save the cleaned dataset as a CSV file

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- Regular Expressions (`re`)

---

## 📂 Project Structure

```
NLP-Text-Preprocessing/
│── preprocessing.py
│── raw_data.csv
│── cleaned_data.csv
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/NLP-Text-Preprocessing.git
```

2. Open the project folder

```bash
cd NLP-Text-Preprocessing
```

3. Install the required library

```bash
pip install pandas
```

4. Run the program

```bash
python preprocessing.py
```

---

## 📊 Output

### Raw Dataset (`raw_data.csv`)
Contains the original text data with URLs, emails, hashtags, mentions, numbers, and special characters.

### Cleaned Dataset (`cleaned_data.csv`)
Contains the cleaned text after preprocessing.

---

## 📚 Regex Operations Used

- `re.findall()` – Extract URLs and hashtags
- `re.search()` – Search for keywords
- `re.split()` – Split text into words
- `re.sub()` – Remove unwanted patterns

---

## 📖 Text Preprocessing Steps

- Convert text to lowercase
- Remove URLs
- Remove email addresses
- Remove user mentions
- Remove hashtags
- Remove numbers
- Remove special characters
- Remove emojis
- Remove extra spaces

---

## 🎯 Learning Outcomes

After completing this project, you will understand how to:

- Create and manage datasets using Pandas
- Read and write CSV files
- Apply Regular Expressions for text processing
- Clean textual data for NLP applications
- Perform basic text preprocessing techniques

---

