# 🛡️ LICENSR — Smart Software Rights & Licensing Engine

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Live%20Production-success.svg)
![Tech Stack](https://img.shields.io/badge/stack-Next.js%20%7C%20Node.js%20%7C%20Supabase-lightgrey)

---

## 💡 What is LICENSR? (Product Overview)
**LICENSR** the first 100% Algerian SaaS Software Licensing & Rights Managem 

I present to you **LICENSR** is a cloud-based B2B SaaS software licensing engine designed to protect software applications, digital products, scripts, and SaaS tools from unauthorized usage and code piracy. It provides software owners with a centralized dashboard to generate, bind, manage, and verify license keys tied to specific client domains, with real-time expiration, suspension, and auditing capabilities.
 

When you spend months building a custom web application, script, or digital product, unauthorized redistribution and code piracy become serious risks. **LICENSR** solves this by providing a centralized dashboard to generate, bind, and manage **cryptographic, domain-restricted license keys**. It allows you to lock your software remotely, verify user domains in real time, and cut off access immediately if a license expires or is suspended.

---

## ⚙️ How It Works (The System Workflow)

LICENSR bridges the gap between your licensing dashboard and your clients' deployed software in four simple steps:

[Your Dashboard] ──1. Generate Key──> [LICENSR Cloud Engine]
│
2. Real-time Check
▼
[Client Software] ──3. API Verify───> [Active / Expired / Blocked]


1. **Create a Project & Issue a Key:** Log into your LICENSR dashboard, create a project for your client, specify their allowed domain (e.g., `client-site.com`), and set an expiration date.
2. **Embed the Verification Snippet:** Add a single, lightweight verification request to your application's frontend or backend code.
3. **Real-Time Automated Validation:** Every time the client's app runs, it securely pings the LICENSR verification endpoint (`/api/license/verify`).
4. **Remote Access Control:** 
   * If the license is **Active** & domain matches ➔ *Software renders normally.*
   * If the license is **Expired, Suspended, or Stolen** ➔ *Software is blocked instantly.*

---

## 🚀 How to Subscribe & Use the Service

Getting started with LICENSR for your own software projects is straightforward:

1. **Sign Up for an Account:**
   * Visit our production portal at **[https://licensr.netlify.app](https://licensr.netlify.app)**.
   * Contact Developer (contact@wbnfy.site)** to create your Software Owner / Admin account.
2. **Create Your First Protected Project:**
   * In your dashboard, click **"New Project"**.
   * Enter your Client's Name, Project Name, Allowed Domain, and Expiration Date.
3. **Copy & Integrate:**
   * Copy the generated License Key.
   * Paste the verification API call into your target product (React, Next.js, WordPress, or Node.js).
4. **Enterprise & Custom Agencies (Subscription Plans):**
   * Need custom white-label licensing, dedicated server hosting, or advanced API limits? Reach out directly via email or LinkedIn for a tailored agency tier.

---

## 👨‍💻 Developer & Contact Information

This system was architected and developed as a complete full-stack SaaS solution. For freelance inquiries, technical consultations, or custom enterprise integrations, feel free to connect with me:

* **LinkedIn:** [ELAOUESSE MOAHMED CHAKIB](https://linkedin.com/in/elmedch)
* **Email:** [contact@wbnfy.site](mailto:contact@wbnfy.site)
* **Live Dashboard:** [licensr.netlify.app](https://licensr.netlify.app)

---

## 🛠️ Architecture & Tech Stack

| Layer | Technologies Used | Key Role |
| :--- | :--- | :--- |
| **Frontend Dashboard** | Next.js, React, Tailwind CSS | Management UI hosted on Netlify |
| **Backend Engine** | Node.js, Express (TypeScript) | Secure API endpoints hosted on Render |
| **Database & ORM** | PostgreSQL (Supabase), Prisma | Encrypted SHA-256 key storage & logs |
| **Security** | JWT, bcrypt, SHA-256 Hashing | Session protection & cryptographic verification |

---

## 📝 License
This project is licensed under the **MIT License**.
