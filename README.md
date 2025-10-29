# 📀 مكتبة نسخ الآيزو

> دليل عملي ومكتبة مرتّبة لأفضل أنظمة التشغيل والأدوات بصيغة ISO

---

## 🚦 نصائح سريعة قبل أي تحميل (احفظها!)
- لا تثبّت على هاردك الحقيقي قبل التجربة على VM أو Live USB
- نزّل فقط من المواقع الرسمية، وابتعد عن أي روابط عشوائية
- تأكد من الهاش SHA256 لكل ملف قبل الحرق
- خذ نسخة احتياطية قبل أي تجربة، ولا تلعب بأقسام القرص عشوائيًا
- استخدم Ventoy لإدارة عدة ISOs على فلاش واحدة، وRufus للحالات المتقدمة
- جرّب، خرب، ارجع Snapshot… التجربة أهم من الكمال

---

## ⭐ أفضل 15 نسخة ISO (جدول Grid عصري)
> مختارة للمبتدئين والمحترفين: لينكس، ويندوز، إنقاذ، وهجينة. لكل بند: الاسم والرابط الرسمي، النوع، لمحة سريعة، ولماذا أنصح بها.

<style>
/***** تنسيق جدول شبكي أنيق يعمل داخل GitHub (مدمج في Markdown) *****/
.grid { display: grid; gap: 8px; }
.grid.head { grid-template-columns: 80px 1.2fr 0.9fr 1.4fr 1.2fr; font-weight: 700; }
.grid.row { grid-template-columns: 80px 1.2fr 0.9fr 1.4fr 1.2fr; }
.cell { padding: 10px; border: 1px solid #e5e7eb; border-radius: 8px; background: #fff; }
.cell.title a { font-weight: 700; text-decoration: none; }
.badge { display:inline-block; padding:2px 8px; border-radius:999px; font-size:12px; background:#f1f5f9; }
.note { color:#334155; font-size: 14px; }
@media (prefers-color-scheme: dark) {
  .cell { background:#0b1020; border-color:#1f2937; }
  .note { color:#cbd5e1; }
}
</style>

<div class="grid head">
  <div class="cell">الأيقونة</div>
  <div class="cell">الاسم + رابط التحميل</div>
  <div class="cell">نوع النظام</div>
  <div class="cell">لمحة سريعة / مميزات</div>
  <div class="cell">لماذا أنصح بها</div>
</div>

<div class="grid row">
  <div class="cell">🐧</div>
  <div class="cell title"><a href="https://ubuntu.com/download">Ubuntu 24.04 LTS</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">واجهة GNOME ودعم طويل</div>
  <div class="cell note">أسهل بداية وثبات 5 سنوات، مجتمع ضخم</div>
</div>
<div class="grid row">
  <div class="cell">🟢</div>
  <div class="cell title"><a href="https://linuxmint.com/download.php">Linux Mint 22 (Cinnamon)</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">سطح مكتب قريب لويندوز، مبني على أوبونتو</div>
  <div class="cell note">انتقال سلس من ويندوز بدون مفاجآت</div>
</div>
<div class="grid row">
  <div class="cell">🧪</div>
  <div class="cell title"><a href="https://getfedora.org/">Fedora 41</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">تقنيات حديثة وتحديثات سريعة</div>
  <div class="cell note">تجربة نظيفة للمطورين ومحبي الأحدث</div>
</div>
<div class="grid row">
  <div class="cell">🧱</div>
  <div class="cell title"><a href="https://www.debian.org/distrib">Debian 12 Bookworm</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">أساس اللينكس المستقر</div>
  <div class="cell note">صلابة واستقرار مثالي للعمل والإنتاج</div>
</div>
<div class="grid row">
  <div class="cell">🧗</div>
  <div class="cell title"><a href="https://archlinux.org/download">Arch Linux (Rolling)</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">ابنِ النظام بنفسك خطوة بخطوة</div>
  <div class="cell note">تحكم كامل وتعلم عميق للمحترفين</div>
</div>
<div class="grid row">
  <div class="cell">🚀</div>
  <div class="cell title"><a href="https://endeavouros.com/latest-release/">EndeavourOS 2025.x</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">Arch جاهز بالتثبيت (KDE/XFCE)</div>
  <div class="cell note">قوة Arch بدون ألم البداية، مجتمع مساعد</div>
</div>
<div class="grid row">
  <div class="cell">🖥️</div>
  <div class="cell title"><a href="https://get.opensuse.org/tumbleweed/">openSUSE Tumbleweed</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">متجدد مع لقطات وYaST</div>
  <div class="cell note">لقطات ترجعك لبر الأمان، أدوات قوية</div>
</div>
<div class="grid row">
  <div class="cell">🎮</div>
  <div class="cell title"><a href="https://pop.system76.com/">Pop!_OS 22.04</a></div>
  <div class="cell"><span class="badge">لينكس</span></div>
  <div class="cell note">صديق للألعاب وتعريفات NVIDIA</div>
  <div class="cell note">تجربة لعب جاهزة من الصندوق</div>
</div>
<div class="grid row">
  <div class="cell">🪟</div>
  <div class="cell title"><a href="https://www.microsoft.com/software-download/windows11">Windows 11 24H2</a></div>
  <div class="cell"><span class="badge">ويندوز</span></div>
  <div class="cell note">ويندوز حديث مع متطلبات TPM 2.0</div>
  <div class="cell note">الأفضل للأجهزة الحديثة وتوافق واسع</div>
</div>
<div class="grid row">
  <div class="cell">🪟</div>
  <div class="cell title"><a href="https://www.microsoft.com/software-download/windows10">Windows 10 22H2</a></div>
  <div class="cell"><span class="badge">ويندوز</span></div>
  <div class="cell note">إصدار مستقر وواسع التوافق</div>
  <div class="cell note">أنسب للأجهزة الأقدم وأخف من 11</div>
</div>
<div class="grid row">
  <div class="cell">🛡️</div>
  <div class="cell title"><a href="https://www.kali.org/get-kali/">Kali Linux 2025.3</a></div>
  <div class="cell"><span class="badge">أمنية</span></div>
  <div class="cell note">منصة اختبار اختراق</div>
  <div class="cell note">أدوات جاهزة للهكر الأخلاقي (استخدم قانونيًا) ⚠️</div>
</div>
<div class="grid row">
  <div class="cell">🦜</div>
  <div class="cell title"><a href="https://parrotsec.org/download/">Parrot Security 6.x</a></div>
  <div class="cell"><span class="badge">أمنية</span></div>
  <div class="cell note">خفيفة مع تركيز على الخصوصية</div>
  <div class="cell note">بديل أخف من Kali وبواجهة لطيفة</div>
</div>
<div class="grid row">
  <div class="cell">🆘</div>
  <div class="cell title"><a href="https://www.hirensbootcd.org/download/">Hiren's BootCD PE 1.0.8</a></div>
  <div class="cell"><span class="badge">إنقاذ</span></div>
  <div class="cell note">إنقاذ ويندوز وأدوات إصلاح شاملة</div>
  <div class="cell note">لازمة لأي فني صيانة، تنقذك وقت الكوارث</div>
</div>
<div class="grid row">
  <div class="cell">💽</div>
  <div class="cell title"><a href="https://www.ventoy.net/en/download.html">Ventoy (USB Multi-ISO)</a></div>
  <div class="cell"><span class="badge">هجين</span></div>
  <div class="cell note">تشغيل عدة ISOs من فلاش واحدة</div>
  <div class="cell note">يوفر وقتك ومساحتك، مثالي للتجارب</div>
</div>
<div class="grid row">
  <div class="cell">💠</div>
  <div class="cell title"><a href="https://chromeenterprise.google/os/chromeosflex/">ChromeOS Flex</a></div>
  <div class="cell"><span class="badge">هجين</span></div>
  <div class="cell note">كروم أو إس للأجهزة القديمة</div>
  <div class="cell note">ينعش اللابتوبات الضعيفة للاستعمال الخفيف والويب</div>
</div>

> إضافي لهواة التجربة: <a href="https://www.android-x86.org/download">Android-x86</a>

---

## 📊 فهرس الأنظمة (توزيعات/أدوات فرعية مقترحة)
- 🦅 Garuda Linux — توزيعة Arch جاهزة بالأداء والألعاب (BTRFS وZen Kernel). رابط: https://garudalinux.org/downloads.html
- 🕹️ Nobara — مشتقة من Fedora مُحسّنة للألعاب ووسائط الملتيميديا. رابط: https://nobaraproject.org/
- 🛟 Rescatux — إنقاذ وإصلاح إقلاع لينكس/ويندوز بسهولة. رابط: https://www.rescatux.org/
- 🐺 MX Linux — خفيفة ومستقرة مبنية على Debian مع أدوات رسومية ممتازة. رابط: https://mxlinux.org/download-links/
- 🧵 TinyCore — خفيفة جدًا (Core/ TinyCore) للتجارب والأجهزة القديمة. رابط: http://tinycorelinux.net/downloads.html
- 🧷 Slax — توزيعة محمولة خفيفة جدًا تعمل من USB. رابط: https://www.slax.org/download.php

---

## 🎯 ملاحظات أخيرة
- للمبتدئين: ابدأ بـ Ubuntu أو Linux Mint، وجرب على VM أولًا
- للمتقدمين: حدّث هذا الملف عند إضافة ISOs وشارك خبرتك
- تحذير: لا تحميل من مواقع مشبوهة، وتحقق من الهاش دائمًا، وخذ Backup

**Happy Computing! 🚀**
