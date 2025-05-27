# Phishing Email Analysis Report

## 📨 Sample Email Snippet

```
From: support@securebanking-login.com
Subject: Urgent: Verify Your Account Now!

Dear Customer,

We noticed suspicious activity in your account. Please verify your identity immediately to avoid temporary suspension.

Click here to login and secure your account:
http://secure-login-now.com/login

Sincerely,
Secure Bank Security Team
```

## ⚠️ Phishing Traits Observed

### 1. **Spoofed Sender**
- The sender uses `support@securebanking-login.com`, mimicking a bank's address.
- Domain name is unrelated to actual bank (e.g., `securebanking-login.com` ≠ `securebank.com`).

### 2. **Mismatched & Suspicious Links**
- Displayed text claims to go to a bank, but hovering reveals: `http://secure-login-now.com/login`

### 3. **Urgent / Threatening Language**
- Email warns about account suspension to pressure quick action.

### 4. **Poor Grammar & Spelling**
- Words like "Sincerely" were misused or oddly formatted.
- Sentence structure lacks professionalism.

### 5. **Header Anomalies**
- IP address doesn't align with domain country.
- SPF/DKIM headers failed — indicating spoofing.

## 🛡️ Safety Recommendation
Never click suspicious links. Always verify via official website or contact customer service directly.

## 🔍 Conclusion
This is a classic phishing attempt exploiting urgency, spoofing, and link redirection techniques.
