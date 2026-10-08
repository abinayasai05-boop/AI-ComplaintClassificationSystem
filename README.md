# AI Complaint Classification and Priority Detection System

## 📌 Project Overview

The **AI Complaint Classification and Priority Detection System** is a machine learning project developed for the **TSA (Text and Speech Analytics)** subject.

The system analyzes customer complaints and automatically identifies the complaint category and priority level. It helps organizations organize customer complaints and identify urgent issues quickly.

## 🎯 Objectives

- Automatically classify customer complaints.
- Identify the type of complaint.
- Calculate prediction confidence.
- Detect complaint priority.
- Reduce manual complaint categorization.
- Help customer support teams handle complaints efficiently.

## 🧠 Complaint Categories

The system classifies complaints into:

- Billing
- Delivery
- Product
- Service
- Account
- Technical
- Refund

## 🚦 Priority Levels

The system automatically detects three priority levels:

- 🔴 **HIGH** – Urgent or critical complaints
- 🟡 **MEDIUM** – Complaints requiring attention
- 🟢 **LOW** – Normal complaints

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- TF-IDF
- Logistic Regression
- Natural Language Processing (NLP)

## ⚙️ How It Works

```text
Customer Complaint
        ↓
Text Preprocessing
        ↓
TF-IDF Feature Extraction
        ↓
Logistic Regression
        ↓
Complaint Category
        ↓
Confidence Score
        ↓
Priority Detection
        ↓
Support Action
```

## 🔍 Example

### Input

```text
My payment was charged twice and this is very urgent.
```

### Output

```text
Category   : Billing
Confidence : High
Priority   : HIGH
Action     : Immediate attention required
```

## 📊 Model Evaluation

The project evaluates the machine learning model using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

A category distribution graph and confusion matrix are also generated to visualize the model's performance.

## 🚀 How to Run

### 1. Open Google Colab

Create a new notebook in Google Colab.

### 2. Copy the Project Code

Paste the complete Python code into a Colab cell.

### 3. Run the Cell

Run the cell and wait for the model to train.

### 4. Enter a Complaint

When prompted, enter a customer complaint.

Example:

```text
The product I received is damaged and I want a replacement.
```

The system will display:

```text
Category
Confidence
Priority
Recommended Action
```

Type:

```text
exit
```

to stop the interactive classifier.

## 📁 Project Structure

```text
AI-Complaint-Classification/
│
├── AI_Complaint_Classification.ipynb
└── README.md
```

## 🌟 Key Features

- 🤖 AI-based complaint classification
- 📝 Natural language processing
- 📊 TF-IDF text representation
- 🧠 Logistic Regression classification
- 📈 Model performance evaluation
- 🎯 Confidence score
- 🚦 Automatic priority detection
- 💬 Interactive complaint testing
- 📉 Confusion matrix visualization

## 🔮 Future Enhancements

- Add a larger real-world complaint dataset.
- Add more complaint categories.
- Use advanced transformer models such as BERT.
- Add multilingual complaint classification.
- Build a web application using Flask or Streamlit.
- Store complaints in a database.
- Add automatic email/ticket generation.
- Add sentiment and emotion detection.
- Create an analytics dashboard for support teams.

## 👩‍💻 Project Type

**TSA – Text and Speech Analytics**

**Project:** AI Complaint Classification and Priority Detection System

**Platform:** Google Colab

**Language:** Python

## 📜 License

This project is developed for educational and academic purposes.
