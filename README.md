# رواق | Riwaq

**رواق — تطبيق سطح مكتب سريع وبسيط لاستعراض وسائطك.**
**Riwaq — a fast, simple desktop gallery for your media.**

---

## حالة المشروع / Project Status

> **العربية**: البرنامج في مرحلة التطوير، والمطوّر ما زال يتعلم راست، لذلك الكود الحالي
> لا يرقى لمستوى النشر العام، وبعض الميزات لا تعمل بعد (مثل إنشاء الألبومات وقوائم التشغيل
> والنقل المتقدم). فور توفر نسخة مستقرة سيتم نشر الكود المصدري بالكامل.
>
> **English**: This project is under active development and the developer is still learning Rust,
> so the current code is not up to public-release standards, and some features do not work
> yet (e.g. album creation, playlists, and advanced transfer).
> The full source code will be published once a stable version is ready.

---

## التنزيلات / Downloads

الحزم المتوفرة حالياً للينكس فقط / Currently Linux only:

| الحزمة | التثبيت |
|---|---|
| [Riwaq_0.1.0_amd64.AppImage](../../releases) | `chmod +x Riwaq_0.1.0_amd64.AppImage && ./Riwaq_0.1.0_amd64.AppImage` |
| [Riwaq_0.1.0_amd64.deb](../../releases) | `sudo dpkg -i Riwaq_0.1.0_amd64.deb` |
| [Riwaq-0.1.0-1.x86_64.rpm](../../releases) | `sudo rpm -i Riwaq-0.1.0-1.x86_64.rpm` |

> يتطلب وجود `ffmpeg` مثبتاً في النظام لاستخراج مصغرات الفيديو ومدة الوسائط.
>
> Requires `ffmpeg` installed on the system for video thumbnails and media durations.

---

## المزايا / Features

- **مصغرات حقيقية**: إطار من الفيديو وغلاف مدمج للصوتيات عبر ffmpeg، مع تخزين مؤقت سريع في `~/.riwaq/thumbs/`
- **تشغيل مباشر**: بث الفيديو والصوت عبر خادم محلي مدمج يدعم استكمال التحميل (Range)
- **مشغل صوتيات**: شريط سفلي دائم مع قائمة تشغيل من المعروض حالياً
- **تنظيم**: ألبومات، مفضلة، سلة محذوفات، وشارة «جديد» على الملفات التي لم تُفتح بعد
- **بحث وفرز**: بالاسم والنوع والتاريخ والحجم
- **تحديث تلقائي**: فحص صامت دوري يعيد بناء القوائم عند تغيّر محتوى المجلدات
- **ثنائي اللغة**: عربي (RTL) وإنجليزي.
- **خصائص الملف**: نافذة معلومات، فتح بالتطبيق الافتراضي، إظهار في مدير الملفات

---

- **Real thumbnails**: actual video frames and embedded audio covers via ffmpeg, cached in `~/.riwaq/thumbs/`
- **Built-in playback**: local streaming server with HTTP Range support for smooth seeking
- **Audio player**: persistent bottom bar with a playlist of what's currently displayed
- **Organization**: albums, favorites, trash, and a "new" badge for unopened files
- **Search & sort**: by name, type, date, and size
- **Auto refresh**: silent periodic scan keeps lists in sync with the disk
- **Bilingual**: Arabic (RTL) and English.
- **File tools**: properties dialog, open with default app, reveal in file manager

---

## الصيغ المدعومة / Supported Formats

### الصور / Images
JPG · JPEG · PNG · GIF · BMP · WebP · SVG · TIFF

### الفيديو / Video
MP4 · AVI · MKV · MOV · WMV · FLV · WebM · M4V

### الصوتيات / Audio
MP3 · WAV · FLAC · AAC · OGG · WMA · M4A

---

## الدعم / Support

للأخطاء والاقتراحات: [Issues](../../issues)
For bugs and suggestions: [Issues](../../issues)

