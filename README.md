# 🧠 Phishing Email Analysis Report
**Cyber Security Internship — Task 2**  
**Objective:** Identify phishing characteristics in a suspicious email sample.

---

## 📨 Sample Phishing Email

**Subject:** ⚠️ Your Account Has Been Suspended – Verify Now!  
**From:** support@paypaI-security.com  
**To:** user@example.com  
**Date:** 22 Oct 2025  

**Body:**  
> Dear Customer,  
> We have detected unusual activity on your PayPal account. To secure your account, please verify your information immediately by clicking the link below:  
> [Verify Account](http://secure-paypal-login.com)  
> Failure to verify within 24 hours will result in account suspension.  
> Thank you,  
> PayPal Security Team  

---

## 🕵️‍♂️ Phishing Indicators Identified

| Indicator | Description |
|------------|-------------|
| **Spoofed Sender Address** | Domain `paypaI-security.com` mimics PayPal using 'I' instead of 'l'. |
| **Suspicious Link** | Link text says PayPal but points to another domain. |
| **Urgent Tone** | Threatens suspension within 24 hours. |
| **Grammar Issues** | Unprofessional language typical of phishing. |
| **Generic Greeting** | Uses 'Dear Customer' instead of a name. |
| **HTTP not HTTPS** | Unsecured login link. |
| **Header Mismatch** | SPF/DKIM failed authentication. |

---

## 🧩 Email Header Analysis

**Tool Used:** [MxToolbox Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

**Findings:**
- Return-Path: `mailer@randomdomain.info`
- Origin IP: Foreign, not related to PayPal servers.
- SPF/DKIM: Failed checks.
- Reply-To: `helpdesk@unknownsupport.net`

---

## ⚠️ Summary of Phishing Traits
✅ Urgent Language  
✅ Suspicious Links  
✅ Sender Spoofing  
✅ Header Mismatch  
✅ Generic Greeting  
✅ Failed SPF/DKIM  

---

## 🔍 Conclusion
The email is a phishing attempt aiming to steal login credentials through social engineering and spoofing tactics.

---

## 🧰 Tools Used
- MxToolbox Header Analyzer  
- Google Admin Toolbox  
- VirusTotal  
- Browser Hover Test  

---

## 📎 Repository Structure
```
📂 Task-2-Phishing-Email-Analysis
│
├── README.md
├── phishing_email_sample.txt
├── header_analysis.pdf
└── screenshots/
```

---

## 📤 Submission Link
[Submit Here → https://forms.gle/8Gm83s53KbyXs3Ne9](https://forms.gle/8Gm83s53KbyXs3Ne9)
