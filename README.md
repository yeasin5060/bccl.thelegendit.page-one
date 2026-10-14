# Bangladesh China Club · Living Culture Demo

A trilingual (English, বাংলা, 中文), interactive culture and club exploration experience for the Bangladesh China Club.

## Features
- **Trilingual support**: Instant language switching between English, Bengali, and Chinese.
- **Dynamic Living Scenes**: Canvas & SVG animated river, boat, lanterns, and sunrise.
- **Interactive Calligraphy & Tea Studio**: Ink canvas, audio synthesizers, and tea steeping animations.
- **Festival Highlights & Historical Silk Route**: Interactive timeline and cultural animations.
- **App Simulation**: Live member card, payment simulation (bKash/Nagad/Cards), stay & dine booking calculator, and AI club concierge chat.

## Vercel Deployment

### Option 1: Automatic Deployment via GitHub (Recommended)
1. Push this repository to GitHub:
   ```bash
   git add .
   git commit -m "feat: setup vercel deployment and index entry"
   git push origin main
   ```
2. Go to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import this repository (`yeasin5060/bccl.thelegendit.page-one`).
4. Click **"Deploy"** (Zero configuration required, `vercel.json` is pre-configured).

### Option 2: Deploy via Vercel CLI
Run the following in the project root:
```bash
npx vercel
```
For production deployments:
```bash
npx vercel --prod
```
