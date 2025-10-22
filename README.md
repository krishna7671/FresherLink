# 🌐 FresherLink – AI Freelancing Platform for Freshers

> Helping students and freshers get real freelance clients using AI skill-matching.  
> 100% built with **no-code tools + AI automation**, free for anyone to clone, remix, or deploy.

---

## 🚀 Features

- 👩‍🎓 Create fresher profiles with skills, college, and sample work  
- 💼 Clients post short-term gigs or internship-style projects  
- 🤖 AI matches freelancers to clients based on skill similarity  
- 💬 Instant contact via WhatsApp or email  
- 🌈 Built with free **no-code tools** and **AI prompts**

---

## 🧩 Tech Stack

| Function | Tool Used |
|-----------|------------|
| App / Frontend | **Glide** |
| Database | **Google Sheets** |
| AI Matching | **ChatGPT (OpenAI API)** via **Make.com** |
| Automation | **Make.com** or **Zapier** |
| Design | **Canva / Figma** |
| Documentation | **Markdown + GitHub Pages** |

---

## 🛠️ Setup Guide

1. **Duplicate the Google Sheet**
   - Open `/data/freelancers_sample.csv` and `/data/gigs_sample.csv`
   - Upload to your Google Drive and convert to Google Sheets

2. **Open the Glide Template**
   - Import the Google Sheet into [https://glideapps.com](https://glideapps.com)
   - Customize branding (logo, colors, etc.)

3. **Add AI Matching Automation**
   - Sign up on [https://www.make.com](https://www.make.com)
   - Import `/automation/make_scenario.json`
   - Add your **OpenAI API Key**  
     *(Create one from https://platform.openai.com/account/api-keys)*

4. **Connect Matching Logic**
   - Make reads new client gigs + freelancer data
   - Runs AI prompt (see below)
   - Writes best match in your Sheet automatically

5. **Publish Your App**
   - Glide → “Publish” → copy your public link  
   - Example: `https://fresherlink.glideapp.io`

6. **Upload to GitHub**
   - Push this entire folder to your GitHub  
   - Add your live link under “Live Demo” below

---

## 🧠 AI Matching Prompt Example


