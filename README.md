# Cartoon Studio

تطبيق Android مبني باستخدام .NET MAUI لإنشاء رسوم كرتونية وحلقات ومشاهد.

## محتويات الحزمة المصدرية
الحزمة الأصلية `CartoonStudio_AllPhases.zip` تحتوي على:
- إدارة المسلسلات والحلقات والشخصيات.
- محرر المشاهد والحركات.
- خدمات الصوت وقراءة WAV.
- محرك التحريك والرسم.
- تصدير الفيديو على Android.

## متطلبات البناء
- Visual Studio 2022 مع .NET MAUI.
- Android workload.
- حزم NuGet: sqlite-net-pcl 1.9.172، SQLitePCLRaw.bundle_green 2.1.8، SkiaSharp.Views.Maui.Controls 2.88.8، SkiaSharp.HarfBuzz 2.88.8، Plugin.Maui.Audio 3.0.1.

> ملاحظة: ملفات المصدر الأصلية وصلت كأرشيف ZIP منفصل، ويجب إضافتها إلى هذا المستودع قبل أن يصبح المشروع قابلاً للبناء. كما أن الحزمة لا تتضمن ملف المشروع `.csproj` أو ملفات منصة Android.
