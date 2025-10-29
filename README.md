# 
 📀 ISO Library Collection — مكتبة نسخ الآيزو
A curated, bilingual catalog of operating system ISO images with practical notes, checksums, and usage tips.
فهرس ثنائي اللغة لصور أنظمة التشغيل (ISO) مع ملاحظات عملية، وقيم تحقق، ونصائح استخدام.
---
## 
 🔰 About — حول المكتبة
- 
 Purpose: centralize ISO knowledge for installs, recovery, testing, and VMs.
- 
 الهدف: توحيد معلومات نسخ ISO للتثبيت والاستعادة والاختبار والأنظمة الوهمية.
- 
 Scope: popular Linux, Windows, Android-x86, hypervisor/rescue tools, and more.
- 
 النطاق: توزيعات لينكس وويندوز وAndroid-x86 وأدوات إنقاذ ومحاكاة وغيرها.
---
## 
 📚 How to Use — طريقة الاستخدام
1)
 Verify integrity (SHA256/GPG) before booting or deploying.
   
- 
 تحقق من سلامة الملف (SHA256/GPG) قبل الإقلاع أو التثبيت.
2)
 Prefer official mirrors/CDNs and avoid third-party repacks.
   
- 
 استخدم الروابط الرسمية وتجنب النسخ المعدّلة.
3)
 Keep a USB toolkit (Ventoy/Rufus/Etcher) and label versions clearly.
   
- 
 احتفظ بأداة USB مثل Ventoy/Rufus وسمّ النسخ بوضوح.
4)
 Test in a VM first when uncertain; snapshot often.
   
- 
 جرّب في آلة افتراضية عند الشك وخذ لقطات محفوظة.
5)
 Document changes; update this README when adding ISOs.
   
- 
 وثّق التغييرات وحدّث هذا الملف عند الإضافة.
---
## 
 🧭 Quick Search and Filters — البحث السريع والتصنيف
- 
 Search by: Name, Version, Kernel, Desktop, Arch (x86_64/ARM), Use-case.
- 
 ابحث بالاسم والإصدار والنواة وبيئة سطح المكتب والمعمارية والاستخدام.
- 
 Suggested tags: desktop, server, lightweight, gaming, security, edu, OEM, rolling.
- 
 وسوم مقترحة: سطح_مكتب، خادم، خفيف، ألعاب، أمن، تعليمي، مصنع، متجدد.
Tip: Use your editor’s table search (Ctrl/Cmd+F) to filter rows.
نصيحة: استخدم بحث المحرّر لتصفية الصفوف بسرعة.
---
## 
 🗂️ ISO Catalog — فهرس النسخ
Legend — الأسطورة:
- 
 Arch: x86_64, aarch64, armhf, i686
- 
 Desktop: GNOME, KDE, XFCE, Cinnamon, LXQt, etc.
- 
 Type: Desktop/Server/Minimal/Rescue/Hypervisor

