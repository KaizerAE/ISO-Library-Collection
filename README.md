# 📀 مكتبة نسخ الآيزو - ISO Library Collection

## 🔸 مقدمة (باللغة العربية)

هذا المستودع مخصص لتنظيم وإدارة مجموعة نسخ الآيزو (ISO Files) الخاصة بي، والتي تشمل أنظمة التشغيل المختلفة، برامج الإنقاذ، وأدوات النظام. الهدف من هذا المستودع هو توفير فهرس منظم ومفصل لكل نسخة آيزو، مع معلومات مهمة حول كل ملف لتسهيل عملية البحث والاستخدام.

### 🎯 أهداف هذا المستودع:
- تنظيم مجموعة نسخ الآيزو بطريقة منهجية
- توثيق كل نسخة مع المعلومات الأساسية
- تسهيل عملية البحث والوصول للنسخ المطلوبة
- توفير مرجع شامل للأنظمة والأدوات المتاحة

---

## 📋 جدول نسخ الآيزو - ISO Files Table

| اسم الملف<br>File Name | النوع<br>Type | الحجم<br>Size | تاريخ الإضافة<br>Date Added | الإصدار/التوزيعة<br>Distribution/Version | ملاحظاتي<br>My Notes |
|------------------------|---------------|-------------|--------------------------|-----------------------------------|---------------------|
| ubuntu-22.04.3-desktop-amd64.iso | Linux OS | 4.6 GB | 2024-01-15 | Ubuntu 22.04.3 LTS (Jammy Jellyfish) | نسخة سطح المكتب - مستقرة وموصى بها |
| windows-10-pro-x64.iso | Windows OS | 5.1 GB | 2024-02-10 | Windows 10 Pro Build 19041 | نسخة أصلية من مايكروسوفت |
| kali-linux-2023.4-installer-amd64.iso | Security OS | 3.8 GB | 2024-03-05 | Kali Linux 2023.4 | للاختبارات الأمنية - آخر إصدار |
| memtest86-usb.iso | Diagnostic Tool | 15 MB | 2024-01-20 | MemTest86 v10.6 | لفحص ذاكرة النظام |
| acronis-rescue-media.iso | Backup Tool | 850 MB | 2024-02-25 | Acronis True Image 2024 | لاستعادة النظام والملفات |
| fedora-39-workstation-x86_64.iso | Linux OS | 2.1 GB | 2024-04-12 | Fedora 39 Workstation | للتطوير - يحتوي على أحدث التقنيات |
| clonezilla-live-3.1.0-22-amd64.iso | Cloning Tool | 420 MB | 2024-03-18 | Clonezilla Live 3.1.0-22 | لاستنساخ الأقراص الصلبة |
| hirens-bootcd-pe-x64.iso | System Rescue | 1.8 GB | 2024-01-30 | Hiren's BootCD PE | أدوات إنقاذ وإصلاح شاملة |
| proxmox-ve-8.1-2.iso | Virtualization | 1.2 GB | 2024-05-08 | Proxmox VE 8.1-2 | لإدارة الأجهزة الافتراضية |
| tails-5.22.iso | Privacy OS | 1.4 GB | 2024-04-30 | Tails 5.22 | لتصفح آمن ومجهول الهوية |

---

## 🗂️ تنظيم الملفات - File Organization

### 📁 هيكل المجلدات الموصى به:
```
ISO_Library/
├── 01_Operating_Systems/
│   ├── Windows/
│   │   ├── Windows_10/
│   │   ├── Windows_11/
│   │   └── Windows_Server/
│   ├── Linux/
│   │   ├── Ubuntu/
│   │   ├── Fedora/
│   │   ├── CentOS/
│   │   └── Others/
│   └── MacOS/
├── 02_Security_Tools/
│   ├── Kali_Linux/
│   ├── Parrot_Security/
│   └── BlackArch/
├── 03_System_Tools/
│   ├── Rescue_Disks/
│   ├── Diagnostic_Tools/
│   ├── Cloning_Tools/
│   └── Recovery_Tools/
├── 04_Virtualization/
│   ├── Proxmox/
│   ├── VMware/
│   └── VirtualBox/
└── 05_Specialty/
    ├── Gaming/
    ├── Education/
    └── Development/
```

### 🏷️ نظام التسمية الموصى به - Naming Convention:

**للأنظمة:**
- `[system-name]-[version]-[architecture]-[date].iso`
- مثال: `ubuntu-22.04.3-amd64-20240115.iso`

**لأدوات الإنقاذ:**
- `[tool-name]-[version]-[type].iso`
- مثال: `hirens-bootcd-pe-v2024.iso`

**للأدوات الأمنية:**
- `[distro-name]-[version]-[variant].iso`
- مثال: `kali-linux-2023.4-installer.iso`

---

## 🌍 English Section - Repository Information

### 📖 About This Repository

This repository serves as a comprehensive catalog and organizational system for my personal ISO file collection. It includes operating systems, rescue tools, security distributions, and various system utilities.

### 🎯 Repository Purpose:
- **Systematic Organization**: Maintain a well-structured inventory of ISO files
- **Documentation**: Detailed information about each ISO image
- **Easy Access**: Quick reference for finding specific tools and systems
- **Version Tracking**: Keep track of different versions and their purposes

### 📊 Collection Statistics:
- **Total ISOs**: 10+ files
- **Operating Systems**: 6 different distributions
- **System Tools**: 4 specialized utilities
- **Total Size**: ~20+ GB
- **Last Updated**: October 2024

### 🔧 Usage Guidelines:

1. **Before Downloading**: Always verify checksums and digital signatures
2. **Storage**: Keep ISOs on fast storage for quick access
3. **Backup**: Maintain copies of critical rescue tools
4. **Updates**: Regularly check for newer versions
5. **Documentation**: Update this README when adding new ISOs

### 🛡️ Security Notes:
- All Windows ISOs are official Microsoft releases
- Linux distributions downloaded from official sources
- Security tools verified with GPG signatures where available
- Regular virus scanning performed on all files

### 📚 Common Use Cases:

**System Administration:**
- Fresh OS installations
- System recovery and repair
- Hardware diagnostics
- Data backup and cloning

**Security Testing:**
- Penetration testing with Kali Linux
- System hardening validation
- Network security assessment

**Development & Testing:**
- Virtual machine deployments
- Cross-platform testing
- Container host systems

### 🔗 Useful Resources:

- [Ubuntu Official Downloads](https://ubuntu.com/download)
- [Microsoft Windows ISOs](https://www.microsoft.com/software-download/)
- [Kali Linux Downloads](https://www.kali.org/get-kali/)
- [Fedora Downloads](https://getfedora.org/)
- [Proxmox Downloads](https://www.proxmox.com/en/downloads)

### 📝 Contributing:

This is a personal collection, but suggestions for organization improvements are welcome through issues.

### ⚖️ Legal Notice:

All ISO images in this collection are used in accordance with their respective licenses. This repository contains only documentation - no actual ISO files are stored here.

---

## 📞 Contact & Support

- **Repository Owner**: KaizerAE
- **Last Updated**: October 2024
- **License**: Documentation only - refer to individual ISO licenses

---

*مكتبة نسخ الآيزو هذه مصممة لتسهيل إدارة وتنظيم مجموعة الأنظمة والأدوات المختلفة بطريقة احترافية ومنظمة.*
