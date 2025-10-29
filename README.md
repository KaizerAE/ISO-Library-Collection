# 📀 ISO Library Collection — مكتبة نسخ الآيزو

A curated, bilingual catalog of operating system ISO images with practical notes, checksums, and usage tips.

فهرس ثنائي اللغة لصور أنظمة التشغيل (ISO) مع ملاحظات عملية، وقيم تحقق، ونصائح استخدام.

---

## 🔰 About — حول المكتبة
- Purpose: centralize ISO knowledge for installs, recovery, testing, and VMs.
- الهدف: توحيد معلومات نسخ ISO للتثبيت والاستعادة والاختبار والأنظمة الوهمية.
- Scope: popular Linux, Windows, Android-x86, hypervisor/rescue tools, and more.
- النطاق: توزيعات لينكس وويندوز وAndroid-x86 وأدوات إنقاذ ومحاكاة وغيرها.

---

## 📚 How to Use — طريقة الاستخدام
1) Verify integrity (SHA256/GPG) before booting or deploying.
   - تحقق من سلامة الملف (SHA256/GPG) قبل الإقلاع أو التثبيت.
2) Prefer official mirrors/CDNs and avoid third-party repacks.
   - استخدم الروابط الرسمية وتجنب النسخ المعدّلة.
3) Keep a USB toolkit (Ventoy/Rufus/Etcher) and label versions clearly.
   - احتفظ بأداة USB مثل Ventoy/Rufus وسمّ النسخ بوضوح.
4) Test in a VM first when uncertain; snapshot often.
   - جرّب في آلة افتراضية عند الشك وخذ لقطات محفوظة.
5) Document changes; update this README when adding ISOs.
   - وثّق التغييرات وحدّث هذا الملف عند الإضافة.

---

## 🧭 Quick Search and Filters — البحث السريع والتصنيف
- Search by: Name, Version, Kernel, Desktop, Arch (x86_64/ARM), Use-case.
- ابحث بالاسم والإصدار والنواة وبيئة سطح المكتب والمعمارية والاستخدام.
- Suggested tags: desktop, server, lightweight, gaming, security, edu, OEM, rolling.
- وسوم مقترحة: سطح_مكتب، خادم، خفيف، ألعاب، أمن، تعليمي، مصنع، متجدد.

Tip: Use your editor’s table search (Ctrl/Cmd+F) to filter rows.
نصيحة: استخدم بحث المحرّر لتصفية الصفوف بسرعة.

---

## 🗂️ ISO Catalog — فهرس النسخ

Legend — الأسطورة:
- Arch: x86_64, aarch64, armhf, i686
- Desktop: GNOME, KDE, XFCE, Cinnamon, LXQt, etc.
- Type: Desktop/Server/Minimal/Rescue/Hypervisor

