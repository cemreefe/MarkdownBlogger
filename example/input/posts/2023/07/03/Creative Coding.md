---
emoji:  💻
tags:   coding
        dev
---

# Creative Coding

This is a blog post with a code block

```java
public class NotificationService {
  private EmailService emailService = new SmsService(); // modify this line
  public void sendNotification(String email, String message) {
    emailService.sendEmail(email, message); // replace with emailService.sendSms(phone, message);
  }
}
```