# 💧 Water Reminder App

This is a lightweight **Python script** that helps you stay hydrated by reminding you to drink water at regular intervals.

---

## 🧩 Features
- Sends a **desktop notification** every hour.  
- Displays a **console message** reminder.  
- Simple and lightweight — runs in the background.  
- Works on all major platforms (Windows, macOS, Linux).

---

## ⚙️ Requirements
Make sure you have Python 3 installed.  
Install the required dependency using:

```bash
pip install plyer
```

---

## 🚀 How to Run

1. Clone or download this repository.  
2. Open a terminal in the project directory.  
3. Run the script:

```bash
python main.py
```

You’ll see:
```
Please sip some water!
```
And you’ll receive a system notification every hour reminding you to drink water.

---

## 🔁 Customization
You can adjust the reminder frequency by changing the sleep interval in `main.py`:

```python
time.sleep(60*60)  # 60 minutes
```

For example, to remind every 30 minutes:
```python
time.sleep(60*30)
```

---

## 📦 Dependencies
- [plyer](https://pypi.org/project/plyer/) — for cross-platform notifications

---

## 🧠 Author
Developed by **Janam Parekh**  
Stay hydrated and healthy! 💦
