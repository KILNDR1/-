/* تطبيق box-sizing لجميع العناصر */
* {
    box-sizing: border-box;
}

/* تنسيق الجسم */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    direction: rtl;
    text-align: right;
    margin: 0;
    padding: 0;
}

/* تنسيق الرأس */
header {
    background-color: #4CAF50;
    color: #fff;
    padding: 20px;
    text-align: center;
    display: flex;
    justify-content: center; /* لضبط العناصر في الوسط */
    align-items: center; /* لضبط محاذاة العناصر رأسياً */
}

/* تنسيق الروابط في شريط التنقل */
nav a {
    margin: 0 15px;
    color: #fff;
    text-decoration: none;
    display: inline-block; /* لضبط الروابط بشكل صحيح */
}

/* تنسيق الأقسام */
section {
    padding: 20px;
    background-color: #fff;
    margin: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* تنسيق العناوين */
h2 {
    color: #4CAF50;
}

/* تنسيق الأزرار */
button {
    background-color: #4CAF50;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease; /* إضافة تأثير التغيير عند التمرير */
}

/* التأثير عند تمرير الفأرة على الأزرار */
button:hover {
    background-color: #45a049;
}