### 🔥 Linux — لينكس
| Name | Version / Date | Architecture | Desktop / Type | Brief Description (EN) | الوصف المختصر (AR) | Personal Notes (EN/AR) | Download |
|---|---|---|---|---|---|---|---|
| 🐧 Ubuntu | 24.04.1 LTS (Noble) | x86_64, aarch64 | GNOME (Desktop/Server) | Long-term support Ubuntu with strong ecosystem and snaps | أوبونتو بدعم طويل ونظام بيئي قوي وحزم Snap | Great defaults; consider minimal install — يفضل التثبيت المصغّر | https://ubuntu.com/download |
| 🐧 Ubuntu | 22.04.5 LTS | x86_64, aarch64 | GNOME (Desktop/Server) | Stable LTS widely supported by vendors | إصدار LTS مستقر ومدعوم على نطاق واسع | Good for production servers — مناسب للخوادم | https://ubuntu.com/download |
| 🐧 Kubuntu | 24.04 | x86_64 | KDE Plasma (Desktop) | Ubuntu base with polished KDE experience | قاعدة أوبونتو مع تجربة KDE مصقولة | Smooth on mid/high-end — سلس على الأجهزة المتوسطة/العليا | https://ubuntu.com/download |
| 🐧 Xubuntu | 24.04 | x86_64 | XFCE (Light Desktop) | Lightweight Ubuntu flavor for older PCs | نكهة خفيفة لأجهزة قديمة | Fast on HDDs — سريع على الأقراص التقليدية | https://ubuntu.com/download |
| 🐧 Fedora Workstation | 41 | x86_64, aarch64 | GNOME (Desktop) | Cutting-edge Fedora with Wayland defaults | فيدورا حديثة مع Wayland افتراضيًا | Great for devs; toolbox/distrobox — ممتاز للمطورين | https://getfedora.org |
| 🐧 Fedora Server | 41 | x86_64, aarch64 | Server | Server edition with Cockpit and SELinux | نسخة خادم مع Cockpit وSELinux | Solid for lab/VMs — مناسب للمعامل | https://getfedora.org |
| 🐧 Arch Linux | 2025-10-01 | x86_64 | Minimal/Rolling | DIY rolling-release, pacman and AUR | نظام متجدد بتركيب يدوي وAUR | Use guided installer archinstall — استخدم archinstall | https://archlinux.org/download |
| 🐧 Manjaro | 24.x | x86_64 | KDE/GNOME/XFCE (Desktop) | User-friendly Arch-based distro | توزيعة سهلة مبنية على Arch | Delayed updates; stable branch — تحديثات مؤجلة | https://manjaro.org/downloads/ |
| 🐧 Linux Mint | 22 (Wilma) | x86_64 | Cinnamon/MATE/XFCE | Ubuntu-based, classic desktop UX | مبنية على أوبونتو بواجهة تقليدية | Great for newcomers — ممتاز للمبتدئين | https://linuxmint.com/download.php |
| 🐧 openSUSE Tumbleweed | Rolling (2025-10) | x86_64, aarch64 | KDE/GNOME | Rolling with snapshots via Btrfs + Snapper | متجدد مع لقطات Btrfs | YaST/rollback friendly — رجوع سريع | https://get.opensuse.org/tumbleweed/ |
| 🐧 openSUSE Leap | 15.6 | x86_64 | KDE/GNOME (Stable) | Enterprise-aligned openSUSE | أوبن سوزه مستقر ومتوافق مع المؤسسات | Predictable updates — تحديثات متوقعة | https://get.opensuse.org/leap/ |
| 🐧 Debian | 12.7 (Bookworm) | x86_64, aarch64, armhf, i386 | GNOME/XFCE/Cinnamon | Universal OS, stable base for many distros | نظام عالمي مستقر | Great server baseline — أساس خوادم قوي | https://www.debian.org/distrib |
| 🐧 EndeavourOS | 2025.xx | x86_64 | KDE/XFCE (Rolling) | Friendly Arch installer with sane defaults | مثبّت سهل مبني على Arch | Great community — مجتمع ممتاز | https://endeavouros.com/latest-release/ |
| 🐧 Zorin OS | 17.x | x86_64 | GNOME (Desktop) | Windows-like UX on Ubuntu base | تجربة قريبة من ويندوز | Good for switchers — مناسب للمنتقلين | https://zorin.com/os/download/ |
| 🐧 elementary OS | 8.x | x86_64 | Pantheon (Desktop) | Design-focused Ubuntu-based distro | توزيعة تركّز على التصميم | Sleek but opinionated — أنيق مع قيود | https://elementary.io |
| 🐧 Pop!_OS | 22.04 LTS | x86_64 | COSMIC GNOME | Ubuntu-based with tiling, Nvidia ISOs | مبنية على أوبونتو مع ميزات للاعبين | Great on Nvidia laptops — ممتاز للمحمولة | https://pop.system76.com/ |
| 🐧 AlmaLinux | 9.4 | x86_64, aarch64 | Server | RHEL-compatible downstream | متوافق مع RHEL | Good CentOS replacement — بديل سنت-أو إس | https://almalinux.org/get-almalinux/ |
| 🐧 Rocky Linux | 9.4 | x86_64, aarch64 | Server | RHEL-compatible downstream by community | متوافق مع RHEL من المجتمع | Enterprise servers — خوادم مؤسسية | https://rockylinux.org/download |
| 🐧 Garuda Linux | 2025.xx | x86_64 | KDE Dr460nized (Desktop/Rolling) | Arch-based, performance-tuned, gaming-friendly | مبنية على Arch معدّلة للأداء والألعاب | Btrfs + Zen kernel; use snapshots — لقطات Btrfs هامة | https://garudalinux.org/downloads.html |
| 🐧 Bodhi Linux | 7.0 | x86_64, i686 | Moksha (Light Desktop) | Ultra-light Ubuntu-based distro | توزيعة خفيفة جدًا مبنية على أوبونتو | Great for very old PCs — ممتاز للأجهزة القديمة جدًا | https://www.bodhilinux.com/download/ |
| 🐧 Mageia | 9 | x86_64 | KDE/GNOME/XFCE (Desktop) | Community fork of Mandriva | مشتقة مجتمع من ماندريفا | MCC tools are handy — أدوات Mageia مفيدة | https://www.mageia.org/en/downloads/ |
| 🐧 MX Linux | 23.x (Libretto) | x86_64, i386 | XFCE/KDE (Desktop) | Debian-based, lightweight, tools-rich | مبنية على ديبيان وخفيفة | MX Tools are excellent — أدوات MX رائعة | https://mxlinux.org/download-links/ |
| 🐧 SparkyLinux | 7.x (Nibiru) | x86_64, i386 | LXQt/XFCE (Light) | Lightweight Debian-based distro | توزيعة خفيفة مبنية على ديبيان | Good on low RAM — مناسب لذاكرة قليلة | https://sparkylinux.org/download/ |
| 🐧 Slackware | 15.0 | x86_64 | Minimal/KDE (Desktop) | Oldest actively maintained distro | أقدم توزيعة نشطة | Manual config; stable & classic — إعدادات يدوية | https://mirrors.slackware.com/slackware/slackware64-15.0-iso/ |
| 🐧 Clear Linux | 40000+ (rolling) | x86_64 | Minimal/Developer | Intel-optimized, performance-focused | محسّنة من إنتل للأداء | Best on Intel hardware — الأفضل على عتاد إنتل | https://clearlinux.org/downloads |
| 🐧 TUXEDO OS | 24.x | x86_64 | KDE Plasma (Desktop) | Ubuntu-based by TUXEDO Computers | مبنية على أوبونتو من TUXEDO | Great on TUXEDO laptops — ممتاز لحواسيبهم | https://www.tuxedocomputers.com/en/Downloads/TUXEDO-OS.tuxedo |
| 🐧 Nitrux | 3x.x | x86_64 | NX Desktop (KDE) | Debian-based with AppImages, NX tools | مبنية على ديبيان مع AppImage | Rolling; Calamares install — متجددة | https://nxos.org/download/ |

