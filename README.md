## 👨🏻‍💻️ BITB-2.0

This educational project demonstrates how **Browser-in-the-Browser (BITB)** attacks work, where hackers use fake browser windows (via **iframes**) to trick users into entering login credentials.

---

## 🚨 Protect Yourself:
Always verify URLs, enable 2FA, and avoid entering credentials in pop-up windows. Also, ensure your website is protected from being embedded in an **iframe**.

---

## 🛡️ Protect Web from Iframed:

Websites can prevent their content from being embedded in iframes by using HTTP headers like **X-Frame-Options** or **Content-Security-Policy (CSP)**. This prevents attackers from creating fake login pages inside iframes on malicious sites.

- **X-Frame-Options**: Use this header with `DENY` or `SAMEORIGIN` values to block your site from being embedded in iframes.
  - `DENY`: The website cannot be embedded in any iframe.
  - `SAMEORIGIN`: The website can only be embedded in iframes from the same origin (same domain).

- **Content-Security-Policy (CSP)**: This provides more granular control over which domains can embed your site, helping protect against **BITB attacks**.

---

## 🌐 Web Using Iframe Protection:

Many large companies, such as **Google**, **Facebook**, and **Twitter**, block their sites from being embedded in iframes to prevent phishing and other types of attacks.

---

**🌐 Free Hosting & Subdomain**

> https://youtu.be/TV8CI3w6P

---

**📸 How does this look?**

![Screenshot1](https://i.postimg.cc/4ydZzp6T/Screenshot-2025-07-29-17-23-45-83-40deb401b9ffe8e1df2f1cc5ba480b12.jpg)

![Screenshot2](https://i.postimg.cc/jqwRd4Sz/Screenshot-2025-07-29-17-27-59-11-40deb401b9ffe8e1df2f1cc5ba480b12.jpg)

**🎥 Educational Demo**
> https://youtube.com/shorts/nrfAEaHKOO4

---

> **⚠️ Warning:** This project is for **educational purposes only**. Never use it for malicious activities. Always obtain **explicit consent** before conducting a
ny security tests.
