# Loupewire Support

Official bug tracker and feature request hub for **Loupewire** - a Chromium extension that captures
HTTP traffic from every tab in one window, masks secrets on screen and in the file, and exports a
HAR you can attach to a ticket.

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/dkoclbklglebhboiodckkicoajbcmbjd?label=Chrome&color=blue&style=for-the-badge)](https://chromewebstore.google.com/detail/dkoclbklglebhboiodckkicoajbcmbjd)
[![Chrome Web Store Users](https://img.shields.io/chrome-web-store/users/dkoclbklglebhboiodckkicoajbcmbjd?label=Chrome%20Users&color=brightgreen&style=for-the-badge)](https://chromewebstore.google.com/detail/dkoclbklglebhboiodckkicoajbcmbjd)
[![Chrome Web Store Rating](https://img.shields.io/chrome-web-store/rating/dkoclbklglebhboiodckkicoajbcmbjd?label=Chrome%20Rating&color=brightgreen&style=for-the-badge)](https://chromewebstore.google.com/detail/dkoclbklglebhboiodckkicoajbcmbjd)<br>
[![Microsoft Edge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fmicrosoftedge.microsoft.com%2Faddons%2Fgetproductdetailsbycrxid%2Ffobjeeglpkfdalljagicbgelbdmhlhgf&query=%24.version&prefix=v&label=Edge&color=blue&style=for-the-badge)](https://microsoftedge.microsoft.com/addons/detail/fobjeeglpkfdalljagicbgelbdmhlhgf)
[![Microsoft Edge Users](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fmicrosoftedge.microsoft.com%2Faddons%2Fgetproductdetailsbycrxid%2Ffobjeeglpkfdalljagicbgelbdmhlhgf&query=%24.activeInstallCount&label=Edge%20Users&color=brightgreen&style=for-the-badge)](https://microsoftedge.microsoft.com/addons/detail/fobjeeglpkfdalljagicbgelbdmhlhgf)
[![Microsoft Edge Rating](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fmicrosoftedge.microsoft.com%2Faddons%2Fgetproductdetailsbycrxid%2Ffobjeeglpkfdalljagicbgelbdmhlhgf&query=%24.averageRating&suffix=%2F5&label=Edge%20Rating&color=brightgreen&style=for-the-badge)](https://microsoftedge.microsoft.com/addons/detail/fobjeeglpkfdalljagicbgelbdmhlhgf)

---

## 🐛 Report a Bug

Found a bug? Let us know!

**[Report Bug →](https://github.com/loupewire/loupewire-support/issues/new?template=bug_report.yml)**

---

## ✨ Request a Feature

Have an idea to make Loupewire better?

**[Request Feature →](https://github.com/loupewire/loupewire-support/issues/new?template=feature_request.yml)**

---

## ❓ Get Help

**[Ask a Question →](https://github.com/loupewire/loupewire-support/issues/new?template=question.yml)** | **[Discussions →](https://github.com/loupewire/loupewire-support/discussions)**

---

## 📋 Guidelines

Before submitting an issue:

- **Search first** - check if your issue already exists
- **Be specific** - provide details, steps to reproduce, and screenshots
- **One issue per report** - don't combine multiple bugs or features
- **No sensitive data** - Loupewire exists to keep credentials out of what you share. Mask or remove
  tokens, cookies and personal data before pasting a screenshot, a HAR file or a log

_This is a support repository for bug reports and feature requests. The source code is private._

---

## ❗ Known limits

Worth reading before reporting these as bugs:

- **No response bodies.** `webRequest`, the API that makes all-tab capture possible, never exposes
  them - in Manifest V2 or V3. Tools that show bodies attach a debugger to each tab or inject
  scripts into pages; Loupewire does neither.
- **Chromium browsers only.** Chrome, Edge & Chromium Browsers. No Firefox, no Safari.

---

## 🌐 Links

- **Website:** [loupewire.com](https://loupewire.com/)
- **Guides:** [loupewire.com/guides](https://loupewire.com/guides/)
- **Privacy Policy:** [loupewire.com/privacy-policy](https://loupewire.com/privacy-policy/)
- **Terms:** [loupewire.com/terms](https://loupewire.com/terms/)

---

## 📧 Contact

- **Security issues:** email [support@loupewire.com](mailto:support@loupewire.com), so the details
  stay private until a fix ships. Please don't open a public issue for them
- **General inquiries:** open an issue or start a discussion

---

<div align="center">
  Made with ❤️ by the Loupewire Team<br>
  <a href="https://github.com/loupewire/loupewire-support/issues">Issues</a> •
  <a href="https://github.com/loupewire/loupewire-support/discussions">Discussions</a>
</div>
