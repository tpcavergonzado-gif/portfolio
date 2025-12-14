# Personal Portfolio Website

A modern, dark-themed personal portfolio website with Home, About, Contact, and Photos pages.

## Features

- 🎨 Modern dark theme with gradient accents
- 📱 Fully responsive design
- ✨ Smooth animations and transitions
- 🚀 Fast and lightweight
- 🎯 Clean and professional design

## Pages

- **Home** - Welcome page with hero section and features
- **About** - Personal introduction and skills showcase
- **Contact** - Contact information and message form
- **Photos** - Gallery of your work/projects

## How to Push to GitHub and Deploy

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Sign up for a free account

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - **Important**: This specific naming format enables GitHub Pages automatically
4. Make it **Public** (required for free GitHub Pages)
5. **Don't** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### Step 3: Install Git (if not already installed)
1. Download Git from [git-scm.com](https://git-scm.com/downloads)
2. Install it with default settings
3. Open Git Bash (Windows) or Terminal (Mac/Linux)

### Step 4: Initialize Git and Push Your Code

Open your terminal/command prompt in the project folder and run these commands:

```bash
# Navigate to your project folder
cd C:\Users\rosal\OneDrive\Desktop\carlos

# Initialize Git repository
git init

# Add all your files
git add .

# Create your first commit
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote (replace YOUR_USERNAME with your actual username)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Note**: You'll be prompted to enter your GitHub username and password (or personal access token).

### Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait a few minutes, then visit: `https://YOUR_USERNAME.github.io`

Your portfolio will be live! 🎉

## Customization

### Change "Your Name" to Your Actual Name

1. Open each HTML file (index.html, about.html, contact.html, photos.html)
2. Find and replace "Your Name" with your actual name
3. Update the `<title>` tags in each file

### Add Your Photo

1. Add your photo to the project folder
2. In `about.html`, replace the photo placeholder:
   ```html
   <div class="gradient-box photo-placeholder">
       <img src="your-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 20px;">
   </div>
   ```

### Update Contact Information

1. Open `contact.html`
2. Update the email, phone, location, and LinkedIn information

### Add Real Photos

1. Add your photos to a folder (e.g., `images/`)
2. In `photos.html`, replace the placeholders:
   ```html
   <div class="photo-placeholder-img">
       <img src="images/photo1.jpg" alt="Description" style="width: 100%; height: 100%; object-fit: cover;">
   </div>
   ```

### Customize Colors

1. Open `styles.css`
2. Modify the CSS variables at the top:
   ```css
   :root {
       --accent-start: #3b82f6;  /* Change to your preferred color */
       --accent-end: #8b5cf6;    /* Change to your preferred color */
   }
   ```

## File Structure

```
portfolio/
├── index.html      # Home page
├── about.html      # About page
├── contact.html    # Contact page
├── photos.html     # Photos page
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md      # This file
```

## Troubleshooting

### Git Authentication Issues
If you have trouble pushing to GitHub:
1. Use a Personal Access Token instead of password
2. Go to GitHub Settings → Developer settings → Personal access tokens
3. Generate a new token with `repo` permissions
4. Use this token as your password when pushing

### Pages Not Updating
- Wait 5-10 minutes after pushing changes
- Clear your browser cache
- Check the repository Settings → Pages to ensure it's enabled

### Need Help?
- GitHub Docs: [docs.github.com](https://docs.github.com)
- Git Tutorial: [git-scm.com/docs](https://git-scm.com/docs)

## License

This project is open source and available for personal use.

---

**Happy coding! 🚀**

