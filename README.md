# Daily Employee Tasks Survey

This repository contains the survey form for daily tasks reporting by employees at the Regional Health Command & Control Center - Jeddah Health.

## Project Contents

- `index.html`: The survey web page with a simple design and support for adding multiple tasks.
- Survey banner image: `WhatsApp-Image-2025-09-25-at-08.38.59.jpg`
- The form submits data to a Google Apps Script Web App for processing and storing data in a Google Sheet.

## Features

- Support for multiple daily tasks with descriptions.
- Password protection for submissions.
- Employee whitelist verification via Google Apps Script.
- User notifications for successful submissions or errors (wrong password or unauthorized employee).
- Hosted on GitHub Pages for easy access.

## Setup and Deployment

1. Host this repository using GitHub Pages (serving `index.html` by default).
2. Update the Google Apps Script Web App URL inside `index.html`’s form `action`.
3. Publish the Google Apps Script as a Web App with "Anyone, even anonymous" permission for public access.
4. Password and authorized employees list are managed in the Google Apps Script `doPost` function for validation.

## Google Apps Script Publishing

- Data processing is handled by a Google Apps Script connected to a Google Sheets spreadsheet.
- This repo provides the front-end; the Apps Script Web App serves as backend.

## How to Use

- Employees visit the survey page hosted on GitHub Pages.
- They enter their name, unit, date, password, and daily tasks.
- Server-side validation is performed with Google Apps Script.
- Data is securely stored in Google Sheets.

---

If you have any questions or need additional support, please feel free to reach out.

---

# استبيان المهام اليومية للموظفين

هذا المستودع يحتوي على نموذج استبيان للمهام اليومية للموظفين في المركز الإقليمي الصحي للقيادة والتحكم - جدة الصحية.

## محتويات المشروع

- `index.html`: صفحة الويب الخاصة بالاستبيان مع تصميم بسيط ودعم لإضافة مهام متعددة.
- صورة شعار الاستبيان: `WhatsApp-Image-2025-09-25-at-08.38.59.jpg`
- يرسل النموذج البيانات إلى تطبيق Google Apps Script لمعالجة وتخزين البيانات في جدول بيانات جوجل.

## الخصائص

- دعم إضافة مهام متعددة مع وصف لكل مهمة.
- حماية بكلمة سر للإرسال.
- التحقق من قائمة الموظفين المصرح لهم عبر Google Apps Script.
- إشعارات المستخدم في حالة نجاح الإرسال أو وجود خطأ في كلمة السر أو اسم الموظف.
- استضافة الصفحة على GitHub Pages لسهولة الوصول.

## الإعداد والتشغيل

1. استضافة هذا المستودع باستخدام GitHub Pages (سيتم استدعاء `index.html` تلقائيًا).
2. تحديث رابط Google Apps Script في خاصية `action` داخل ملف `index.html`.
3. نشر Google Apps Script كـ Web App مع صلاحية "الجميع، حتى من لم يسجلوا الدخول".
4. إدارة كلمة السر وقائمة الموظفين المصرح لهم داخل دالة `doPost` في Google Apps Script.

## نشر Google Apps Script

- تتم معالجة البيانات عبر Google Apps Script المرتبط بجدول بيانات Google Sheets.
- هذا المستودع عبارة عن الواجهة الأمامية، وتطبيق Google Apps Script يخدم كخلفية.

## كيفية الاستخدام

- يقوم الموظفون بزيارة صفحة الاستبيان المستضافة على GitHub Pages.
- يقومون بإدخال اسم الموظف، الوحدة، التاريخ، كلمة السر، والمهام اليومية.
- يتم التحقق من صحة الإدخال في خادم Google Apps Script.
- يتم تخزين البيانات بأمان في Google Sheets.

---

إذا كان لديك أي استفسارات أو تحتاج دعم إضافي، لا تتردد في التواصل معي.
