# קרן סיוע – מערכת ניהול

מערכת לניהול מעשרות, הלוואות, פדיון והכנסות.

## התקנה כאפליקציה

1. פתח את הקישור ב-GitHub Pages
2. לחץ על "הוסף למסך הבית" בדפדפן
3. האפליקציה תותקן כ-PWA

## העלאה ל-GitHub Pages

1. צור repository חדש ב-GitHub
2. העלה את כל הקבצים:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png` ו-`icon-512.png`
   - `.nojekyll`
3. הכנס ל-Settings → Pages → Branch: main → Save
4. האתר יהיה זמין בכתובת: `https://[username].github.io/[repo-name]`

## גיבוי נתונים

הנתונים נשמרים מקומית בדפדפן (localStorage).
להעברה בין מכשירים: הגדרות → ייצוא JSON → שמור
במכשיר החדש: הגדרות → ייבוא JSON
