# 📋 UAT Report — bKash Mobile App

> A structured User Acceptance Testing report for **bKash** — Bangladesh's leading Mobile Financial Services app with 65+ million users.

---

## 🧭 Project Overview

This project demonstrates core QA competencies through a real-world UAT exercise conducted on a publicly available mobile application.

**Skills demonstrated in this project:**
- Manual exploratory testing & bug documentation
- UX evaluation using user personas
- Structured report writing (ISTQB-aligned severity classification)
- Stakeholder-ready documentation with actionable recommendations

---

## 📊 Test Summary

| Field | Details |
|---|---|
| **App Tested** | bKash (v6.3.1) |
| **Platform** | Android 14 — Samsung Galaxy A54 5G |
| **Testing Period** | April 21–23, 2026 (3 days, ~6 hours) |
| **Test Scenarios** | 28 scenarios across 8 feature areas |
| **Bugs Found** | 9 (2 Critical, 3 High, 3 Medium, 1 Low) |
| **UX Issues** | 7 major friction points |
| **Overall Rating** | **6.8 / 10 — Conditionally Accepted** |

---

## 📸 Report Screenshots

### Cover & Executive Summary
![Cover](screenshots/Screenshot%202026-04-24%20165047.png)

### Test Scope & Methodology
![Scope](screenshots/Screenshot%202026-04-24%20165100.png)

### Bugs Found
![Bugs](screenshots/Screenshot%202026-04-24%20165025.png)

### UX Issues Part 1
![UX1](screenshots/Screenshot%202026-04-24%20165012.png)

### UX Issues Part 2
![UX2](screenshots/Screenshot%202026-04-24%20164951.png)

### What Works Well
![Good](screenshots/Screenshot%202026-04-24%20164911.png)

### Recommendations
![Rec](screenshots/Screenshot%202026-04-24%20164843.png)

### UAT Verdict
![Verdict](screenshots/Screenshot%202026-04-24%20164828.png)

---

## 🐛 Key Bugs Found

| # | Bug | Severity |
|---|-----|----------|
| 1 | App crashes after 8-min background idle in Send Money flow | 🔴 Critical |
| 2 | OTP not delivered when phone number contains a space | 🔴 Critical |
| 3 | Wrong currency symbol ($ instead of ৳) after OS language switch | 🟠 High |
| 4 | QR scanner freezes under fluorescent lighting | 🟠 High |
| 5 | Biometric login fails on first try after app update | 🟠 High |
| 6 | Agent search returns empty results for 4-digit codes | 🟡 Medium |
| 7 | Bank list does not scroll on Samsung Galaxy A14/A15 | 🟡 Medium |
| 8 | Push notifications delayed 15–40s on Grameenphone network | 🟡 Medium |
| 9 | Back button doesn't dismiss post-transaction modal | 🔵 Low |

---

## 😤 UX Issues Identified

1. **Confusing Navigation Hierarchy** — 16 flat tiles with no grouping or search
2. **No PIN Attempt Feedback** — silent failure causes lockouts for low-literacy users
3. **No Network Degradation Mode** — infinite spinner on 2G with no timeout
4. **Inaccessible Bangla Font** — too small on lower-resolution screens
5. **Fee Hidden on Confirmation Screen** — users miss charges before confirming
6. **Promotional Banners Dominate Home Screen** — 35% of above-the-fold space
7. **No Deep Link from SMS Alerts** — tapping notification opens home screen, not transaction

---

## ✅ What Works Well

- ⚡ P2P transfers complete in under 4 seconds on LTE
- 🔐 Strong security notifications on every login/transaction
- 📱 Mobile recharge flow is clean and intuitive (3 taps)
- 📄 One-tap PDF statement export — great for freelancers
- 🧾 Transaction history is well-designed and color-coded
- 💡 Bill pay (DESCO, TITAS, WASA) works flawlessly

---

## 💡 Top Recommendations

**Critical / Must Fix:**
- Fix session timeout crash in active transaction flows
- Validate phone number input before OTP dispatch
- Fix QR scanner under indoor lighting

**Medium Priority:**
- Redesign home screen with grouped categories + search bar
- Add 15-second network timeout with retry option
- Increase minimum Bangla font size to 16px

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `bKash_UAT_Report.docx` | Full report in Word format |
| `bKash_UAT_Report.pdf` | Full report in PDF format |
| `screenshots/` | Report page s
