# FreezeNova S1 — Unblocked Games Site

A streamlined version of the FreezeNova unblocked games website, ready for quick deployment. This repository provides a **mini game portal** with minimal setup. Feel free to **fork**, **clone**, or **customize** it to suit your needs.

---

## Deployments

This project is deployed on several platforms for demonstration:

- **Vercel**  
  [https://freezenova.vercel.app/](https://freezenova.vercel.app/)  
  Automated Git integration and continuous deployment for every push.

- **Netlify**  
  [https://freezenova.netlify.app/](https://freezenova.netlify.app/)  
  Simple build setup, instant rollbacks, and deploy previews.

- **Surge**  
  [https://freezenova.surge.sh/](https://freezenova.surge.sh/)  
  Straightforward static hosting via CLI. Note that Surge has stricter size limits, so some games may be omitted here.

---

# Getting Started

1. **Clone or Fork the Repository**  
   - **Fork** from [freezenova/freezenova.github.io](https://github.com/freezenova/freezenova.github.io) if you intend to make changes.  
   - **Clone** locally if you just want to deploy:
     ```bash
     git clone https://github.com/freezenova/freezenova.github.io
     ```
   - The main branch has all the files you need to launch your unblocked games site.

2. **Deploying to Vercel**  
   1. **Create a Vercel Account**  
      Sign up at [vercel.com](https://vercel.com/) (GitHub login recommended).
   2. **Import the Project**  
      - Click **New Project** → **Import Git Repository**.  
      - Select your fork or the main repo.
   3. **Configure Build Settings**  
      - For a purely static site, Vercel auto-detects a suitable configuration.  
      - Ensure your **Output Directory** is the folder with `index.html` (usually the repo root).
   4. **Deploy**  
      - Click **Deploy**.  
      - After the build finishes, you’ll get a URL like `https://your-project-name.vercel.app/`.
   5. **Visit & Customize**  
      - Optionally, add a custom domain in the **Domains** section.

3. **Deploying to Netlify**  
   1. **Create a Netlify Account**  
      Sign up at [netlify.com](https://netlify.com/) (GitHub login recommended).
   2. **New Site from Git**  
      - Click **Add new site** → **Import from Git**.  
      - Connect to GitHub, then choose your repo.
   3. **Build and Publish**  
      - **Build Command**: leave empty if no build step is needed.  
      - **Publish Directory**: `./` if your `index.html` is in the root folder.
   4. **Deploy**  
      - Netlify automatically builds and hosts your site.  
      - You’ll get a subdomain like `your-site-name.netlify.app`.
   5. **Custom Domain**  
      - Set up a custom domain in the Netlify dashboard if desired.

4. **Deploying to Surge**  
   1. **Install Surge**  
      ```bash
      npm install --global surge
      ```
   2. **Build/Prepare Your Site** (if applicable)  
      If the site is already static, skip this step.
   3. **Deploy**  
      - Navigate to the folder with `index.html`.  
      - Run:
        ```bash
        surge
        ```
      - Enter your **email**, **project path**, and choose a **domain** (e.g., `freezenova.surge.sh`).
   4. **Check Your Site**  
      - Surge will provide a success message with the URL.  
      - Note that **Surge has file size limits**; large sites or files may not deploy fully.

---

## Next Steps & Customization

- **Custom Domain**: Each hosting platform supports easy custom domain setup.  
- **HTTPS**: All platforms (Vercel, Netlify, Surge) offer free SSL certificates.  
- **Automatic Updates**:  
  - **Vercel** and **Netlify** rebuild on every Git push.  
  - **Surge** requires manual redeployment (re-run `surge`).
- **Modify the Games**: Customize which games appear, update the layout, or add new sections to tailor it to your audience.

---

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

You are free to **share** (copy and redistribute) and **adapt** (remix, transform, and build upon) the material for non-commercial purposes, provided you give appropriate credit and indicate if changes were made.

---
