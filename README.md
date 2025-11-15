# Macedonian Translations for Odoo 18 Project Module
# Македонски преводи за Odoo 18 Project модул

[![License: LGPL-3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Odoo Version](https://img.shields.io/badge/Odoo-18.0-875A7B.svg)](https://www.odoo.com/)
[![Language](https://img.shields.io/badge/Language-Macedonian-red.svg)](https://en.wikipedia.org/wiki/Macedonian_language)

## 📋 Overview / Преглед

This module provides **Macedonian (mk_MK)** translations for the Odoo 18 Project Management module.

Овој модул обезбедува **македонски (mk_MK)** преводи за Odoo 18 Project Management модулот.

## 📊 Translation Statistics / Статистика на преводот

- **Total entries:** 833
- **Translated:** 827 (99.3%)
- **Quality:** 100% (all placeholders and HTML preserved)
- **Characters:** 36,000+

### Coverage / Покриеност

- ✅ Project / Проект
- ✅ Task / Задача
- ✅ Milestone / Прекретница
- ✅ Update / Ажурирање
- ✅ Timesheet / Работен распоред
- ✅ Stage / Фаза
- ✅ Tag / Ознака
- ✅ Collaboration / Соработка
- ✅ Activity / Активност
- ✅ Portal / Портал

## 🚀 Installation / Инсталација

### Method 1: Manual Installation

1. Download this module:
```bash
cd /path/to/odoo/addons
git clone https://github.com/Palifra/l10n_mk_project.git
```

2. Restart Odoo:
```bash
sudo systemctl restart odoo
# or
docker-compose restart odoo
```

3. Install the module:
   - Go to **Apps**
   - Remove the **Apps** filter
   - Search for **"North Macedonia - Project"**
   - Click **Install**

4. Activate Macedonian language:
   - Go to **Settings → Users → Preferences**
   - Select **Language → Macedonian / македонски јазик**
   - Click **Save**
   - Refresh the page (F5)

### Method 2: Docker

Add to your `docker-compose.yml`:
```yaml
volumes:
  - ./l10n_mk_project:/mnt/extra-addons/l10n_mk_project
```

## 📦 Dependencies / Зависности

- `project` (Odoo Project Management module)

## 🔧 Technical Details / Технички детали

### Module Structure / Структура на модулот

```
l10n_mk_project/
├── __init__.py
├── __manifest__.py
├── i18n/
│   └── mk_MK.po          # 827 translated terms
└── README.md
```

### Translation Quality / Квалитет на преводот

- ✅ **0 placeholder errors** - All `%(variable)s` placeholders preserved
- ✅ **0 HTML errors** - All HTML tags and attributes preserved
- ✅ **99.3% coverage** - Only 6 technical/code terms untranslated
- ✅ **100% accuracy** - Verified with automated quality scanner

### Key Terminology / Клучна терминологија

| English | Македонски |
|---------|-----------|
| Project | Проект |
| Task | Задача |
| Milestone | Прекретница |
| Update | Ажурирање |
| Stage | Фаза |
| Timesheet | Работен распоред |
| Activity | Активност |
| Deadline | Краен рок |
| Progress | Напредок |
| Collaboration | Соработка |

## 🌍 About Macedonian Language / За македонскиот јазик

Macedonian (македонски јазик) is a South Slavic language spoken primarily in North Macedonia. This translation follows official terminology used in project management contexts.

Македонскиот јазик е јужнословенски јазик што се зборува главно во Северна Македонија. Овој превод ја следи официјалната терминологија што се користи во контекст на управување со проекти.

## 🤝 Contributing / Придонес

Contributions are welcome! If you find translation errors or have suggestions:

1. Open an issue on GitHub
2. Submit a pull request
3. Contact: info@eskon.mk

## 📄 License / Лиценца

This module is licensed under **LGPL-3.0** - same as Odoo.

## 👥 Credits / Заслуги

**Author / Автор:** ЕСКОН-ИНЖЕНЕРИНГ ДООЕЛ Струмица

**Translation Method / Метод на превод:**
- DeepL API (Beta Macedonian language)
- Automated masking technique for placeholder/HTML preservation
- Glossary-based consistency (3,681 terms)
- Manual quality control and corrections

**Tools Used / Користени алатки:**
- DeepL API for translation
- polib for PO file manipulation
- Custom masking algorithm for quality assurance
- Automated quality scanner for validation

## 📧 Contact / Контакт

- **Organization:** ЕСКОН-ИНЖЕНЕРИНГ ДООЕЛ Струмица
- **Email:** info@eskon.mk
- **Website:** https://eskon.mk
- **GitHub:** https://github.com/Palifra

## 🔗 Related Modules / Поврзани модули

- [l10n_mk_inventory](https://github.com/Palifra/l10n_mk_inventory) - Inventory/Stock translations
- [l10n_mk_invoicing](https://github.com/Palifra/l10n_mk_invoicing) - Invoicing/Accounting translations
- [l10n_mk_fleet](https://github.com/Palifra/l10n_mk_fleet) - Fleet/Vehicle Management translations
- [l10n_mk_base](https://github.com/Palifra/l10n_mk_base) - Base module translations
- [l10n_mk](https://github.com/OCA/l10n-macedonia) - Chart of Accounts for North Macedonia

---

**Supported Odoo Version:** 18.0
**Language:** Macedonian (mk_MK)
**Last Updated:** 2025-11-15

**Среќно со македонскиот Odoo! 🇲🇰**
