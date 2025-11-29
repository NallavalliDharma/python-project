# 🚀Job Notifier

An automated Python project designed to help you stay updated on the latest internship job postings on LinkedIn. It uses **Selenium** to scrape job data, **Pandas** to process and filter listings, and an **SMTP server** to send the curated list directly to your email inbox as a CSV attachment.

---

## ✨ Features

### 🔍 Targeted Scraping  
Automatically scrapes job postings (initially configured for **"Software Developer" internships in "Bengaluru"**) from LinkedIn.

### 📜 Dynamic Loading  
Includes logic to scroll and click the **"See more jobs"** button multiple times to load a large number of listings.

### 🧠 Keyword Filtering  
Filters scraped job titles based on a defined list of keywords (e.g., *Software Engineer*, *Full Stack Developer*, *Python*) for personalized job recommendations.

### 📧 Automated Email Notification  
Sends the filtered job listings (`filtered1_internships.csv`) to a specified email address using **Gmail's SMTP server**.

### ⚙️ Zero-Touch Deployment  
The included shell script `notifer.sh` automates environment setup (dependencies, cloning, execution) for deployment on a **server** or **CI/CD pipeline**.

---

## 🛠️ Tech Stack

- **Python** – Core logic for scraping, filtering, emailing  
- **Selenium** – Browser automation  
- **Pandas** – Data processing and CSV handling  
- **SMTP/MIME** – Email sending with attachments  
- **Bash / Shell Scripting** – Automation via `notifer.sh`  

---
