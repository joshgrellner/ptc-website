# Penley Transportation Company Website

## 🚀 Quick Setup Guide for GitHub Pages

### Step 1: Create GitHub Account (if needed)
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create a free account

### Step 2: Create New Repository
1. Click the **+** icon in top right → **New repository**
2. Name it: `penley-transportation` (or your preferred name)
3. Make it **Public** (required for free GitHub Pages)
4. DON'T initialize with README (we have our own)
5. Click **Create repository**

### Step 3: Upload Files
1. Click **uploading an existing file** link on the repository page
2. Drag and drop ALL these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - All image files (`.jpg`, `.jpeg`, `.png`)
3. Type commit message: "Initial website upload"
4. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. In your repository, go to **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** (or master)
5. Select **/ (root)** folder
6. Click **Save**

### Step 5: Access Your Site
- Your site will be live at: `https://[your-username].github.io/penley-transportation/`
- It may take 5-10 minutes to go live initially

### Step 6: Connect Your Custom Domain (from Squarespace)

#### In GitHub:
1. Go to **Settings → Pages**
2. Under **Custom domain**, enter: `penleytransportation.com` (or your domain)
3. Click **Save**
4. Check **Enforce HTTPS**

#### In Squarespace:
1. Log into Squarespace
2. Go to **Settings → Domains**
3. Click on your domain
4. Go to **DNS Settings**
5. Add these records:

**For apex domain (penleytransportation.com):**
- Type: A
- Host: @
- Points to: 185.199.108.153
- Type: A
- Host: @
- Points to: 185.199.109.153
- Type: A
- Host: @
- Points to: 185.199.110.153
- Type: A
- Host: @
- Points to: 185.199.111.153

**For www subdomain:**
- Type: CNAME
- Host: www
- Points to: [your-username].github.io

### 📁 Files Included
- `index.html` - Main website structure
- `styles.css` - All styling
- `script.js` - JavaScript functionality
- Image files:
  - `Map.jpeg` - Service area map
  - `Truck-trailer.jpeg` - Fleet image
  - `wellsite-operations.jpg` - Hero background
  - `PTC_Logo.png` - Company logo
  - Other supporting images

### 🔧 Making Updates
1. Edit files locally
2. Go to your repository on GitHub
3. Click on the file you want to update
4. Click the pencil icon to edit
5. Make changes and commit

Or upload new versions:
1. Navigate to your repository
2. Click **Add file → Upload files**
3. Upload updated files
4. Commit changes

### 📞 Support
For issues with:
- **GitHub Pages**: Check [GitHub Pages Documentation](https://docs.github.com/en/pages)
- **Domain setup**: [Configuring custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---
Website built for Penley Transportation Company
Family-owned crude oil transportation since 2013
Serving Oklahoma, Kansas, Texas & New Mexico