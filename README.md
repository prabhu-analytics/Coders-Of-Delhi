# Coders of Delhi - Pure Python Social Network Analysis

A pure Python data science project simulating social network features like "People You May Know" and "Pages You Might Like" using JSON data. Includes data cleaning, user-page analysis, and recommendation logic — all without pandas or external libraries.

## 🔍 Project Overview

- **Goal**: Analyze and enhance user engagement on CodeBook using raw Python.
- **Dataset**: JSON-based user data including friendships and liked pages.
- **Tools Used**: Python standard library (`json`, `set`, `dict`, etc.)

## 📁 Project Structure

- `codebook_data.json`: Raw input data
- `cleaned_codebook_data.json`: Cleaned and structured output
- `main.py`: Contains all logic for loading, cleaning, and recommending

## 🚀 Features Implemented

### 1. Data Loading & Display
- Load JSON data using Python's built-in `json` module
- Display user details, connections, and liked pages

### 2. Data Cleaning
- Remove users with missing names
- Deduplicate friend lists and page entries
- Remove inactive users (no friends or liked pages)

### 3. People You May Know
- Suggest friends based on mutual connections
- Rank suggestions by number of shared friends

### 4. Pages You Might Like
- Recommend pages using collaborative filtering
- Score pages based on shared interests with similar users

## 📌 Sample Output

```python
People You May Know for User 1: [4]
Pages You Might Like for User 1: [103,102,104]

## 🧠 Key Learnings

- Built recommendation logic from scratch using dictionaries and sets
- Practiced data cleaning and transformation without external libraries
- Simulated real-world social media features using basic Python
- Strengthened understanding of collaborative filtering and graph-based suggestions
- Gained hands-on experience with JSON data structures and pure Python workflows
