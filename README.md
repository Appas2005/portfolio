# Appas S - Software Developer Portfolio

Personal developer portfolio showcasing projects, skills, education, and contact information.

## 🚀 Live Deployment on Render

### Option A: Deploy as a Web Service (Recommended for full server support)
1. Log in to [Render](https://dashboard.render.com).
2. Click **New +** -> **Web Service**.
3. Connect your GitHub repository: `Appas2005/portfolio`.
4. Configure settings:
   - **Name**: `appas-portfolio`
   - **Runtime**: `Node`
   - **Build Command**: Leave empty or `npm install`
   - **Start Command**: `node server.js`
   - **Instance Type**: `Free`
5. Click **Create Web Service**. Your portfolio will be live at `https://appas-portfolio.onrender.com`.

### Option B: Deploy as a Static Site (Zero server maintenance)
1. Click **New +** -> **Static Site**.
2. Connect your GitHub repository: `Appas2005/portfolio`.
3. Configure settings:
   - **Publish Directory**: `./` (or leave empty)
   - **Build Command**: Leave empty
4. Click **Create Static Site**.

---

## 💻 Local Development
To preview the website locally:
```bash
node server.js
```
Open your browser at `http://localhost:3000`.
