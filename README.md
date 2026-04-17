# SmartChat.WPF

אפליקציית צ'אט חכמה שנבנתה באמצעות WPF בשפת #C, המאפשרת תקשורת עם מודלי בינה מלאכותית (Gemini ו-ChatGPT), כולל שימוש בכלים (Tools) חיצוניים.

---

## 📌 פרטי הסטודנט

- שם: עלאא אלמדאדחה  
- תעודת זהות: 342542248  

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



דוגמה
מה התאריך היום?

![Chat Image](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/q.png)


---

## 🖥️ מסכים במערכת

### 📷 מסך ראשי (בחירת מודל)
![Chat Image](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/main.png)

---

### 📷 מסך צ'אט Gemini
![Chat Image](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/chat.png)

---

### 📷 מבנה הפרויקט
![Chat Image](https://raw.githubusercontent.com/madadha/SmartChat.WPF/main/structure.png)

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


### שימוש ב-Calculator:
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

## 🚀 הרצה

1. פתח את הפרויקט ב-Visual Studio  
2. הוסף מפתח API (Gemini / OpenAI)  
3. הרץ את התוכנית  

---

## ⚠️ הערות חשובות

- אין להעלות מפתחות API ל-GitHub
- יש להשתמש ב-Environment Variables

---

## 🏁 סיכום

המערכת מדגימה:
- שילוב של בינה מלאכותית
- עבודה עם Tools
- פיתוח ממשק משתמש מתקדם ב-WPF

