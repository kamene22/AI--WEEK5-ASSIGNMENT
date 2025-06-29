# 📚 Team Collaboration Guide – Week of Theoretical Work

## Hey Team! 👋

Welcome back, everyone! This week our work is more **theoretical** – so instead of writing code, you'll be creating and uploading **PDF reports** to our GitHub repository. 📝

Please take a minute to read this short guide. It explains **how to prepare and push your PDF files**, and reminds you of the **essential GitHub collaboration rules** to avoid any problems with the repo. Let’s stay organized and efficient!

---

## ✅ What You Need to Do This Week

1. **Write your report** in Google Docs, Microsoft Word, or WPS Office.
2. **Export it as a PDF.** (Google Docs: `File → Download → PDF Document`)
3. **Push the PDF to the repository** following the steps below.

---

## 🚨 General GitHub Rules (Still Apply!)

Please follow these rules — they're more important than ever when we’re all pushing files to the repo.

### ❌ DO NOT:

* **❌ Push directly to the `main` branch** – always use your own branch.
* **❌ Push large files or videos without asking.**
* **❌ Use `git push --force` on shared branches.**

### ✅ DO:

* **✅ Create your own branch** for your PDF upload.
* **✅ Pull the latest changes** from `main` **before you start** or **before pushing**.
* **✅ Write clear commit messages** (e.g., `"Add project overview PDF"`).
* **✅ Push only your PDF** (not unnecessary files).

---

## 📦 Step-by-Step Workflow for This Week

### 1. Clone the Repository (Only First Time)

```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

### 2. Always Start By Pulling the Latest Changes

```bash
git checkout main
git pull origin main
```

### 3. Create Your Own Branch

```bash
git checkout -b docs/your-report-title
```

### 4. Add and Commit Your PDF

```bash
# Copy your exported PDF into the project folder
git add your-file.pdf
git commit -m "Add PDF for [your topic/title]"
```

### 5. Push to GitHub

```bash
git push origin docs/your-report-title
```

### 6. Create a Pull Request

* Go to GitHub → "Pull Requests" → "New Pull Request"
* Make sure it’s from your branch **into** `main`
* Add a short title + description of your report
* Submit it for review

---

## 📂 PDF Tips

* Name your file clearly, e.g., `AI-Project-Ethics-Kennedy.pdf`
* Double-check that it’s the final version before pushing
* One file = one pull request

---

## 💬 Need Help?

If you're stuck:

* Ping me on Slack/Discord/WhatsApp
* Or create an Issue in GitHub
* We're here to help each other!

---

## 🚀 Final Reminder

Let’s keep things smooth and clean this week by:

* **NOT pushing to `main`**
* **Creating branches for your work**
* **Pulling before pushing**
* **Writing clear commit messages**

Thanks for being awesome! Let’s finish this theoretical week strong and tidy. 💪📘

---