| Name | Version / Date | Architecture | Desktop / Type | Brief Description (EN) | الوصف المختصر (AR) | Personal Notes (EN/AR) |
|---|---|---|---|---|---|---|
| Ubuntu | 24.04.1 LTS (Noble) | x86_64, aarch64 | GNOME (Desktop/Server) | Long-term support Ubuntu with strong ecosystem and snaps | أوبونتو بدعم طويل ونظام بيئي قوي وحزم Snap | Great defaults; consider minimal install to avoid bloat — يفضل التثبيت المصغّر |
| Ubuntu | 22.04.5 LTS | x86_64, aarch64 | GNOME (Desktop/Server) | Stable LTS widely supported by vendors | إصدار LTS مستقر ومدعوم على نطاق واسع | Good for production servers — مناسب للخوادم |
| Kubuntu | 24.04 | x86_64 | KDE Plasma (Desktop) | Ubuntu base with polished KDE experience | قاعدة أوبونتو مع تجربة KDE مصقولة | Smooth on mid/high-end — سلس على الأجهزة المتوسطة/العليا |
| Xubuntu | 24.04 | x86_64 | XFCE (Light Desktop) | Lightweight Ubuntu flavor for older PCs | نكهة خفيفة لأجهزة قديمة | Fast on HDDs — سريع على الأقراص التقليدية |
| Fedora Workstation | 41 | x86_64, aarch64 | GNOME (Desktop) | Cutting-edge GNOME, Wayland-first, fast updates | أحدث الميزات مع تحديثات سريعة | Great dev box; watch for ABI changes — ممتاز للمطورين |
| Fedora Server | 41 | x86_64, aarch64 | Server | Modern server platform with Cockpit | منصة خادم حديثة مع Cockpit | Cockpit is a plus — واجهة Cockpit ميزة مهمة |
| Arch Linux | 2025.10 (rolling) | x86_64 | Minimal | DIY rolling distro with pacman | توزيعة متجددة موجهة للمستخدم المتقدم | Use archinstall; read wiki — استخدم archinstall وويكي |
| Manjaro | 24.x | x86_64 | KDE/GNOME/XFCE | User-friendly Arch-based with curated repos | مبنية على Arch بواجهة أسهل | Good hardware detection — كشف عتاد جيد |
| Linux Mint | 22 (Wilma) | x86_64 | Cinnamon/MATE/XFCE | Ubuntu-based, traditional desktop | مبني على أوبونتو بسطح مكتب تقليدي | Stable and beginner-friendly — مناسب للمبتدئين |
| openSUSE Tumbleweed | rolling | x86_64, aarch64 | KDE/GNOME | Rolling with Snapper + Btrfs | متجدد مع Snapper وBtrfs | Snapper saves time — لقطات النظام مفيدة |
| openSUSE Leap | 15.6 | x86_64 | KDE/GNOME | Stable, enterprise-aligned | مستقر وموجّه للمؤسسات | Good for servers — مناسب للخوادم |
| Debian | 12.7 (Bookworm) | x86_64, aarch64 | GNOME/XFCE/etc. | Rock-solid, huge repos | مستقرة جدًا ومستودعات ضخمة | Prefer netinst for control — netinst يعطي تحكمًا أكبر |
| Kali Linux | 2024.3 | x86_64, arm | Security | Pen-testing distro with many tools | توزيعة اختبار اختراق بأدوات كثيرة | Use VM/USB, legal use only — للاستخدام القانوني فقط |
| EndeavourOS | 2024.x | x86_64 | KDE/XFCE/GNOME | Friendly Arch installer and defaults | أداة تثبيت ودودة لبيئة Arch | Good balance of control/ease — توازن جيد |
| Zorin OS | 17 | x86_64 | GNOME-based | Windows-like UX on Ubuntu base | تجربة تشبه ويندوز على أوبونتو | Easy switch for newcomers — انتقال سهل |
| Elementary OS | 7.1 | x86_64 | Pantheon | Design-focused, minimal | تركيز على التصميم والبساطة | Beautiful but opinionated — جميل لكنه تقليدي |
| Pop!_OS | 22.04 LTS | x86_64 | GNOME/COSMIC | Dev/gaming friendly with tiling | مناسب للمطورين والألعاب | Great on NVIDIA — ممتاز مع بطاقات إنفيديا |
| AlmaLinux | 9.4 | x86_64, aarch64 | Server | RHEL-compatible community rebuild | متوافق مع RHEL | Strong RHEL alternative — بديل قوي |
| Rocky Linux | 9.4 | x86_64, aarch64 | Server | RHEL downstream enterprise OS | نظام مؤسسي مشتق من RHEL | Solid for prod — مناسب للإنتاج |
| Proxmox VE | 8.3 | x86_64 | Hypervisor | Debian-based virtualization with ZFS | محاكٍ يعتمد على Debian مع ZFS | Great homelab choice — ممتاز للمختبر المنزلي |
| VMware ESXi | 8.0u3 | x86_64 | Hypervisor | Bare-metal hypervisor | محاكي افتراضي على العتاد مباشرة | License caveats — اعتبارات الترخيص |
| Windows 11 | 24H2 | x86_64, ARM64 | Desktop | Latest Windows with Copilot+ features | أحدث ويندوز بميزات جديدة | Use official tool; TPM 2.0 req — استخدم الأداة الرسمية |
| Windows 10 | 22H2 | x86_64 | Desktop | Mature Windows with broad app support | ويندوز ناضج بدعم واسع للتطبيقات | Extended support cycles — دورات دعم ممتدة |
| ChromeOS Flex | 2025.xx | x86_64 | Desktop/Cloud | ChromeOS for PCs (no Android apps) | ChromeOS للحواسيب (بدون تطبيقات أندرويد) | Great for old laptops — ممتاز للأجهزة القديمة |
| FydeOS | 17.x | x86_64 | Desktop | ChromiumOS variant with Android support | نسخة ChromiumOS بدعم أندرويد | Good for apps testing — مناسب للتجارب |
| Remix OS (legacy) | 3.x | x86_64 | Desktop | Android-x86 with desktop paradigm | أندرويد-إكس86 بواجهة مكتبية | Legacy, use for demos — قديم للتجارب فقط |
| Android-x86 | 9.0/8.1 | x86_64 | Desktop/Mobile | Android port for PCs | أندرويد للحواسيب | Hardware varies — التوافق يختلف |
| Hiren’s BootCD PE | 1.0.8 | x86_64 | Rescue | Windows PE-based rescue toolkit | أدوات إنقاذ مبنية على WinPE | Must-have USB — أداة أساسية |
| Ventoy | 1.0.xx | x86_64 | Tool | Multi-ISO boot tool | أداة إقلاع متعددة ISO | Simplifies ISO library — تسهل الإدارة |

