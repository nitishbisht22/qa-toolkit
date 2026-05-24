# QA Toolkit

A modern browser-based credential launcher built for QA and testing workflows.

This toolkit allows teams to quickly load credential workbooks, launch environments, and copy usernames/passwords instantly — all from a clean UI running completely in the browser.

---

## ✨ Features

- 📂 Load Excel workbooks (`.xlsx`, `.xls`)
- 🚀 Launch environment URLs instantly
- 📋 Auto-copy usernames to clipboard
- 🔐 Copy passwords securely
- 💾 Personal credentials stored locally in browser
- ⚡ Fast, lightweight, no backend required
- 🌙 Modern responsive dark UI

---

## 📁 Workbook Structure

The shared workbook must contain these sheets:

- `Core`
- `Ops`
- `Flow`

The personal workbook must contain:

- `Personal`

Each sheet should include these columns:

| Profile Name | Username | Password | URL |
| ------------ | -------- | -------- | --- |

---

## 🛠️ Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- SheetJS (XLSX Parser)

---

## 🚀 Run Locally

Simply open the HTML file in your browser:

```bash
open QA_Toolkit_Generic_Version.html
```
