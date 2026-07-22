# Legal Pages

Static legal pages for TikTok Developer App registration.

## Files

- `terms.html` - Terms of Service
- `privacy.html` - Privacy Policy

## Deploy to GitHub Pages

### Option A: Create a new repository

1. Create a new repository on GitHub (e.g., `legal-pages`)
2. Open terminal in this folder and run:

```powershell
git remote add origin https://github.com/FIT-dev-AI/legal-pages.git
git branch -M main
git push -u origin main
```

3. Go to repository **Settings** > **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### Option B: Push to existing repository

If you prefer to use your existing repository (`Html-Postiz`):

```powershell
git remote add origin https://github.com/FIT-dev-AI/Html-Postiz.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in Settings > Pages.

## After Deployment

Once deployed, your pages will be available at:

```
https://FIT-dev-AI.github.io/Html-Postiz/terms.html
https://FIT-dev-AI.github.io/Html-Postiz/privacy.html
```

Or if using a separate repository:

```
https://FIT-dev-AI.github.io/legal-pages/terms.html
https://FIT-dev-AI.github.io/legal-pages/privacy.html
```

## TikTok Developer App Setup

Use these URLs in your TikTok Developer App registration:

- **Terms of Service URL:** `https://FIT-dev-AI.github.io/Html-Postiz/terms.html`
- **Privacy Policy URL:** `https://FIT-dev-AI.github.io/Html-Postiz/privacy.html`

Replace the domain with your actual GitHub Pages URL after deployment.

## Before Using for Real Business

**Important:** Replace `[YOUR_EMAIL]` placeholders in both HTML files with your actual contact email. Then have a qualified attorney review these documents for your specific business use case.
