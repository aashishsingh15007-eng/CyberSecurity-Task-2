Phishing Email Analysis Report

1. Phishing Email Sample Text
**From:** PayPal Security <support@paypaI-update-center.com>  
**To:** user@example.com  
**Subject:** URGENT: Your account has been suspended!  

**Email Body:**  
Dear Customer,  

We detected unauthorized login attempts to your account from an unknown IP address. For your safety, we have temporarily suspended your account access.  

You must verify your identity within 24 hours, otherwise your account will be permanently closed and your funds frozen.  

Please click the link below to restore your account immediately:  
[Restore My Account Now](http://secure-verification-paypal.net/login)  

Thank you,  
PayPal Security Team  

---

2. Phishing Indicators Found

After analyzing the sample email above, I identified the following phishing traits:

1. **Spoofed Sender Address:** The domain name looks like `paypaI-update-center.com`. If you look closely, the "l" in PayPal is actually a capital "I" (paypaI). This is a typo-squatting technique used to mimic the official domain.
2. **Generic Greeting:** The email addresses the user as "Dear Customer" instead of using their actual legal name, which a real financial institution would typically do.
3. **Urgent and Threatening Language:** The subject line uses "URGENT" and the body threatens that the account will be "permanently closed within 24 hours" if immediate action isn't taken. This creates panic so the victim acts without thinking.
4. **Mismatched / Suspicious URL:** The text says "Restore My Account", but when hovering over the link, it points to `http://secure-verification-paypal.net/login` instead of the official `https://www.paypal.com`. Also, it uses insecure `http` instead of `https`.
