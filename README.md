# Community Newsletter
Community Newsletter CMS — a lightweight, backend‑free blog platform for creating, editing, publishing, and deploying posts with secure automation, credential rotation, and compliance logging.

# About 
Community Newsletter CMS is a lightweight, backend‑free platform designed to help community teams create, edit, and publish newsletters with ease. Built on Netlify for deployment and GitHub Actions for automation, it combines the simplicity of a blog editor with secure credential rotation, GPG key management, and compliance logging.

This project ensures that every newsletter is published seamlessly while maintaining strong governance over secrets and keys. With built‑in dry‑run testing, rollback safety nets, and Slack/email notifications, the system is resilient, transparent, and ready for community collaboration.

Whether you’re writing posts, deploying updates, or managing security workflows, Community Newsletter CMS provides a secure, automated pipeline that balances simplicity with reliability.

# Features 
## Core CMS 
Posts — Create and manage newsletter posts with a simple editor.
Editor — Lightweight interface for writing and formatting content.
Publish — Push posts live with one click.
Deploy — Automatic deployment to Netlify for fast, reliable hosting. 

## Secure Automation 
Key Management — Collect, audit, and update GPG public keys; handle expiration and revocation.
Password Rotation — Automatically reset Netlify Identity test user credentials and update GitHub secrets.
Dry‑Run Mode — Safely simulate rotations on pull requests without touching production secrets.
Rollback — Backup and restore secrets if rotation fails, ensuring resilience.
Audit & Compliance — Generate logs and reports for transparency and governance.
Notifications — Slack/email alerts distinguish dry‑runs, full rotations, and rollback events. 

## Non‑Functional Strengths 
Backend‑Free — Runs entirely in GitHub Actions and Netlify, no server required.
Lightweight — Minimal setup, easy to maintain.
Transparent — Clear logs and alerts keep the team informed.
Community‑Ready — Open‑source design for collaboration and contribution. 

