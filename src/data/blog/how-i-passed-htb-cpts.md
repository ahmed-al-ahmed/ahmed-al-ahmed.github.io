---
author: Ahmed Al Ahmed
pubDatetime: 2026-03-05T15:22:00Z
modDatetime: 2026-03-05T15:22:00Z
title: How I passed HTB Certified Penetration Testing Specilist
slug: how-i-passed-htb-cpts
featured: true
draft: false
tags:
  - htb
  - security
  - ctf
  - certificates
description:
  Theoritical and practical guides on the resources I have followed when I studied and prepared for CPTS.
---


## Complete Preparation Guide, Tips, and Real Experience
A year ago, I committed to earning the CPTS (Certified Penetration Testing Specialist). This is my complete experience: the preparation, the challenges, the exam process (without breaking NDA), and everything I learned along the way.
Check the post <a target="_blank" href="https://www.linkedin.com/posts/engahmedalahmed_penetrationtesting-security-cybersecurity-share-7410451463283396608-GCSr">here</a>
and the certificate on <a target="_blank" href="https://www.credly.com/badges/3ccac3ec-24f4-4d80-8920-f57fa9051ec1/public_url">credly</a>.

## 🧭 Why I Chose CPTS (And Why It’s Growing Fast)

Over the last year, CPTS has become more recognized across the cybersecurity industry. Many professionals even consider it a strong modern alternative to the OSCP, with better:

- Active Directory coverage.
- Realistic enterprise simulations.
- Red-team-style methodology.
- Hands-on labs and AEN training.

## 🛠️ My Preparation Strategy
My approach was simple but consistent:

Time Commitment: 2–3 hours per day after my full-time job.

Note-Taking: Revisiting every module and creating structured notes.

**Focus Areas:**

- Active Directory attacks.
- Password attacks.
- Windows & Linux privilege escalation.

Overcoming Lab Issues
To compensate for network instability or environment quirks, I had to:

- Repeat scans multiple times.
- Reset the environment frequently.
- Switch VPN servers when latency was high.
- Validate tool output manually to ensure accuracy.

## 🏁 The Exam Experience
The exam flow generally followed: **Enumeration → Foothold → PrivEsc → Flags**.

Step 1 — Enumeration
Enumerate everything. Then enumerate again. Finally, enumerate again! This is the foundation of CPTS success.

Step 2 — Finding the Foothold
Most students find the first flag the hardest. For me, it was manageable—even with network issues, I captured it in approximately 7 hours. After gathering enough indicators, the initial foothold path became clear.

Step 3 — Completing the Flags
By the end of Day 4, I had collected 12/14 flags. On Day 5, I finalized everything I needed for submission. I didn’t attempt the last two flags as they were not required for a pass, and I was ready to close this chapter.

## 📝 Reporting
I previously failed CWES on my first attempt due to a weak report, so this time I documented everything:

- Screenshots and terminal outputs.
- Step-by-step reproduction.
- Detailed enumeration results.
- Attack paths and justifications.

I submitted the report on Friday evening and received a "Pass" the next business day—much faster than the usual 2-week SLA.

## 🔥 My Proven Tips to Pass the CPTS Exam
These are the tips I wish someone had told me before starting:

Enumerate Thoroughly — Seriously. 80% of the exam depends on solid enumeration. Don’t rush this step.

Don’t Limit Your Thinking. Avoid assumptions. Just because something worked in Academy modules or labs does not mean it will work the same way here.

Remember: CPTS Is Not a CTF. It’s not a simple HTB box or a typical CTF environment; it simulates a real enterprise penetration test. Approach it with a professional mindset.

Document Everything During the Exam. Your report is your lifeline. Capture screenshots and command evidence as you go, not after you finish.

Use ligolo-ng for Pivoting. Among all pivoting tools, ligolo-ng is the most stable, flexible, and exam-friendly.

Keep It Simple + Stay Calm. Overthinking kills progress. Follow your methodology, breathe, and let the indicators guide your next step.