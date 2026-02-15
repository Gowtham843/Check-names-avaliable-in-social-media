# Social Handle Availability Checker

Check if usernames are available on Instagram, YouTube, X (Twitter), and LinkedIn.

## 🚀 Quick Deploy to Vercel

### Option 1: Using Vercel CLI
```bash
# Install Vercel CLI globally
npm install -g vercel

# Navigate to your project folder
cd your-project-folder

# Deploy
vercel
```

### Option 2: Using Vercel Dashboard
1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

## 📁 Project Structure
```
your-project/
├── index.html          # Main page
├── styles.css          # Styling
├── package.json        # Dependencies
├── vercel.json         # Vercel configuration
└── api/
    └── check.js        # API endpoint
```

## 🛠️ Local Development

1. Install dependencies:
```bash
npm install
```

2. Run locally with Vercel Dev:
```bash
vercel dev
```

3. Open `http://localhost:3000`

## 📝 Features

- ✅ Multiple input methods (TXT, CSV, Excel, Manual)
- ✅ Bulk username checking
- ✅ Real-time availability status
- ✅ Clean, modern UI
- ✅ Mobile responsive

## 🔧 Troubleshooting

### 404 Error on Homepage
Make sure your files are at the **root level** of your project:
- `index.html` must be in the root
- `styles.css` must be in the root
- `api/` folder must be in the root

### API Not Working
1. Check that `node-fetch` is installed: `npm install`
2. Verify `api/check.js` is in the `/api` folder
3. Redeploy: `vercel --prod`

## 📦 Dependencies

- `node-fetch` - For making HTTP requests in the API

## 🌐 Live Demo

After deployment, your app will be available at:
`https://your-project-name.vercel.app`
