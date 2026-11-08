# AI Security Notes | לומדים אבטחת AI בעברית

סדרת למידה קצרה שמחברת בין אבטחת AI, מסגרת OWASP ו־Data Science. כל פרק מתחיל ברעיון פשוט, ממשיך בדוגמה ובוויזואליזציה, ומסתיים במשהו שאפשר לנסות לבד.

המאגר מלווה סדרת תוכן ללינקדאין. אין צורך במפתח API או בשירות בתשלום.

## מסלול הלמידה

| פרק | מה לומדים | התנסות |
| --- | --- | --- |
| [01 — מפת OWASP](topics/01-owasp-overview/README.md) | איפה נמצאים הסיכונים ביישום AI? | מיפוי זרימת מידע |
| [02 — Prompt Injection](topics/02-prompt-injection/README.md) | כשמידע חיצוני מנסה להפוך להוראה | ניתוח תרחיש סינתטי |
| [03 — זיהוי בעזרת ML](topics/03-ml-detection/README.md) | איך מודדים גלאי, ומה המחיר של טעויות? | מחברת עם נתונים סינתטיים וגרף |
| [04 — Excessive Agency](topics/04-excessive-agency/README.md) | מה קורה כשמחברים מודל ליותר מדי כוח? | תכנון הרשאות ואישורים |

## מתחילים לשחק

[פתיחת המחברת ב־Google Colab](https://colab.research.google.com/github/Liranbz/ai-security-notes/blob/main/topics/03-ml-detection/starter.ipynb)

או מקומית, עם Python 3.10 ומעלה:

```bash
git clone https://github.com/Liranbz/ai-security-notes.git
cd ai-security-notes
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

ב־Windows מפעילים את הסביבה באמצעות `.venv\Scripts\activate`.
פתחו את `topics/03-ml-detection/starter.ipynb` והריצו את התאים לפי הסדר.

## איך בנוי כל פרק?

רעיון אחד → דוגמה → תרשים → התנסות → מגבלות ושאלת המשך. הפרקים הם נקודת פתיחה ללמידה ולהרחבה, ולא מערכת הגנה מוכנה לייצור.

## מקורות וגרסאות

המיפוי מבוסס על [OWASP Top 10 for LLM Applications — מהדורת 2025](https://genai.owasp.org/llm-top-10/), שנבדקה ב־8 בנובמבר 2026. זהו מאגר לימוד עצמאי, ללא שיוך רשמי ל־OWASP. ההסברים והתרשימים כאן מקוריים; המקורות החיצוניים כפופים לרישיונות שלהם.

## שימוש ותרומה

כל הדוגמאות סינתטיות ורצות מקומית ללא קריאות למודל, רשת או כלים חיצוניים. אין להעלות מפתחות, שיחות אמיתיות, נתוני לקוחות או מידע ארגוני. הנחיות לתרומה נמצאות ב־[CONTRIBUTING.md](CONTRIBUTING.md).

קוד, טקסטים מקוריים ונתונים סינתטיים במאגר מופצים ברישיון [MIT](LICENSE).
