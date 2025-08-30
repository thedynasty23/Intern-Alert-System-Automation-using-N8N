# 🎯 Intern Alert System using N8N  

![n8n](https://img.shields.io/badge/Workflow-n8n-orange?logo=n8n)
![WebScraping](https://img.shields.io/badge/Web-Scraping-lightblue?logo=selenium)
![Automation](https://img.shields.io/badge/Automation-100%25-green)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

An **automated internship alert system** 🚀 built with **[n8n](https://n8n.io/)** to scrape internship opportunities from **Internshala** 🧑‍💻.  

It fetches internship details (title, company, location, stipend, etc.) and can be extended to **send alerts** via email, Telegram, Slack, or any other integration supported by n8n.  

---

## ✨ Features  
- 🌐 Scrapes internships from **Internshala**  
- 🏢 Extracts details:  
  - Title 📌  
  - Company 🏢  
  - Location 📍  
  - Duration ⏳  
  - Stipend 💰  
  - Apply By 🗓️  
  - Link 🔗  
- ⚡ Fully automated with n8n  
- 📩 Extendable to send notifications (Email, Telegram, Slack, etc.)  

---

## 🛠️ How it Works  
The workflow (`Intern Alert System using N8N.json`) includes:  
1. **Manual Trigger** → Start the workflow when executed  
2. **HTTP Request Node** → Fetches the internship listings page  
3. **HTML Extraction Node** → Extracts internship details using CSS selectors  
4. (Optional) Add nodes for **Email / Telegram alerts**  

---

## 🚀 Getting Started  

### 1️⃣ Requirements  
- [n8n](https://n8n.io/) installed (self-hosted or cloud)  
- Internet connection 🌍  
- (Optional) Credentials for email/Telegram integration  

### 2️⃣ Import Workflow  
1. Open n8n  
2. Import `Intern Alert System using N8N.json`  
3. (Optional) Add notification nodes to send alerts  

### 3️⃣ Run the Workflow  
- Execute workflow ▶️  
- Extracted internship details will be available in n8n  

---

## 📂 Repository Structure  

```
.
├── Images/                            # Demo screenshots 📸
├── Intern Alert System using N8N.json # Main workflow file ⚙️
└── README.md                          # Project documentation 📘
```

---

## 📸 Demo  
(See [`Images/`](./Images) folder for screenshots and workflow previews)  

---

## 🧩 Future Enhancements  
- 📩 Automated daily alerts via Email / Telegram  
- 🔎 Filters (e.g., location-based, stipend-based alerts)  
- 📊 Dashboard to track saved internships  

---

## 🤝 Contributing  
Feel free to fork this project and improve it 💡. Pull requests are welcome!  

---

## 📜 License  
This project is licensed under the MIT License.  

---

🚀 Built with ❤️ using **n8n** and **Internshala scraping**
