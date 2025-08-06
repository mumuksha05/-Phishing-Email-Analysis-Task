# 🛡️ Phishing Email Analysis Report

---

## 📌 Email Subject:
Immediate Action Required - Account Suspended

## 1. 🧑‍💻 Spoofed Sender Address:
- Displayed as: `support@paypal-alert.com`
- Real PayPal emails come from `@paypal.com`

## 2. 🧾 Header Discrepancy:
- IP address: `203.0.113.10` — unrelated to PayPal
- SPF and DKIM: Failed authentication checks

## 3. 🔗 Suspicious Links:
- Link Text: `Verify Now`
- Actual URL: `http://paypal-login-alert.ru/verify`

## 4. 🚨 Threatening Language:
- “Your account has been temporarily suspended”
- “Failure to confirm will result in permanent suspension”

## 5. 🔍 Mismatched URLs:
- Displayed: Looks like PayPal
- Actual: Malicious Russian domain

## 6. 📉 Spelling/Grammar Errors:
- “We have noticed unusual activity” — vague
- "permanent suspension of your account" — robotic tone

---

## ✅ Conclusion:

The email shows multiple red flags:
- Spoofed sender address
- Failed SPF/DKIM checks
- Malicious URLs masked as PayPal
- Threatening, urgent tone
- Grammar and spelling inconsistencies

**Final Verdict: Phishing Email Detected**