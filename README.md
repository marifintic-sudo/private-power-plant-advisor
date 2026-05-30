# Private Power Plant Australia — AI Advisor
## Deploy to Render in 5 minutes (free)

---

### Step 1 — Upload to GitHub

1. Go to **github.com** and sign up / log in (free)
2. Click **"New repository"**
3. Name it: `private-power-plant-advisor`
4. Click **"Create repository"**
5. Click **"uploading an existing file"**
6. Upload ALL files from this folder:
   - `server.js`
   - `package.json`
   - `public/index.html`
7. Click **"Commit changes"**

---

### Step 2 — Deploy on Render

1. Go to **render.com** and sign up / log in (free)
2. Click **"New +"** → **"Web Service"**
3. Connect your GitHub account
4. Select your `private-power-plant-advisor` repository
5. Fill in these settings:
   - **Name:** private-power-plant-advisor
   - **Runtime:** Node
   - **Build Command:** `npm install`
   - **Start Command:** `node server.js`
6. Click **"Advanced"** → **"Add Environment Variable"**
   - Key: `ANTHROPIC_API_KEY`
   - Value: your key from console.anthropic.com
7. Click **"Create Web Service"**

---

### Step 3 — Share your link!

Render gives you a free URL like:
`https://private-power-plant-advisor.onrender.com`

Share that link with anyone — no API key needed on their end!

---

### Costs
- Render free tier: **$0/month** (sleeps after 15min inactivity, wakes on visit)
- Anthropic API: **~$0.01–0.03 per conversation**
- For high traffic, upgrade Render to paid ($7/month) so it doesn't sleep

---

### Need help?
Ask your Claude advisor to walk you through any step!
