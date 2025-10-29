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
| Fedora Workstation | 41 | x86_64, aarch64 | GNOME (Desktop) | Cutting-edge Fedora with Wayland defaults | فيدورا حديثة مع Wayland افتراضيًا | Great for devs; toolbox/distrobox — ممتاز للمطورين |
| Fedora Server | 41 | x86_64, aarch64 | Server | Server edition with Cockpit and SELinux | نسخة خادم مع Cockpit وSELinux | Solid for lab/VMs — مناسب للمعامل |
| Arch Linux | 2025-10-01 | x86_64 | Minimal/Rolling | DIY rolling-release, pacman and AUR | نظام متجدد بتركيب يدوي وAUR | Use guided installer archinstall — استخدم archinstall |
| Manjaro | 24.x | x86_64 | KDE/GNOME/XFCE (Desktop) | User-friendly Arch-based distro | توزيعة سهلة مبنية على Arch | Delayed updates; stable branch — تحديثات مؤجلة |
| Linux Mint | 22 (Wilma) | x86_64 | Cinnamon/MATE/XFCE | Ubuntu-based, classic desktop UX | مبنية على أوبونتو بواجهة تقليدية | Great for newcomers — ممتاز للمبتدئين |
| openSUSE Tumbleweed | Rolling (2025-10) | x86_64, aarch64 | KDE/GNOME | Rolling with snapshots via Btrfs + Snapper | متجدد مع لقطات Btrfs | YaST/rollback friendly — رجوع سريع |
| openSUSE Leap | 15.6 | x86_64 | KDE/GNOME (Stable) | Enterprise-aligned openSUSE | أوبن سوزه مستقر ومتوافق مع المؤسسات | Predictable updates — تحديثات متوقعة |
| Debian | 12.7 (Bookworm) | x86_64, aarch64, armhf, i386 | GNOME/XFCE/Cinnamon | Universal OS, stable base for many distros | نظام عالمي مستقر | Great server baseline — أساس خوادم قوي |
| Kali Linux | 2025.3 | x86_64, aarch64 | Security/Forensics | Pen-testing distribution by Offensive Security | توزيعة اختبار اختراق | Use in lab; legal/ethics first — للاستخدام القانوني فقط |
| EndeavourOS | 2025.xx | x86_64 | KDE/XFCE (Rolling) | Friendly Arch installer with sane defaults | مثبّت سهل مبني على Arch | Great community — مجتمع ممتاز |
| Zorin OS | 17.x | x86_64 | GNOME (Desktop) | Windows-like UX on Ubuntu base | تجربة قريبة من ويندوز | Good for switchers — مناسب للمنتقلين |
| elementary OS | 8.x | x86_64 | Pantheon (Desktop) | Design-focused Ubuntu-based distro | توزيعة تركّز على التصميم | Sleek but opinionated — أنيق مع قيود |
| Pop!_OS | 22.04 LTS | x86_64 | COSMIC GNOME | Ubuntu-based with tiling, Nvidia ISOs | مبنية على أوبونتو مع ميزات للاعبين | Great on Nvidia laptops — ممتاز للمحمولة |
| AlmaLinux | 9.4 | x86_64, aarch64 | Server | RHEL-compatible downstream | متوافق مع RHEL | Good CentOS replacement — بديل سنت-أو إس |
| Rocky Linux | 9.4 | x86_64, aarch64 | Server | RHEL-compatible downstream by community | متوافق مع RHEL من المجتمع | Enterprise servers — خوادم مؤسسية |
| Proxmox VE | 8.3 | x86_64 | Hypervisor | Debian-based virtualization platform | منصة افتراضية مبنية على ديبيان | Great for homelab — ممتاز للمعمل المنزلي |
| Garuda Linux | 2025.xx | x86_64 | KDE Dr460nized (Desktop/Rolling) | Arch-based, performance-tuned, gaming-friendly | مبنية على Arch معدّلة للأداء والألعاب | Btrfs + Zen kernel; use snapshots — لقطات Btrfs هامة |
| Bodhi Linux | 7.0 | x86_64, i686 | Moksha (Light Desktop) | Ultra-light Ubuntu-based distro | توزيعة خفيفة جدًا مبنية على أوبونتو | Great for very old PCs — ممتاز للأجهزة القديمة جدًا |
| Mageia | 9 | x86_64 | KDE/GNOME/XFCE (Desktop) | Community fork of Mandriva | مشتقة مجتمع من ماندريفا | MCC tools are handy — أدوات Mageia مفيدة |
| MX Linux | 23.x (Libretto) | x86_64, i386 | XFCE/KDE (Desktop) | Debian-based, lightweight, tools-rich | مبنية على ديبيان وخفيفة | MX Tools are excellent — أدوات MX رائعة |
| SparkyLinux | 7.x (Nibiru) | x86_64, i386 | LXQt/XFCE (Light) | Lightweight Debian-based distro | توزيعة خفيفة مبنية على ديبيان | Good on low RAM — مناسب لذاكرة قليلة |
| Slackware | 15.0 | x86_64 | Minimal/KDE (Desktop) | Oldest actively maintained distro | أقدم توزيعة نشطة | Manual config; stable & classic — إعدادات يدوية |
| Clear Linux | 40000+ (rolling) | x86_64 | Minimal/Developer | Intel-optimized, performance-focused | محسّنة من إنتل للأداء | Best on Intel hardware — الأفضل على عتاد إنتل |
| TUXEDO OS | 24.x | x86_64 | KDE Plasma (Desktop) | Ubuntu-based by TUXEDO Computers | مبنية على أوبونتو من TUXEDO | Great on TUXEDO laptops — ممتاز لحواسيبهم |
| Nitrux | 3x.x | x86_64 | NX Desktop (KDE) | Debian-based with AppImages, NX tools | مبنية على ديبيان مع AppImage | Rolling; Calamares install — متجددة |
| Parrot Security | 6.x | x86_64, aarch64 | Security/Forensics | Security, privacy, and forensics suite | توزيعة أمن وخصوصية | Use VM; tools heavy — استخدام في VM أفضل |
| Windows 11 | 24H2 | x86_64, ARM64 | Desktop | Latest Windows with Copilot+ features | أحدث ويندوز بميزات جديدة | Use official tool; TPM 2.0 req — استخدم الأداة الرسمية |
| Windows 10 | 22H2 | x86_64 | Desktop | Mature Windows with broad app support | ويندوز ناضج بدعم واسع للتطبيقات | Extended support cycles — دورات دعم ممتدة |
| ChromeOS Flex | 2025.xx | x86_64 | Desktop/Cloud | ChromeOS for PCs (no Android apps) | ChromeOS للحواسيب (بدون تطبيقات أندرويد) | Great for old laptops — ممتاز للأجهزة القديمة |
| FydeOS | 17.x | x86_64 | Desktop | ChromiumOS variant with Android support | نسخة ChromiumOS بدعم أندرويد | Good for apps testing — مناسب للتجارب |
| Remix OS (legacy) | 3.x | x86_64 | Desktop | Android-x86 with desktop paradigm | أندرويد-إكس86 بواجهة مكتبية | Legacy, use for demos — قديم للتجارب فقط |
| Android-x86 | 9.0/8.1 | x86_64 | Desktop/Mobile | Android port for PCs | أندرويد للحواسيب | Hardware varies — التوافق يختلف |
| Hiren’s BootCD PE | 1.0.8 | x86_64 | Rescue | Windows PE-based rescue toolkit | أدوات إنقاذ مبنية على WinPE | Must-have USB — أداة أساسية |
| Ventoy | 1.0.xx | x86_64 | Tool | Multi-ISO boot tool | أداة إقلاع متعددة ISO | Simplifies ISO library — تسهل الإدارة |

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
- Garuda: https://garudalinux.org/downloads
- Bodhi: https://www.bodhilinux.com/download
- Mageia: https://www.mageia.org/en/downloads/
- MX Linux: https://mxlinux.org/download-links/
- SparkyLinux: https://sparkylinux.org/download/
- Slackware: https://www.slackware.com/getslack/
- Clear Linux: https://clearlinux.org/downloads
- TUXEDO OS: https://www.tuxedocomputers.com/en/TUXEDO-OS.tuxedo
- Nitrux: https://nxos.org/download/
- Parrot Security: https://parrotsec.org/download
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
