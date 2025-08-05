# 🚴 Habit Tracker with Pixela API

This is a Python-based habit tracker that integrates with the [Pixela API](https://pixe.la/) to track daily activities like cycling, running, or any custom habit — visualized as a graph.

## 📌 Features

- Add daily habit entries (e.g., kilometers cycled)
- Update entries
- Delete entries
- REST API integration using `requests`

## 📷 Example Graph (from Pixela)
![Pixela Graph](https://docs.pixe.la/_images/graph.png)

---

## 🧰 Technologies Used

- Python 3
- `requests` library
- [Pixela API](https://pixe.la/)

---

## ⚙️ How It Works

### ✅ User Creation
Creates a Pixela user (only needed once).

### ✅ Graph Creation
Defines a custom graph (e.g., `Cycling Graph`) with color and units.

### ✅ Daily Pixel Entry
User inputs how much they did (e.g., "How many km did you cycle today?") and it's logged to the graph.

### ✅ Update or Delete
You can also update or delete today's entry.

---

## 🛠 Setup Instructions

1. Clone this repo:
```bash
git clone https://github.com/YOUR_USERNAME/habit-tracker-with-pixela-api.git
```
2. Create a virtual environment (optional):
```bash
python -m venv .venv
```
3. Activate the virtual environment:
- Windows: .\.venv\Scripts\activate
- Mac/Linux: source .venv/bin/activate
  
4. Install dependencies:
```bash
pip install requests
```
5. Replace these variables in main.py with your Pixela details:
```python
TOKEN = "your_token"
USERNAME = "your_username"
GRAPH_ID = "your_graph_id"
```
6. Run the program:
```bash
python main.py
```
---
## 📝 Example
```sql
How many kilometers did you cycle today? 5.2
```
✅ Success message returned from Pixela API and your graph is updated.
---

## 📜 License
This project is open source and free to use.
---
## ✨ Author
- Sayan Sanki
- GitHub: @Ssayan1
```yaml
Let me know if you'd like me to generate the `README.md` file for download, or if you want to push this automatically.
```
---
