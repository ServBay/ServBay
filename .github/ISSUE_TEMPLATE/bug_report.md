---
name: 🐞 Bug Report (macOS)
about: Create a report to help us improve ServBay for macOS
title: "[BUG] A brief and clear title"
labels: bug, macos
assignees: ''

---

**Pre-submission Checklist:**

- [ ] I have used the built-in [**Troubleshoot**](https://support.servbay.com/faq/troubleshooting) feature to check for common issues.
- [ ] I have checked the [help center documentation](https://support.servbay.com/).
- [ ] I have searched the existing issues to prevent duplicates.
- [ ] I am using the [latest version of ServBay](https://www.servbay.com/download/).

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Actual behavior**
A clear and concise description of what actually happened.

**Screenshots or Logs**
If applicable, add screenshots or log files to help explain your problem. You can find ServBay logs in the following locations on macOS:

- **Service Logs (Nginx, PHP, MariaDB, etc.):**
  Log files for individual services are located within the `/Applications/ServBay/logs/` directory. Please check the relevant file for the service you are having issues with (e.g., `nginx/error.log`, `php/php-8.3.log`).

- **ServBay Helper Log:**
  For issues with the core application startup or background processes, you can monitor the helper log in real-time via the Terminal app:
  `tail -f /tmp/Dev.ServBay.macOS.ServBay.Helper.log`

**Environment:**
 - **ServBay Version:** [e.g., 1.14.1]
 - **macOS Version:** [e.g., 14.5 Sonoma]
 - **Chip:** [e.g., Apple M1, Intel]

**Additional context**
Add any other context about the problem here.