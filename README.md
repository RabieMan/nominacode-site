# NominaCode – אתר · Website

האתר הציבורי של **NominaCode**, נומרולוגיה של שמות בעברית, בערבית ובאנגלית, מבית [RabieMan Labs](https://rabieman.github.io/).
הקוד של האפליקציה נמצא בריפו פרטי. כאן יש רק את מה שחייב להיות ציבורי. האתר מתפרסם ב-GitHub Pages מ-`main`.

The public website of NominaCode. The app code lives in a private repo; this repo holds only the public pages.

## דפים · Pages

| דף · Page | שפות · Languages | כתובת · URL |
|---|---|---|
| דף הבית · Landing | עברית · العربية · English (בורר שפות) | https://rabieman.github.io/nominacode-site/ |
| מדיניות פרטיות · Privacy | he · ar · en (`?lang=he\|ar\|en`) | https://rabieman.github.io/nominacode-site/privacy.html |
| תנאי שימוש · Terms | he · ar · en | https://rabieman.github.io/nominacode-site/terms.html |
| הודעות צד שלישי · Notices | he · ar · en | https://rabieman.github.io/nominacode-site/licenses.html (הקישור נמצא בסוף דף התנאים) |

הקישור למדיניות הפרטיות הוא הקישור שמוזן ב-Play Console. האפליקציה פותחת את שלושת הדפים המשפטיים מתוך מסך "אודות", בשפה שנבחרה.

## תוכן · Content

- **קשר:** rabieman.labs+nominacode@gmail.com
- **סרטון:** YouTube `776AHPOZe34` ("לא רשום" עד החשיפה) מתחת לכותרת בכל שפה, עם תמונת שער מקומית `img/promo-poster.jpg`; נטען מ-youtube-nocookie רק בלחיצה, כך שהדף לא פונה ל-YouTube לפני כן (מוזכר גם במדיניות הפרטיות).
- **בורר שפות:** עברית · العربية · English בראש הדף, בסגול של האפליקציה, כמו באתר הבית: שפה אחת בכל פעם, נשמרת עם אותו מפתח `rl_lang` של rabieman.github.io; `?lang=he|ar|en` או `#ar` / `#en` פותחים שפה ישירות, והקישורים המשפטיים בתחתית עוברים באותה שפה.
- **תמונת שיתוף:** `img/og.jpg` (1200×630). היא נוצרת בריפו הפרטי עם `python3 tools/store_graphics.py` (`store/og-he.jpg`). אחרי שמחליפים אותה, מעלים את `?v=` בתגיות ה-OG ומרעננים ב-Facebook Sharing Debugger.
- **הדפים המשפטיים:** זהים לעותקים שבאפליקציה (`www/legal/`). כל שינוי נעשה בשני המקומות, ומעדכנים את תאריך "עודכן לאחרונה".

## סטטוס · Status

**בבדיקה סגורה ב-Google Play** (מנובמבר 2026). האתר ציבורי, ותג "בקרוב ב-Google Play" מופיע כאן ובכרטיס באתר הבית. בהשקה הציבורית: התג יוחלף בקישור לחנות (גם בתמונת השיתוף), והסרטון ביוטיוב יהפוך לציבורי.

## `img/`

`icon.png` · `rabieman-labs.webp` · `og.jpg` · צילומי מסך עם נתוני דמו – אותם ארבעה בכל שפה: `01-today` · `02-code` · `03-sky` · `04-names`, כל אחד ב-`-he.jpg`, ב-`-ar.jpg` וב-`-en.jpg`. הם נוצרים מאותו סקריפט Playwright מתוך `www/` של האפליקציה, באותו גודל (540×960).

---

© 2026 RabieMan Labs
