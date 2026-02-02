# AWS Account Setup Lab - Solution

**Student Name:** [Ahmet Erdogan]  
**Date Completed:** [02.02.2026]

---

## Exercise 1: MFA Configuration

### Screenshot:
![MFA Enabled](<img width="951" height="294" alt="image" src="https://github.com/user-attachments/assets/bf5905ca-1517-4430-bc31-3e6d50bd78ce" />
)

### Notes:
- Authenticator app used: [2FAS]
- MFA setup completed successfully: [Yes]
- Backup codes saved: [No]

---

## Exercise 2: Billing Alerts

### Screenshots:

**Billing Preferences:**
![Billing Preferences](<img width="1440" height="389" alt="image" src="https://github.com/user-attachments/assets/805dc64b-f9a5-41a7-9043-0c2d5ac32652" />
)

**Billing Alarm:**
![Billing Alarm](<img width="1484" height="419" alt="image" src="https://github.com/user-attachments/assets/6225844a-12d1-4897-b74f-e6d816b2060d" />
)

**SNS Confirmation:**
![SNS Confirmed](<img width="902" height="233" alt="image" src="https://github.com/user-attachments/assets/58c81030-3a72-47f3-9276-30c9bfcdc805" />
)

### Configuration Details:
- Alert threshold: $[1]
- Email confirmed: [Yes]
- Additional thresholds created (bonus): [Yes]

---

## Exercise 3: Account Alias

### Screenshot:
![Account Alias](screenshots/account-alias.png)

### Account Details:
- **Account Alias:** [Ahmet-Erdogan-Ironhack]
- **Sign-In URL:** `ahmet-erdogan-ironhack.signin.aws.amazon.com/console`
- **Tested successfully:** [No]

---

## Exercise 4: Free Tier Dashboard

### Screenshot:
![Free Tier Dashboard](<img width="1418" height="540" alt="image" src="https://github.com/user-attachments/assets/1265a6ca-4969-4cf0-b226-05aad3bf3e9a" />
)

### Current Free Tier Usage Summary:

| Service | Current Usage | Free Tier Limit | Status |
|---------|--------------|-----------------|--------|
| EC2 | [X hours / 750 hours] | 750 hours/month | [Green/Yellow/Red] |
| S3 | [X GB / 5 GB] | 5 GB | [Green/Yellow/Red] |
| [Other services...] | | | |

### Notes:
- Any services approaching limits? [No]
- Any unexpected usage? [Yes, it seems like some of the balance has been used, but it doesn't specify what]]

---

## Exercise 5: Reflection Questions

### 1. Why is MFA important even for a personal learning account?

**Your Answer:**
[Because it is connected to a payment method and if someone with bad intentions gets acess to your account you might end up with a huge bill at the end of the month.]

---

### 2. What would happen if you left your root user unprotected?

**Your Answer:**
[Someone could easily get acess to my account.]

---

### 3. How do billing alerts help prevent unexpected charges?

**Your Answer:**
[You are more likely to find out about the unnecesary charges before they rack up.]

---

### 4. What threshold did you set for your billing alert and why?

**Your Answer:**
[1 Usd. I will just switch to a different account when my credit expires.]

---

### 5. What is your account alias and why did you choose it?

**Your Answer:**
- **Alias:** [ahmet-erdogan-ironhack]
- **Reasoning:** [Because it is really simple to remember and I am unlikely to forget it.]

---

### 6. What services are you currently using according to the Free Tier dashboard?

**Your Answer:**
[Nothing at the moment.]

---

## Bonus Challenges Completed (Optional)

### Challenge 1: Multiple Billing Alert Thresholds

- [ ] $5 threshold
- [ ] $25 threshold
- [ ] $50 threshold

**Screenshots (if completed):**
[Add screenshots here]

---

### Challenge 2: CloudTrail Enabled

- [ ] CloudTrail enabled
- [ ] Logging to S3 configured

**Notes:**
[Add any notes about CloudTrail setup]

---

### Challenge 3: AWS Trusted Advisor Reviewed

- [ ] Accessed Trusted Advisor
- [ ] Reviewed recommendations

**Key recommendations found:**
[List any recommendations you found]

---

## Lessons Learned

**What was the most challenging part of this lab?**

[Fork]

---

**What would you do differently next time?**

[Go step by step]

---

**What security practices will you implement going forward?**

[Extra billing protections]

---

## Checklist Before Submission

- [ ] All required screenshots captured and saved
- [ ] Screenshots are clear and show relevant information
- [ ] All reflection questions answered thoroughly
- [ ] Account alias documented
- [ ] Free Tier usage documented
- [ ] Work committed to Git
- [ ] Pull request created
- [ ] PR URL submitted to Student Portal

---

**Lab Completed By:** [Ahmet Erdogan]  
**Date:** [02.02.2026]
