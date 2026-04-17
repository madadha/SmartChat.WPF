# SmartChat.WPF

אפליקציית צ'אט חכמה שנבנתה באמצעות WPF בשפת #C, המאפשרת תקשורת עם מודלי בינה מלאכותית (Gemini ו-ChatGPT), כולל שימוש בכלים (Tools) חיצוניים.

---

## 🎯 מטרת הפרויקט

מטרת הפרויקט היא לבנות מערכת צ'אט חכמה אשר:
- מאפשרת תקשורת עם מודלי AI
- תומכת בזיכרון שיחה
- מאפשרת בחירת מודל
- תומכת בהזרמת תשובות (Streaming)
- משתמשת בכלים חיצוניים (Tools)

---

## 🧠 טכנולוגיות בשימוש

- WPF (Windows Presentation Foundation)
- C#
- Gemini API (Google)
- OpenAI API
- JSON Processing

---

## ⚙️ תכונות עיקריות

### ✅ צ'אט עם מודלים
- Gemini
- ChatGPT

### ✅ זיכרון שיחה
- שמירת היסטוריית השיחה  
- אפשרות לניקוי זיכרון  

### ✅ בחירת מודל
- מסך ראשי לבחירת המודל  

### ✅ הזרמת תשובות (Streaming)
- תשובות מוצגות בצורה הדרגתית  

### ✅ שימוש בכלים (Tools)
- DateTime Tool (תאריך ושעה)  
- Calculator Tool (חישובים מתמטיים)  

---

## 🛠️ הסבר על הכלים (Tools)

### 📅 DateTimeTool
מחזיר:
- תאריך נוכחי  
- שעה נוכחית  

דוגמה:
מה התאריך היום?

![Date Tool](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/q.png)

---

### 🧮 CalculatorTool
מבצע חישובים מתמטיים.
![CalculatorTool](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/CalculatorTool.png)
דוגמה:
כמה זה (5*5)**

---

## 🖥️ מסכים במערכת

### 📷 מסך ראשי (בחירת מודל)
![Main Screen](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/main.png)

---

### 📷 מסך צ'אט Gemini
![Gemini Chat](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/chat.png)

---

### 📷 מבנה הפרויקט
![Project Structure](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/structure.png)

---

## 🔄 איך המערכת עובדת

1. המשתמש שולח שאלה  
2. המערכת שולחת את השאלה ל-AI  
3. המודל מחליט האם להשתמש בכלי (Tool)  
4. אם כן:
   - הכלי מופעל  
   - התוצאה מוחזרת למודל  
5. המודל מחזיר תשובה סופית למשתמש  

---

## 🧪 דוגמאות לשימוש

שימוש ב-Date Tool:
מה השעה עכשיו?

שימוש ב-Calculator Tool:
כמה זה 5*5?

---

## 📦 מבנה הפרויקט

SmartChat.WPF
│
├── Models
├── Services
├── Tools
├── Views
├── Styles
├── Helpers
│
├── App.xaml

---
🚀 הרצה
פתח את הפרויקט ב-Visual Studio
הוסף מפתח API (Gemini / OpenAI)
הרץ את התוכנית


🏁 סיכום
המערכת מדגימה:
שילוב של בינה מלאכותית
עבודה עם Tools
פיתוח ממשק משתמש מתקדם ב-WPFF  
