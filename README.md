# 🚀 ISS Overhead Notifier

Get an email when the International Space Station (ISS) is passing above you during nighttime!

## 📜 About

This Python project checks two conditions:

1. **Is the ISS currently overhead?**  
2. **Is it currently night at your location?**

If both are true, the program will **send you an email alert** so you can step outside and try to spot the ISS in the sky!

It uses:
- `open-notify` API to get ISS location
- `sunrise-sunset` API to check day/night
- `smtplib` to send an email notification

## 🛠️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/iss-overhead-notifier.git
   cd iss-overhead-notifier
