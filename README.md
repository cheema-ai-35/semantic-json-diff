# 🧩 JSON Diff Visualizer — Side-by-Side JSON Comparison

A **Next.js** web application that intelligently visualizes the differences between two JSON objects — side by side, beautifully and clearly.

This tool highlights exactly what changed, what was added, and what was removed between two JSON inputs.
It’s built for developers, analysts, and anyone who needs to quickly understand complex JSON differences at a glance.

---

## ✨ Features

* 🔍 **Smart JSON Diffing** — Detects nested changes, additions, and deletions.
* 🧠 **Intelligent Highlighting** — Color-coded visualization for added, removed, or modified keys/values.
* 🎨 **Clean UI/UX** — Minimalist design that focuses on readability and clarity.
* ⚡ **Fast & Interactive** — Built with [Next.js](https://nextjs.org/) and React for instant feedback.
* 🪶 **Lightweight** — No backend required; everything runs in the browser.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/AbdullahCheema35/semantic-json-diff.git
cd semantic-json-diff
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Run the development server

```bash
npm run dev
# or
yarn dev
```

Then open **[http://localhost:3000](http://localhost:3000)** in your browser.

---

## 🧠 How It Works

1. Paste or upload two JSON objects — **Left (Base)** and **Right (Changed)**.
2. The app parses both objects and recursively compares their structure and values.
3. It intelligently categorizes differences:

   * 🟩 **Added** — Exists in Right but not in Left
   * 🟥 **Removed** — Exists in Left but not in Right
   * 🟨 **Modified** — Key exists in both but value differs
4. Results are rendered side-by-side with syntax highlighting and smooth transitions.

---

## 🧩 Tech Stack

* **Framework:** [Next.js](https://nextjs.org/)
* **Language:** TypeScript / JavaScript (depending on your setup)
* **Styling:** Tailwind CSS / CSS Modules (optional — customize as needed)
* **Diff Engine:** Custom diff logic or library integration (e.g., `jsondiffpatch`, `deep-diff`)

---

## 🧰 Possible Enhancements

* 🗂️ Support for large JSON files with streaming diffs
* 🌙 Dark mode
* 📤 Export diffs as JSON or Markdown reports
* 🔗 Shareable diff URLs

---

## 📜 License

MIT © [Your Name]
Feel free to use, modify, and share.

---

## ❤️ Contributing

Contributions are welcome!
If you’d like to improve the diffing logic, UI, or add new features, please fork the repo and open a pull request.

---

Would you like me to **customize this README** (e.g., add badges, live demo link, screenshots, or instructions for deploying to Vercel)?
