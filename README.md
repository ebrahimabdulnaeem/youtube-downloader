# YouTube Downloader

تطبيق ويب لتحميل مقاطع فيديو YouTube بجودات مختلفة.

## المتطلبات

- Node.js (v14 أو أحدث)
- npm (v6 أو أحدث)

## التثبيت

1. استنسخ المستودع:
```bash
git clone https://github.com/ebrahimabdulnaeem/youtube-downloader.git
cd youtube-downloader
```

2. قم بتثبيت تبعيات الخادم:
```bash
cd server
npm install
```

3. قم بتثبيت تبعيات الواجهة الأمامية:
```bash
cd ../client
npm install
```

4. أضف مفتاح YouTube API:
- قم بإنشاء ملف `.env` في مجلد `server`
- أضف المتغير البيئي التالي:
```
YOUTUBE_API_KEY=your_api_key_here
```

## تشغيل التطبيق

1. تشغيل الخادم:
```bash
cd server
npm start
```

2. تشغيل الواجهة الأمامية (في نافذة طرفية جديدة):
```bash
cd client
npm start
```

سيتم فتح التطبيق تلقائياً في متصفحك على العنوان `http://localhost:3000`

## المميزات

- تحميل مقاطع فيديو YouTube بجودات مختلفة
- عرض معلومات الفيديو (العنوان، الوصف، عدد المشاهدات، إلخ)
- واجهة مستخدم سهلة الاستخدام
- دعم اللغة العربية 