### 🛡️ Security — أمنية
| Name | Version / Date | Architecture | Desktop / Type | Brief Description (EN) | الوصف المختصر (AR) | Personal Notes (EN/AR) | Download |
|---|---|---|---|---|---|---|---|
| 🔒 Kali Linux | 2025.3 | x86_64, aarch64 | Security/Forensics | Pen-testing distribution by Offensive Security | توزيعة اختبار اختراق | Use in lab; legal/ethics first — للاستخدام القانوني فقط | https://www.kali.org/get-kali/ |
| 🔒 Parrot Security | 6.x | x86_64, aarch64 | Security/Forensics | Security, privacy, and forensics suite | توزيعة أمن وخصوصية | Use VM; tools heavy — استخدام في VM أفضل | https://parrotsec.org/download/ |

### 👨‍🔧 Rescue/Tools — استعادة/أدوات
| Name | Version / Date | Architecture | Desktop / Type | Brief Description (EN) | الوصف المختصر (AR) | Personal Notes (EN/AR) | Download |
|---|---|---|---|---|---|---|---|
| 👨‍🔧 Hiren’s BootCD PE | 1.0.8 | x86_64 | Rescue | Windows PE-based rescue toolkit | أدوات إنقاذ مبنية على WinPE | Must-have USB — أداة أساسية | https://www.hirensbootcd.org/download/ |
| 👨‍🔧 Ventoy | 1.0.xx | x86_64 | Tool | Multi-ISO boot tool | أداة إقلاع متعددة ISO | Simplifies ISO library — تسهل الإدارة | https://www.ventoy.net/en/download.html |
| 👨‍🔧 Proxmox VE | 8.3 | x86_64 | Hypervisor | Debian-based virtualization platform | منصة افتراضية مبنية على ديبيان | Great for homelab — ممتاز للمعمل المنزلي | https://www.proxmox.com/en/downloads |

### 🪟 Windows — ويندوز
| Name | Version / Date | Architecture | Desktop / Type | Brief Description (EN) | الوصف المختصر (AR) | Personal Notes (EN/AR) | Download |
|---|---|---|---|---|---|---|---|
| 🪟 Windows 11 | 24H2 | x86_64, ARM64 | Desktop | Latest Windows with Copilot+ features | أحدث ويندوز بميزات جديدة | Use official tool; TPM 2.0 req — استخدم الأداة الرسمية | https://www.microsoft.com/software-download/windows11 |
| 🪟 Windows 10 | 22H2 | x86_64 | Desktop | Mature Windows with broad app support | ويندوز ناضج بدعم واسع للتطبيقات | Extended support cycles — دورات دعم ممتدة | https://www.microsoft.com/software-download/windows10 |

### 💠 Hybrid/Android — هجينة
| Name | Version / Date | Architecture | Desktop / Type | Brief Description (EN) | الوصف المختصر (AR) | Personal Notes (EN/AR) | Download |
|---|---|---|---|---|---|---|---|
| 💠 ChromeOS Flex | 2025.xx | x86_64 | Desktop/Cloud | ChromeOS for PCs (no Android apps) | ChromeOS للحواسيب (بدون تطبيقات أندرويد) | Great for old laptops — ممتاز للأجهزة القديمة | https://chromeenterprise.google/os/chromeosflex/ |
| 💠 FydeOS | 17.x | x86_64 | Desktop | ChromiumOS variant with Android support | نسخة ChromiumOS بدعم أندرويد | Good for apps testing — مناسب للتجارب | https://fydeos.io/download |
| 💠 Remix OS (legacy) | 3.x | x86_64 | Desktop | Android-x86 with desktop paradigm | أندرويد-إكس86 بواجهة مكتبية | Legacy, use for demos — قديم للتجارب فقط | https://www.jide.com/remixos |
| 💠 Android-x86 | 9.0/8.1 | x86_64 | Desktop/Mobile | Android port for PCs | أندرويد للحواسيب | Hardware varies — التوافق يختلف | https://www.android-x86.org/download |

---
## 
 🔗 Official Download Links — روابط التحميل الرسمية
- 
 Ubuntu: https://ubuntu.com/download
- 
 Fedora: https://getfedora.org
- 
 Arch: https://archlinux.org/download
- 
 Debian: https://www.debian.org/distrib
- 
 openSUSE: https://get.opensuse.org
