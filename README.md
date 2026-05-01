# QRLJacking Simulation & Education Tool

A modern, visually-oriented web application designed to demonstrate the mechanics of **QRLJacking** (Quick Response Login Jacking). This project serves as an educational simulation to raise awareness about QR-based phishing and session hijacking.

---

## 🚀 Overview

QRLJacking is a social engineering attack where an attacker "relays" a legitimate login QR code to a victim. When the victim scans the code, they inadvertently authorize the attacker's device to access their account.

This tool provides:
- **Attacker Perspective**: A dashboard showing the relay process and session capture.
- **Victim Perspective**: A landing page that simulates a "hijacked" session and provides a comprehensive safety guide.
- **Educational Insights**: Data-driven statistics and actionable safety tips to prevent QR scams.

---

## 🛠️ Project Structure

```bash
├── index.html      # Attacker Dashboard & QR Relay Simulation
├── victim.html     # Victim Landing Page & Educational Guide
└── style.css       # Shared design system (Modern Dark Mode)
```

---

## 📖 How to Use

1.  **Open the Attacker Dashboard**: Launch `index.html` in your browser.
2.  **Generate the Relay**: The dashboard automatically detects its hosting URL and generates a QR code pointing to the `victim.html` page.
3.  **Simulate the Scan**:
    *   **Real Scenario**: Scan the QR code with a mobile device (requires the files to be hosted on a local network or public server).
    *   **Manual Simulation**: Click the **"MANUAL SIMULATE SCAN"** button on the dashboard.
4.  **Observe the Attack**:
    *   The **Hacker Console** will log the session relay and token capture.
    *   The **Access Card** will update to show a "HIJACK SUCCESSFUL" status.
    *   A full-screen **"TARGET HACKED"** overlay will confirm the breach.
5.  **Learn**: On the victim's side (`victim.html`), click **"Learn How to Stay Safe"** to access the Cyber Awareness Guide.

---

## 🛡️ Key Safety Tips

*   **Check the URL**: Always verify the destination link before authorizing any action.
*   **Verify Location**: Pay attention to login prompts that show device location or IP address.
*   **Use Official Apps**: Only scan sensitive authentication codes within the service's official app.
*   **Enable MFA**: Use hardware security keys or authenticator apps for an extra layer of protection.

---

## 📊 Statistics at a Glance

*   **400%** global rise in QR-related scams between 2023 and 2025.
*   **1 in 8** phishing emails now contain malicious QR codes.
*   Over **₹56 Crore** lost to QR fraud in India alone within the last two fiscal years.

---

*This project was developed for educational purposes to highlight the security risks associated with QR-based authentication.*
