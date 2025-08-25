# Vercel Deployment Instructions for AHP Mod 2.0

## Quick Deploy to Vercel

### Option 1: Web Interface (Recommended)
1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click "New Project"
3. Upload the project folder or connect via Git
4. Set project name to: **ahpmod2**
5. Click "Deploy"

### Option 2: CLI Deployment
```bash
# Install Vercel CLI globally
npm install -g vercel

# Login to Vercel
vercel login

# Deploy from project directory
cd "c:\Users\digit\CascadeProjects\AHPMOD PRESENT 1"
vercel --name ahpmod2
```

## Project Structure Ready for Deployment
```
├── index.html              # Landing page
├── presentation.html       # Main responsive presentation
├── slide1.html - slide4.html  # Individual slides
├── package.json            # Project metadata
├── vercel.json             # Vercel configuration
├── .gitignore              # Git ignore rules
└── README.md               # Documentation
```

## Key Files for Vercel:
- **`vercel.json`** - Deployment configuration
- **`package.json`** - Project metadata with name "ahpmod2"
- **`index.html`** - Entry point with navigation to both presentation formats

## Expected URLs after deployment:
- Main site: `https://ahpmod2.vercel.app`
- Full presentation: `https://ahpmod2.vercel.app/presentation.html`
- Individual slides: `https://ahpmod2.vercel.app/slide1.html` etc.

## Features Included:
✅ Fully responsive design (no scrolling on any screen size)
✅ Keyboard navigation (arrow keys, spacebar)
✅ Print-friendly CSS for PDF export
✅ Professional AHP Mod 2.0 branding
✅ External image hosting (no local image dependencies)
✅ Cross-browser compatibility

The presentation is ready to deploy to Vercel with the project name "ahpmod2".
