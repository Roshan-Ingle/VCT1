Vibe Code Tool v2 🚀
The Instant Deployment & Management Hub for GitHub Pages
Vibe Code Tool is a high-performance, single-file browser utility designed for "Vibe Coders" and rapid prototypers. It allows you to move from a local HTML file to a live URL in seconds, entirely from your browser (mobile or desktop), without ever touching a terminal or the complex GitHub settings menus.
💡 Why This Tool?
Traditionally, hosting a static site on GitHub requires multiple manual steps: creating a repo, uploading files, navigating to settings, and enabling Pages.
Vibe Code Tool collapses this workflow. It serves as a lightweight "Control Center" that automates the boring parts of deployment so you can focus on building.
✨ Features
1. Instant Site Launch (v1)
 * Auto-Provisioning: Creates a new repository on your GitHub account automatically.
 * Direct Push: Encodes and uploads your file as index.html instantly.
 * Auto-Pages: Configures GitHub Pages settings silently so the site is live immediately.
 * Live Status Tracking: Real-time polling of GitHub's build status.
2. Full Repo Management (v2)
 * Dashboard View: Fetch and filter through your existing project portfolio.
 * One-Click Updates: Select an existing repo and overwrite it with new code to update your live site.
 * Site Kill-Switch: "Unpublish" (disable GitHub Pages) without deleting your code.
 * Power Actions: Rename or permanently delete repositories directly from the app interface.
3. Security-First Architecture
 * Zero-Backend: Runs entirely in your browser. No data or tokens are ever sent to a third-party server.
 * Cryptographic Vault: Uses AES-GCM encryption to protect your Personal Access Token (PAT) in memory during the session.
 * Transparent: As a single-file HTML tool, the source code is 100% inspectable.
🚀 How to Use
 * Get a GitHub Token: Create a Personal Access Token (fine-grained) with Contents (write) and Pages (write) permissions. If you want to delete repos via the tool, add the Administration permission.
 * Open the Tool: Open Vibe Code Tool 1.html in any modern browser.
 * Authenticate: Paste your token into the secure vault.
 * Deploy: - Go to the Deploy Site tab.
   * Enter a project name and select your HTML file.
   * Hit Launch and watch it go live.
 * Manage: - Switch to the Manage Repos tab to update, rename, or delete existing projects.
🛠 Technical Stack
 * UI: Material Design 3 (MD3) Dark Theme
 * API: GitHub REST API
 * Security: Web Crypto API (AES-GCM)
 * Framework: Vanilla JavaScript (No dependencies)
📝 License
This tool is open-source and free to use. Built with Vibe Code energy.
Disclaimer: This tool communicates directly with the GitHub API. Ensure your Personal Access Tokens are kept private and never shared.
