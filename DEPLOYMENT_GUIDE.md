# Deployment Guide for Islamic Calendar Web Application

## Deploying to GitHub Pages

Follow these steps to deploy your Islamic Calendar web application to GitHub Pages:

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com/) and sign in to your account (or create one if you don't have it)
2. Click the '+' button in the top right corner and select 'New repository'
3. Name your repository (e.g., `islamic-calendar`)
4. Make sure the repository is set to 'Public'
5. Click 'Create repository'

### 2. Push Your Code to GitHub

Run these commands in your terminal, replacing `YOUR_USERNAME` with your GitHub username and `REPO_NAME` with your repository name:

```powershell
# Add the remote repository
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push your code to GitHub
git push -u origin master
```

### 3. Configure GitHub Pages

1. Go to your repository on GitHub
2. Click on 'Settings' tab
3. Scroll down to the 'GitHub Pages' section
4. Under 'Source', select 'master branch'
5. Click 'Save'

### 4. Access Your Deployed Website

After a few minutes, your site will be available at:
`https://YOUR_USERNAME.github.io/REPO_NAME/`

## Alternative Deployment Options

### Netlify

1. Sign up for a free account at [Netlify](https://www.netlify.com/)
2. Click 'New site from Git'
3. Select GitHub and authorize Netlify
4. Select your repository
5. Click 'Deploy site'

### Vercel

1. Sign up for a free account at [Vercel](https://vercel.com/)
2. Click 'Import Project'
3. Select 'Import Git Repository'
4. Enter your repository URL
5. Click 'Deploy'

## Maintaining Your Deployment

Whenever you make changes to your application:

1. Commit your changes locally:
   ```
   git add .
   git commit -m "Description of changes"
   ```

2. Push to GitHub:
   ```
   git push
   ```

3. GitHub Pages will automatically update your site with the new changes