# How to Deploy Your Islamic Calendar Application

## Problem Identified

You encountered an error when trying to push to GitHub because the repository URL was incorrect. The error message showed:

```
remote: Repository not found.
fatal: repository 'https://github.com/YOUR_USERNAME/REPO_NAME.git/' not found
```

## Solution

Follow these steps to correctly deploy your application to GitHub:

### 1. Create Your Repository on GitHub

1. Go to [GitHub](https://github.com/) and sign in
2. Click the '+' button in the top right corner and select 'New repository'
3. Name your repository (e.g., `islamic-calendar`)
4. Make sure it's set to 'Public'
5. Click 'Create repository'

### 2. Set Up the Correct Remote URL

Run these commands in your terminal, replacing the placeholders with your actual information:

```powershell
# Remove any existing remote (if needed)
git remote remove origin

# Add the correct remote URL with your GitHub username and repository name
git remote add origin https://github.com/DARK0810/islamic-calendar.git

# Push your code to GitHub
git push -u origin master
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on 'Settings' tab
3. Scroll down to the 'Pages' section
4. Under 'Source', select 'Deploy from a branch'
5. Select 'master' branch and click 'Save'

### 4. Access Your Website

After a few minutes, your site will be available at:
`https://DARK0810.github.io/islamic-calendar/`

## Alternative Deployment Options

If you prefer not to use GitHub Pages, you can also deploy to:

- **Netlify**: Free hosting with automatic deployments from GitHub
- **Vercel**: Similar to Netlify with excellent performance
- **Firebase Hosting**: Google's hosting platform with free tier

All these options provide free hosting for static websites like your Islamic Calendar application.