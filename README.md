# 🏏 IPL Data API Project

## 🚀 Features
* **Match History:** Purane matches ka data (2008-2024).
* **Team Stats:** Har team ki performance aur squad ki details.
* **Player Profiles:** Players ka record aur unke stats.
* **Fast & Lightweight:** Optimized endpoints for quick response.

## 🛠️ Tech Stack
* **Language:** [e.g., Python 3.x]
* **Framework:** [e.g., Flask / FastAPI / Express.js]
* **Database:** [e.g., SQLite / PostgreSQL / MongoDB]
* **Dataset:** Kaggle IPL Dataset (2008-2024)

## 📂 Project Structure
```text
├── matches/             # CSV files or database backups
├── ipl/                 # API Endpoint handlers
├── rescue/              # API Endpoint handlers
├── main.py              # Main entry point
├── requirements.txt     # Python dependencies
└── README.md            # Documentation
```

## ⚙️ Installation & Setup

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/ipl-api-project.git
   cd ipl-api-project
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the API:**
   ```bash
   python app.py
   ```

## 📍 API Endpoints (Usage)

| Endpoint | Method | Description |
| :--- | :--- | :--- |
| `/api/matches` | `GET` | Saare matches ki list milti hai. |
| `/api/match/<id>` | `GET` | Specific match ki details (Umpire, Venue, Result). |
| `/api/teams` | `GET` | Saari IPL teams ki list. |

**Example Response (`/api/match/1312200`):**
```json
{
  "id": 1312200,
  "city": "Ahmedabad",
  "winner": "Gujarat Titans",
  "umpire1": "CB Gaffaney",
  "umpire2": "Nitin Menon"
}
```
