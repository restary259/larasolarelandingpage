# לָארה סולארה — אתר GitHub Pages

זהו העתק של האתר כפי שסופק, ללא Lovable badge / analytics. העלה את הקבצים ל־repo והפעל GitHub Pages.

מה לעשות:
1. עדכן קבצים:
   - החלף את `CNAME` בדומיין שלך (או מחק את הקובץ אם אין דומיין מותאם).
   - עדכן את `link rel="canonical"` ב־index.html לכתובת הפרודקשן שלך.
   - וודא שכל קבצי ה־assets (CSS, JS, images) נמצאים בתיקיית `/assets`.

2. שלח ל־main:
   - git add .
   - git commit -m "Deploy site to GitHub Pages"
   - git push origin main

3. בדוק:
   - אחרי ה‑push, ה־workflow יפרסם את האתר. עבור ל־Settings → Pages כדי לאמת את הכתובת וה‑HTTPS.

הערות אבטחה/ביצועים:
- אם תוסיף סקריפטים צד‑שלישי: העדיף טעינה מותנית וסקריפטים אסינכרוניים.
- הוסף Content-Security-Policy כותרת בשרת/hosting אם נחוץ.
- מיטב ביצועים: שים תמונות ב‑WebP/AVIF, הוסף width/height ל‑img, השתמש ב‑preload/preconnect עבור פונטים קריטיים.
