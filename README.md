# How to Host Your Profile Page on GitHub Pages (FREE)

## Step 1: Create GitHub Account
1. Go to https://github.com
2. Click "Sign Up" and create free account

## Step 2: Create New Repository
1. Click "+" icon (top right) → "New repository"
2. Repository name: `profile` (or any name you like)
3. Make it **Public**
4. Check "Add a README file"
5. Click "Create repository"

## Step 3: Upload Your Profile Page
1. Open your new repository
2. Click "Add file" → "Upload files"
3. Drag and drop the `index.html` file from this folder
4. Click "Commit changes"

## Step 4: Enable GitHub Pages
1. Go to repository "Settings" (tab at top)
2. Scroll down to "Pages" (left sidebar)
3. Under "Source", select "Deploy from a branch"
4. Branch: select "main", folder: "/ (root)"
5. Click "Save"
6. Wait 2-3 minutes

## Step 5: Get Your Link
Your profile will be live at:
```
https://YOUR_USERNAME.github.io/profile
```

Example: If your username is `miranali` and repo is `profile`:
```
https://miranali.github.io/profile
```

## Step 6: Add Your Photo
For profile photo, you have 2 options:

### Option A: Use ImgBB (Easy)
1. Go to https://imgbb.com
2. Click "Start uploading"
3. Upload your photo
4. Copy the "Direct link"
5. Replace the image URL in index.html

### Option B: Upload to GitHub
1. Upload photo to your repository
2. Use URL: `https://YOUR_USERNAME.github.io/profile/photo.jpg`

## Step 7: Edit Your Info
Edit index.html and change:
- Name
- Title
- Company
- Phone numbers
- Emails
- Websites
- Address
- Photo URL

## Step 8: Generate QR Code
1. Open your Flutter app
2. Create profile
3. Select "Web Link" tab
4. Enter your GitHub Pages URL
5. Download QR code

## Done!
Now when anyone scans your QR code, they'll see your beautiful profile page!

---

## Quick Customization Guide

### Change Colors
Find this line in index.html:
```css
background: linear-gradient(135deg, #7CB9A8 0%, #5B9A8B 50%, #3D7A6D 100%);
```
Change the hex colors (#7CB9A8, etc.) to your preferred colors.

### Add More Phone Numbers
Copy this block and paste it:
```html
<a href="tel:+YOUR_NUMBER" class="contact-item">
    <div class="contact-icon">
        <i class="fas fa-phone"></i>
    </div>
    <div class="contact-info">
        <div class="contact-label">Mobile</div>
        <div class="contact-value">+YOUR NUMBER</div>
    </div>
</a>
```

### Add Social Links
Add icons like:
- `fa-facebook` - Facebook
- `fa-instagram` - Instagram
- `fa-linkedin` - LinkedIn
- `fa-twitter` - Twitter
- `fa-whatsapp` - WhatsApp

Example:
```html
<a href="https://wa.me/8801711565070" target="_blank" class="contact-item">
    <div class="contact-icon">
        <i class="fab fa-whatsapp"></i>
    </div>
    <div class="contact-info">
        <div class="contact-label">WhatsApp</div>
        <div class="contact-value">+880 1711565070</div>
    </div>
</a>
```
