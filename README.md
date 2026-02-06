# NewInternalCampaign1 - Static HTML Website

This is a static HTML website ready for deployment on Vercel.

## Deployment Instructions

### Deploy to Vercel via GitHub

1. **Push to GitHub** (if not already done):

   ```bash
   git add .
   git commit -m "Initial commit: Prepare for Vercel deployment"
   git push origin main
   ```

2. **Connect to Vercel**:

   - Go to [vercel.com](https://vercel.com)
   - Sign in with your GitHub account
   - Click "Add New Project"
   - Import your GitHub repository (NewInternalCampaign1)

3. **Configure Project**:

   - Framework Preset: **Other** (or leave as detected)
   - Root Directory: `./` (leave as default)
   - Build Command: (leave empty for static sites)
   - Output Directory: (leave empty for static sites)
   - Click "Deploy"

4. **Done!** Your site will be live at `your-project.vercel.app`

### Configuration

The `vercel.json` file includes:

- Clean URLs (removes `.html` extensions)
- Trailing slash handling
- Static file serving optimization

## Project Structure

- `index.html` - Main landing page
- `wp-content/` - WordPress content assets
- `wp-includes/` - WordPress includes
- Various static assets (CSS, images, etc.)
# 1st-task
