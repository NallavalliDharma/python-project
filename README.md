
🚀 LinkedIn Internship Job Notifier
An automated Python project designed to help you stay updated on the latest internship job postings on LinkedIn. It uses Selenium to scrape job data, Pandas to process and filter listings by relevance, and an SMTP server to send the curated list directly to your email inbox as a CSV attachment.

✨ Features
Targeted Scraping: Automatically scrapes job postings (initially configured for "Software Developer" internships in "Bengaluru") from LinkedIn.

Dynamic Loading: Includes logic to scroll and click the "See more jobs" button multiple times to load a large number of listings.

Keyword Filtering: Filters scraped job titles based on a defined list of keywords (e.g., Software Engineer, Full stack Developer, python) for personalized job recommendations.

Automated Email Notification: Sends the filtered job listings (filtered1_internships.csv) to a specified email address using Gmail's SMTP server.

Zero-Touch Deployment: The included shell script (notifer.sh) automates environment setup (dependencies, cloning, execution) for deployment on a server or CI/CD pipeline.

🛠️ Tech Stack
Python: The core logic for scraping, filtering, and emailing.

Selenium: Used for web scraping (browser automation).

Pandas: Used for data handling, filtering, and saving data to CSV files.

SMTP/MIME: Used for constructing and sending the email notification with the CSV attachment.

Bash/Shell Scripting: Used for automated setup and sequential execution (notifer.sh).

xvfb: Virtual framebuffer used to run the headless Chrome browser in server environments (like GitHub Actions or a VPS).