Add more rows as your collection grows.
أضف المزيد من الصفوف مع توسع المكتبة.

---

## 🔗 Official Download Links — روابط التحميل الرسمية
- Ubuntu: https://ubuntu.com/download
- Fedora: https://getfedora.org
- Arch: https://archlinux.org/download
- Debian: https://www.debian.org/distrib
- openSUSE: https://get.opensuse.org
- Linux Mint: https://linuxmint.com/download.php
- Kali: https://www.kali.org/get-kali/
- Manjaro: https://manjaro.org/downloads
- AlmaLinux: https://almalinux.org
- Rocky: https://rockylinux.org
- Proxmox: https://www.proxmox.com/en/downloads
- Windows: https://www.microsoft.com/software-download/
- ChromeOS Flex: https://chromeenterprise.google/os/chromeosflex/
- Android-x86: https://www.android-x86.org

---

## 🧪 Verification — التحقق
- Always compare SHA256 against publisher checksums; verify GPG signatures when provided.
- قارن قيمة SHA256 مع الموقع الرسمي وتحقق من توقيع GPG إن توفر.
- Useful tools: sha256sum, shasum -a 256, certutil -hashfile, gpg.
- أدوات مفيدة: sha256sum و gpg و certutil.

Example — مثال:
```
sha256sum ubuntu-24.04.1-desktop-amd64.iso
curl -fsSLO https://releases.ubuntu.com/24.04/SHA256SUMS
gpg --verify SHA256SUMS.gpg SHA256SUMS
```

---

## 🧰 USB Creation — إنشاء USB قابل للإقلاع
- Ventoy: copy ISOs to the USB once; boot and choose.
- Ventoy: انسخ ملفات ISO إلى الفلاشة مرة واحدة ثم اختر الإقلاع منها.
- Rufus/Etcher: write single ISO per drive; select GPT/UEFI as needed.
- Rufus/Etcher: كتابة ISO واحد لكل فلاشة؛ اختر GPT/UEFI حسب الحاجة.

---

## 🗃️ Organization Ideas — أفكار التنظيم
- Folder scheme: OS/Family/Version/Arch (e.g., Linux/Ubuntu/24.04/x86_64).
- هيكل المجلدات: نظام/العائلة/الإصدار/المعمارية.
- Keep a checksums.txt per folder; add NOTES.md for personal remarks.
- احتفظ بملف checksums.txt وملف NOTES.md للملاحظات.

---

## ⚖️ Legal — ملاحظات قانونية
This repository contains documentation only; no ISO files are hosted here. Respect licenses and trademarks.
هذا المستودع توثيقي فقط؛ لا يستضيف أي ملفات ISO. احترم التراخيص والعلامات التجارية.

---

## 👤 Maintainer — المشرف
- Owner: KaizerAE
- Last Updated: October 2025
- Contact: Open an issue for suggestions and improvements.
- للتواصل: افتح بلاغًا بالمقترحات والتحسينات.
