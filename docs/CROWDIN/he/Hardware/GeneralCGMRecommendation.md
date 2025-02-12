# המלצות כלליות של חיישנים רציפים (CGM)

## היגיינה

בכל מערכת חיישן שהיא, אם אתם מתכוונים להשתמש בכיול מבוסס דם, אז יש כמה כללים מאוד ברורים שצריך ליישם, בין אם משתמשים בתוכנות "עשה זאת בעצמך" או באפליקציות הרשמיות.

-   יש לוודא שהידיים והערכה נקיות.
-   נסו לכייל כשהסוכר יציב, כלומר שיש סדרה של נקודות עם חץ שטוח  (בדרך כלל מספיקות 15-30 דקות)
-   הימנעו מכיול כאשר רמות הסוכר נעות מעלה או מטה.
-   בצעו "מספיק" כיולים - באפליקציות רשמיות, תתבקשו   לבצע בדיקות פעם או פעמיים ביום. במערכות עשה זאת בעצמך ייתכן שלא תתבקשו והיזהרו משימוש ללא כיולים.
-   אם אפשר, כיילו עם חלק מהקריאות שלך בטווח נמוך יותר (72-90 מ"ג/ד"ל) וחלק ברמה קצת יותר גבוהה (126-160 מ"ג/ד"ל) כי כך מסופק טווח טוב יותר עבור כיול הנקודה\שיפוע.

## הדבקת חיישן Dexcom G6

בעת החדרת החיישן, מומלץ לא ללחוץ חזק מדי על מכשיר ההחדרה על מנת למנוע דימום. חוט החיישן לא אמור לבוא במגע עם דם.

לאחר החדרת החיישן, ניתן ללחוץ את המשדר לתוך החיישן. זהירות! תחילה הרכיבו את הצד המרובע ולאחר מכן לחצו כלפי מטה על הצד העגול.

## פתרון בעיות

### בעיה בחיבור

חיבור הבלוטות' עלול להיות מופרע על ידי התקני בלוטות' אחרים בקרבת מקום כגון מדי סוכר בדם, אוזניות, טאבלטים או מכשירי מטבח כגון תנורי מיקרוגל או כיריים קרמיות. במקרה זה xDrip לא יציג ערכי סוכר. כאשר חיבור הבלוטות' מתייצב מחדש, הנתונים החסרים נטענים בחזרה.

### שגיאות חיישן

אם מתרחשות שגיאות חוזרות בחיישן, נסו לבחור אתר אחר בגוף כדי להחדיר בו את החיישן. חוט החיישן לא אמור לבוא במגע עם דם.

לעתים קרובות ניתן לתקן "שגיאת חיישן" על ידי שתייה מיידית ועיסוי סביב החיישן!

### ערכים קופצניים

ניתן להחיל הגדרות לחסימת רעש ב-xDrip (הגדרות - הגדרות לשיתוף פעולה בין יישומים - חסימת רעש) לקריאה נוספת [כאן](../Usage/Smoothing-Blood-Glucose-Data-in-xDrip.md).

### גיל חיישן שלילי

![גיל חיישן שלילי](../images/Troubleshooting_SensorAge.png)

זה מתרחש אם יש ערך כפול של "הכנסת חיישן CGM" ב[לשונית\תפריט פעולות](../Configuration/Config-Builder#actions) או הוספת חיישן עם תאריך שגוי. עברו ללשונית טיפולים > פורטל הטיפולים ומחקו את הערך השגוי.
