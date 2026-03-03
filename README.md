# Postcraft — LinkedIn Post Generator
### Deploy once, share with anyone on any browser

---

## Deploy to Render.com (free, 5 minutes)

Render.com hosts your app at a public URL like `https://postcraft.onrender.com`
Anyone on Chrome, Safari, Edge, or any browser can use it.

### Steps

**1. Create a free GitHub account** (if you don't have one)
   - Go to github.com and sign up

**2. Create a new GitHub repository**
   - Click the + icon → New repository
   - Name it `postcraft`, set to Public, click Create

**3. Upload these files to the repository**
   Upload all files from this zip maintaining the folder structure:
   ```
   server.js
   package.json
   public/
     index.html
   ```
   - Click "uploading an existing file" on the repo page
   - Drag and drop all files
   - Click "Commit changes"

**4. Deploy on Render.com**
   - Go to render.com and sign up for free
   - Click "New +" → "Web Service"
   - Connect your GitHub account and select your postcraft repo
   - Render auto-detects Node.js — just click Deploy
   - Wait ~2 minutes for the build to finish

**5. Share your URL**
   - Render gives you a URL like `https://postcraft-xxxx.onrender.com`
   - Share that link with anyone — they just need a browser

---

## How it works for users

1. Open the URL in any browser (Chrome, Safari, Edge, Firefox)
2. Enter their own Anthropic API key (free at console.anthropic.com)
3. Their key is saved in their browser only — never stored on your server
4. Generate posts — each person uses their own API key and pays their own usage

---

## Local development (optional)

If you want to run it locally first:
```
npm install
npm start
```
Then open http://localhost:3000

---

## Requirements
- Node.js 18+ (Render provides this automatically)
- Users need their own Anthropic API key
