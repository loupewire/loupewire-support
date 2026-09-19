# Loupewire Support

Official bug tracker and feature request hub for **Loupewire** — a browser extension that captures
HTTP traffic from every tab in one window, masks secrets on screen and in the file, and exports a
HAR you can attach to a ticket.

> **Not published yet.** Loupewire is awaiting review on the Chrome Web Store. Install links and
> the privacy policy will appear here once it is live.

---

## 🐛 Report a Bug

Found a bug? Let us know!

**[Report Bug →](https://github.com/niftybox/loupewire-support/issues/new?template=bug_report.yml)**

---

## ✨ Request a Feature

Have an idea to make Loupewire better?

**[Request Feature →](https://github.com/niftybox/loupewire-support/issues/new?template=feature_request.yml)**

---

## ❓ Get Help

**[Ask a Question →](https://github.com/niftybox/loupewire-support/issues/new?template=question.yml)** | **[Discussions →](https://github.com/niftybox/loupewire-support/discussions)**

---

## 📋 Guidelines

Before submitting an issue:

- **Search first** — Check if your issue already exists
- **Be specific** — Provide details, steps to reproduce, and screenshots
- **One issue per report** — Don't combine multiple bugs or features
- **No sensitive data** — Loupewire exists to keep credentials out of what you share. Mask or remove
  tokens, cookies and personal data before pasting a screenshot, a HAR file or a log

_This is a support repository for bug reports and feature requests. The source code is private._

---

## ❗ Known limits

Worth reading before reporting these as bugs:

- **No response bodies.** `webRequest`, the API that makes all-tab capture possible, never exposes
  them — in Manifest V2 or V3. Tools that show bodies attach a debugger to each tab or inject
  scripts into pages; Loupewire does neither.
- **Chromium browsers only.** Chrome, Edge, Brave, Opera, Arc. No Firefox, no Safari.

---

## 🌐 Links

- **Chrome Web Store:** _not published yet_
- **Microsoft Edge Add-ons:** _not published yet_
- **Privacy Policy:** _coming with the first release_
- **Terms:** _coming with the first release_

---

## 📧 Contact

- **Security issues:** open an issue titled "Security Vulnerability", or contact the maintainer
  privately if the details should not be public yet
- **General inquiries:** open an issue or start a discussion

---

## 🚧 TODO

- [ ] Add Chrome Web Store and Edge Add-ons links once the extension is published
- [ ] Publish the privacy policy and terms, then link them here
- [ ] Enable Discussions

---

<div align="center">
  Made with ❤️ by NiftyBox<br>
  <a href="https://github.com/niftybox/loupewire-support/issues">Issues</a> •
  <a href="https://github.com/niftybox/loupewire-support/discussions">Discussions</a>
</div>
