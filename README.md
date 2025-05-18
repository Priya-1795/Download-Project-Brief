# Phishing Simulation Site

## Overview
This simple site has one page with a clickable link.  
When clicked, it sends you an email notification via FormSubmit and then redirects to a "You are phished!" thank-you page.

## Setup Instructions

1. Replace `your.email@example.com` in `index.html` form's `action` URL with your actual email.
2. Create a GitHub repository and push these files (`index.html`, `thank-you.html`, `README.md`) to the root directory.
3. In GitHub repo settings, enable **GitHub Pages** on the branch `main` or `master` and set folder to `/root`.
4. Visit your GitHub Pages URL (like `https://yourusername.github.io/reponame/`).
5. Share this URL with your employees for the phishing simulation.

## Notes

- You will receive an email each time someone clicks the link.
- FormSubmit sends emails without requiring server-side code.
- Check your email spam/junk folder in case emails go there.
- Customize the message or styling as needed.
