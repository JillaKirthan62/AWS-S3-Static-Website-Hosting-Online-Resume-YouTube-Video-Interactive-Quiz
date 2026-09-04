# ☁️ AWS S3 Static Website Hosting
### 🎓 Online Resume • 🎬 YouTube Video • 🧠 Interactive Quiz

> **A hands-on cloud deployment project built with AWS + frontend technologies.**

---

## 🌟 What is this project?

This project turns a collection of HTML, CSS, JavaScript, images, and interactive content into a **publicly accessible static website hosted on Amazon S3**.

It combines three practical web components:

```text
🗂️ Static Website
       │
       ├── 👨‍💻 Online Resume
       │
       ├── 🎬 YouTube Video
       │
       └── 🧠 JavaScript Quiz
```

The deployment is extended with **Amazon CloudFront** and **Amazon Route 53** to demonstrate a scalable AWS website architecture.

---

## ✨ Highlights

| ☁️ Cloud | 🌐 Web | ⚡ Interactive |
|---|---|---|
| Amazon S3 | HTML | JavaScript Quiz |
| CloudFront | CSS | Score Calculation |
| Route 53 | Website Pages | Result Display |
| Bucket Policy | Resume | MCQ Questions |

---

## 🏗️ Architecture

```text
                         👤 USER
                            │
                            ▼
                    🌍 Amazon Route 53
                       DNS Routing
                            │
                            ▼
                   ⚡ Amazon CloudFront
                    Content Delivery
                            │
                            ▼
                     🪣 Amazon S3
                  Static Website Hosting
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
         📄 HTML/CSS    ⚙️ JavaScript    🖼️ Assets
             │              │
             ▼              ▼
       👨‍💻 Online Resume   🧠 Interactive Quiz
                            │
                            ▼
                      🎬 YouTube
                     Embedded Video
```

---

## ☁️ AWS Setup

### 🪣 01 — Create the S3 Bucket

A unique Amazon S3 bucket was created to store the static website files.

The bucket was configured for:

- 📄 `index.html` as the main website document
- 🚫 `404.html` as the custom error document
- 📦 HTML, CSS, JavaScript, images, and other assets
- 🌐 Static website hosting

---

### 🔓 02 — Make the Website Public

The S3 permissions were configured so that the website could be accessed publicly.

```text
S3 Bucket
   │
   ├── 🔐 Block Public Access → Configured
   │
   └── 📜 Bucket Policy → Public Read Access
                              │
                              ▼
                       🌍 Public Website
```

The deployed website was tested through the S3 website endpoint, including testing the custom error page with an unavailable URL.

---

## 👨‍💻 Online Resume

The website also contains a dedicated **HTML/CSS online resume**.

### 📌 Resume includes

- 📸 Passport-sized photograph
- 🎓 Education
- 🛠️ Technical skills
- 🚀 Projects
- 💼 Experience
- 🔗 GitHub hyperlink
- 🔗 LinkedIn hyperlink

Instead of keeping the resume only as a document, it was converted into a **web-based resume and hosted online through S3**.

---

## 🎬 YouTube Integration

A separate static webpage was created to display an **embedded YouTube video**.

```text
YouTube Video
      │
      ▼
🎬 Embedded in HTML Page
      │
      ▼
☁️ Hosted through Amazon S3
```

This demonstrates how external media can be integrated into a static website without requiring a backend server.

---

## 🧠 Interactive JavaScript Quiz

The project also includes a client-side quiz built with **JavaScript**.

### 🎯 Quiz flow

```text
❓ Question
     ↓
🔘 Select Answer
     ↓
➡️ Continue
     ↓
🧮 Calculate Score
     ↓
🏆 Display Result
```

The quiz supports:

- ❓ Multiple-choice questions
- 🔘 Answer selection
- 🧮 Score calculation
- 📊 Result handling
- 🏆 Final result display

All quiz interaction is handled on the client side using JavaScript.

---

## ⚡ CloudFront + Route 53

The architecture incorporates:

### ⚡ Amazon CloudFront
Used as the content delivery layer to provide **low-latency access** to the website.

### 🌍 Amazon Route 53
Used for **DNS routing** within the website architecture.

### 🪣 Amazon S3
Acts as the **static website hosting and storage layer**.

Together:

```text
🌍 Route 53
     ↓
⚡ CloudFront
     ↓
🪣 S3
     ↓
🌐 Static Website
```

---

## 🧰 Tech Stack

```text
☁️ AWS
├── 🪣 Amazon S3
├── ⚡ Amazon CloudFront
└── 🌍 Amazon Route 53

💻 Frontend
├── HTML
├── CSS
└── JavaScript

🔧 Tools
└── GitHub
```

---

## 📁 Suggested Project Structure

```text
📦 AWS-S3-Static-Website
│
├── 📄 index.html
├── 📄 404.html
├── 📄 resume.html
├── 📄 youtube.html
├── 📄 quiz.html
├── 🎨 style.css
├── ⚙️ script.js
│
├── 🖼️ images/
│   └── profile-photo.jpg
│
└── 📘 README.md
```

---

## 🎯 What I Practiced

Through this project, I gained practical experience with:

- ☁️ Amazon S3 static website hosting
- 🔐 S3 public-access configuration
- 📜 Bucket policies
- 🚫 Block Public Access settings
- 📄 Custom error-page configuration
- 🌐 Website deployment and testing
- 👨‍💻 HTML/CSS resume development
- 🎬 YouTube embedding
- 🧠 JavaScript-based interactivity
- ⚡ CloudFront content delivery
- 🌍 Route 53 DNS architecture
- 🔧 GitHub-based project management

---

## 📸 Project Evidence

The project was completed as part of the **Introduction to Cloud Computing** lab assignment and covers the required activities for:

**1️⃣ S3 Static Website → 2️⃣ Online Resume → 3️⃣ YouTube Video + Quiz**

The submitted assignment includes screenshots and implementation evidence for these activities.

---

## 👨‍💻 Author

### **Jilla Kirthan**

🎓 B.Tech — Computer Science & Engineering  
🤖 Specialization — Artificial Intelligence & Machine Learning

🔗 **GitHub:**  
https://github.com/JillaKirthan62

🔗 **LinkedIn:**  
_Add your LinkedIn profile URL here_

---

## ⭐ Project Snapshot

```text
        ☁️ AWS
         │
    ┌────┴────┐
    │         │
   🪣 S3    ⚡ CloudFront
    │         │
    └────┬────┘
         │
    🌍 Route 53
         │
         ▼
   🚀 LIVE WEBSITE
         │
   ┌─────┼─────┐
   ▼     ▼     ▼
  👨‍💻    🎬    🧠
Resume  Video  Quiz
```

> 💡 **A practical demonstration of hosting, configuring, and delivering a frontend website using AWS cloud services.**

---

## 📄 License

This project is created for **Personal project MIT license**.
