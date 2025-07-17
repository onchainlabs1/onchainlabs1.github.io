# 🚀 onchainlabs1 Portfolio Website

Modern portfolio website built with Jekyll and Beautiful Jekyll theme, showcasing ML/AI projects and technical expertise.

## 🌟 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Professional Layout** - Clean, modern design focused on impressing recruiters
- **Project Showcase** - Detailed descriptions of ML/AI projects
- **SEO Optimized** - Built-in SEO features for better visibility
- **Fast Loading** - Optimized for performance

## 🎯 Sections

- **Home** - Hero section with professional introduction
- **About Me** - Detailed technical skills and professional profile
- **Projects** - Showcase of featured repositories and achievements
- **Contact** - Direct links to social media and professional networks

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to [GitHub](https://github.com)
2. Create a new repository named `your-username.github.io`
3. Make sure it's **public**

### Step 2: Upload Files
1. Upload all files from this directory to your new repository
2. Commit with message: "Initial portfolio setup"

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Scroll to **Pages** section
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

### Step 4: Customize Your Information
Edit these files with your personal information:

#### `_config.yml`
```yaml
# Update these lines:
author:
  name: "Your Name"
  email: "your-email@example.com"
  github: "your-github-username"
  linkedin: "your-linkedin-profile"
```

#### `aboutme.md`
- Update skills and experience
- Add your professional background
- Update contact information

#### `projects.md`
- Update project descriptions
- Add your specific repositories
- Customize technical details

### Step 5: Access Your Site
Your site will be available at: `https://your-username.github.io`

## 🛠️ Local Development (Optional)

If you want to test locally before deploying:

```bash
# Install Ruby and Bundler first
gem install bundler

# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Open http://localhost:4000
```

## 🎨 Customization

### Colors and Styling
Edit `assets/css/main.scss` to customize:
- Color scheme
- Fonts
- Layout spacing
- Animations

### Add New Pages
Create new `.md` files with front matter:
```markdown
---
layout: page
title: "Page Title"
subtitle: "Page subtitle"
---

Your content here...
```

### Navigation
Update `_config.yml` to add/remove navigation items:
```yaml
navbar-links:
  About: "aboutme"
  Projects: "projects"
  Blog: "blog"  # Add new pages here
```

## 📱 Mobile Optimization

The site is fully responsive and optimized for:
- ✅ Mobile phones
- ✅ Tablets
- ✅ Desktop computers
- ✅ Large screens

## 🔧 Troubleshooting

### Site Not Loading?
1. Check repository name is `username.github.io`
2. Ensure repository is public
3. Wait 5-10 minutes for GitHub Pages to build
4. Check Settings > Pages for any errors

### Need to Update?
1. Edit files directly on GitHub
2. Or clone repository and push changes
3. GitHub Pages will automatically rebuild

## 📞 Support

Need help customizing your portfolio?
- Check [Beautiful Jekyll documentation](https://beautifuljekyll.com/)
- Review [Jekyll documentation](https://jekyllrb.com/)
- Ask questions in GitHub Issues

## 🏆 Results

This portfolio is designed to:
- ✅ Impress recruiters and hiring managers
- ✅ Showcase technical skills effectively
- ✅ Demonstrate professional quality work
- ✅ Provide easy contact and networking
- ✅ Stand out from basic GitHub profiles

---

**Ready to launch your professional portfolio?** Follow the steps above and you'll have a stunning website in minutes!

*Built with ❤️ using Jekyll and Beautiful Jekyll theme* 