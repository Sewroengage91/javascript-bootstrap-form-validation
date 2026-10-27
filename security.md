# 📝 JavaScript Bootstrap Form Validation

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=9,22,29&height=210&section=header&text=JS%20Bootstrap%20Form%20Validation&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Clean.%20Fast.%20Accessible.%20Bulletproof.&descAlignY=56&descSize=19" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.0.1-06D6A0?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![License](https://img.shields.io/badge/license-MIT-118AB2?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Size](https://img.shields.io/badge/size-%3C%205kb-EF476F?style=for-the-badge&logo=javascript&logoColor=white)](https://github.com)

<br/>

### ⚡ A lightweight, dependency-free form validation library for Bootstrap 5

*🎯 Real-Time Feedback • ♿ Fully Accessible • 🎨 Zero-Styling Conflicts • 🌐 i18n Ready*

<br/>

<a href="https://share.google/k4Dtj67ef4SsG3ZXX">
  <img src="https://img.shields.io/badge/🚀_TRY_IT_LIVE-06D6A0?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=049C76" alt="Try It Live" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/k4Dtj67ef4SsG3ZXX">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_LIB-118AB2?style=for-the-badge&logo=javascript&logoColor=white&labelColor=0A5A73" alt="Download" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/k4Dtj67ef4SsG3ZXX">
  <img src="https://img.shields.io/badge/📚_DOCS-7952B3?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=4F3572" alt="Docs" height="45"/>
</a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**JavaScript Bootstrap Form Validation** is a modern, dependency-free validation library that seamlessly integrates with **Bootstrap 5**. It brings beautiful, accessible, and instant form feedback to any web project — without the bloat of heavy frameworks or messy configuration.

Just add `data-validate` to your form, and you're done. It's that simple.

> 💡 **Perfect for:** SaaS signups, contact forms, checkout flows, admin panels — any form where **user experience matters**.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Validation Features

<div align="center">

| ✅ **40+ Rules** | 🎨 **Bootstrap Native** | ♿ **Accessible** |
|:---:|:---:|:---:|
| Email, phone, URL,<br/>password strength & more | Inherits Bootstrap<br/>styles perfectly | ARIA-compliant<br/>error messages |

| 🌐 **i18n Support** | 🔌 **Custom Rules** | 📦 **Tiny Footprint** |
|:---:|:---:|:---:|
| 15+ built-in<br/>languages | Register your own<br/>validators easily | Under 5kb<br/>minified + gzip |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Library

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⚡ **Zero Dependencies** | Pure vanilla JS — no jQuery, no framework, no bloat |
| 🎨 **Bootstrap-Native** | Works *with* Bootstrap, not against it — no CSS conflicts ever |
| ♿ **WCAG 2.1 AA** | Screen-reader tested, keyboard navigation, focus management built-in |
| 🚀 **Instant Feedback** | Validates on blur, keystroke & submit — no waiting for page reloads |
| 🧩 **Extensible** | Register custom rules in 3 lines of code |
| 🌍 **Global-Ready** | Ready for international forms with automatic RTL support |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Live Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  📝  Sign Up Form                                ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  Email                                           ║
║  ┌────────────────────────────────────────────┐  ║
║  │ john@example.com                       ✅  │  ║
║  └────────────────────────────────────────────┘  ║
║                                                  ║
║  Password                                        ║
║  ┌────────────────────────────────────────────┐  ║
║  │ ••••••••••••                           ✅  │  ║
║  └────────────────────────────────────────────┘  ║
║  ✓ 12+ characters  ✓ Uppercase  ✓ Symbol        ║
║                                                  ║
║  Confirm Password                                ║
║  ┌────────────────────────────────────────────┐  ║
║  │ •••••••                                 ❌  │  ║
║  └────────────────────────────────────────────┘  ║
║  ⚠️ Passwords do not match                       ║
║                                                  ║
║           [ Create Account ]                     ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📝 js-bootstrap-form-validation/
├── 🎯 src/
│   ├── validator.js           # Core validation engine
│   ├── rules/                 # Built-in rules
│   │   ├── email.js
│   │   ├── password.js
│   │   └── phone.js
│   └── ui/                    # Bootstrap feedback binding
├── 🌐 i18n/                   # 15+ language packs
├── 🎨 themes/                 # Optional visual presets
├── 🧪 tests/                  # Vitest unit + Playwright e2e
└── 📖 docs/                   # Live playground & guides
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want a new rule? Have a translation to share?

<div align="center">

<a href="https://share.google/k4Dtj67ef4SsG3ZXX">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/k4Dtj67ef4SsG3ZXX">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-EF476F?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/k4Dtj67ef4SsG3ZXX">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-06D6A0?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### ⚡ Made with 📝 by the Form Validation Team

*If this library saves you time — drop a star!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=9,22,29&height=120&section=footer" width="100%"/>

</div>

---
