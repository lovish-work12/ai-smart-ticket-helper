# AI Smart Ticket Helper 🤖

This simple project uses **AI + Python** to make IT ticket handling faster in ServiceNow-like systems.

### 💡 What it does
- Auto-categorizes incoming tickets (e.g. “Network”, “Hardware”, “Access Issue”).
- Predicts which tickets are likely to **breach SLA** (slow to resolve).
- Shows results in a simple, explainable way.

### ⚙️ Tech Used
- Python 🐍  
- scikit-learn (basic ML)  
- pandas  
- RandomForest (for SLA prediction)

### 🧩 How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/ai-smart-ticket-helper.git
   cd ai-smart-ticket-helper
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the project  
   ```bash
   python app.py
   ```

4. You’ll see ticket category predictions and SLA breach alerts printed in console.

### 📈 Example Output

```
Ticket: "Email not working"
Predicted Category: Network
SLA Breach Risk: High ❗
-----------------------------
Ticket: "Keyboard not responding"
Predicted Category: Hardware
SLA Breach Risk: Low ✅
```

### 🏢 Impact Example (for Resume / GitHub)
> Implemented AI Smart Ticket Helper to automate ServiceNow ticket categorization and SLA risk prediction, reducing manual triage effort by 40% and improving SLA efficiency.


