# 🎬 Random Watch Picker

A fun Python script that helps you decide **what to watch** when you're stuck in indecision-land! Pick a genre, and it randomly selects a movie or show from your custom watchlist — complete with an image if you've added one.

---

## 📂 Features

- 🎭 Filter by genre
- 🎲 Randomly selects a title from your CSV
- 🖼️ Displays an image (poster/thumbnail) if available
- 🔁 Keeps looping until you type `exit`
- 💻 Runs in Google Colab, Jupyter Notebook, or VS Code

---

## 📄 How It Works

1. You provide a CSV file with your watchlist.
2. The script prompts you to choose a genre.
3. It randomly selects a title that matches.
4. If an image URL is provided in the CSV, it shows the poster too!
5. Type `exit` at any time to end the script.

---

## 🧾 CSV Format

Make sure your file is named: `Watchlist - Sheet1.csv`

**Required columns:**
- `Title` – the name of the show/movie
- `Genre` – e.g., Action, Comedy, Animated
- `Platform` – e.g., Netflix, Hulu, Disney+
- `Type` – e.g., Movie, TV Show
- `Image` *(optional)* – a direct URL to a poster or thumbnail

**Example:**

| Title              | Genre   | Platform | Type    | Image                                      |
|-------------------|---------|----------|---------|--------------------------------------------|
| The Office         | Comedy  | Peacock  | TV Show | https://upload.wikimedia.org/.../office.jpg |
| Inception          | Action  | Netflix  | Movie   | https://upload.wikimedia.org/.../inception.jpg |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/randomshow.git
cd randomshow
