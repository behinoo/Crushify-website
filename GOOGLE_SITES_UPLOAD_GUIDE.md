# 📱 How to Publish Crushify Homepage on Google Sites

This guide will help you publish your beautiful Crushify homepage on Google Sites step by step.

---

## 🎯 Option 1: Embed HTML in Google Sites (Recommended)

Google Sites doesn't directly support uploading HTML files, but you can embed the content. Here's how:

### Step 1: Host Your HTML File
First, you need to host your HTML file somewhere online:

#### Option A: Use GitHub Pages (Free & Easy)
1. Go to [github.com](https://github.com) and sign in
2. Create a new repository called `crushify-website`
3. Upload the `index.html` file from `website/` folder
4. Go to **Settings** → **Pages**
5. Under "Source", select **main** branch and **/(root)**
6. Click **Save**
7. Your site will be live at: `https://yourusername.github.io/crushify-website/`

#### Option B: Use Firebase Hosting (Free tier available)
```powershell
# Install Firebase CLI
npm install -g firebase-tools

# Login to Firebase
firebase login

# Initialize hosting
firebase init hosting

# Deploy
firebase deploy
```

### Step 2: Create Google Site
1. Go to [sites.google.com](https://sites.google.com)
2. Click **+ Blank** to create a new site
3. Give it a name like "Crushify"

### Step 3: Embed the HTML
1. In Google Sites editor, click **Insert** → **Embed**
2. Select **By URL** tab
3. Paste your hosted HTML URL (from GitHub Pages or Firebase)
4. Click **Insert**
5. Resize the embed to fill the page

### Step 4: Publish
1. Click the **Publish** button (top right)
2. Choose your site URL (e.g., `sites.google.com/view/crushify`)
3. Click **Publish**

---

## 🎨 Option 2: Recreate in Google Sites Native Editor

If you prefer a pure Google Sites solution without embedding:

### Step 1: Create New Google Site
1. Go to [sites.google.com](https://sites.google.com)
2. Click **+ Blank** to create a new site
3. Click on "Untitled site" to rename it to **Crushify**

### Step 2: Set Theme & Colors
1. Click **Themes** in the right panel
2. Select a theme (recommended: **Simple** or **Diplomat**)
3. Click the color palette icon
4. Set primary color to purple: `#764ba2`
5. Set secondary color to pink: `#f093fb`

### Step 3: Create Hero Section
1. Click **Insert** → **Image**
2. Upload your app icon (`assets/icon.JPG`)
3. Add a **Title** text box: "Crushify 💕"
4. Add a **Subtitle**: "Amplify Your Crush"
5. Add body text with the app description
6. Insert a **Button** → Link to your Play Store page

### Step 4: Add Features Section
1. Add a **Section divider**
2. Add heading: "✨ Powerful Features"
3. Use **Insert** → **Layout** → Choose 3-column layout
4. Add feature cards with icons and descriptions:

| Icon | Title | Description |
|------|-------|-------------|
| 💬 | AI Reply Generation | Get contextual, witty replies powered by advanced AI |
| 📷 | Screenshot OCR | On-device text extraction keeps your data private |
| 👥 | Profile Management | Create workspaces for each match with conversation history |
| 📊 | Profile Analysis | AI-powered compatibility insights and openers |
| ✍️ | Bio Generator | Create compelling bios for any dating platform |
| ❤️ | 150+ Date Ideas | Curated activities filtered by category & budget |

### Step 5: Add How It Works Section
1. Add another section divider
2. Add heading: "🚀 How It Works"
3. Use numbered layout or text boxes:
   - **1. Capture** - Screenshot or type the message
   - **2. Choose Tone** - Select from 8+ response styles
   - **3. Get Replies** - AI generates perfect responses

### Step 6: Add Privacy Section
1. Add section with heading: "🔒 Privacy First"
2. Add 4 columns with icons:
   - 📱 On-Device OCR
   - 🗑️ Instant Deletion
   - 🔐 AES-256 Encryption
   - 🛡️ No Data Stored

### Step 7: Add Footer
1. Use **Insert** → **Footer**
2. Add links to:
   - Privacy Policy
   - Terms of Service
   - Contact: cognizenai@gmail.com
3. Add: "© 2025 CognizenAI. All rights reserved."

### Step 8: Add Pages
Create additional pages for:
1. **Privacy Policy** - Copy content from `assets/privacy-policy.md`
2. **Terms of Service** - Copy content from `assets/terms-of-service.md`

### Step 9: Preview & Publish
1. Click the **Preview** 👁️ icon to see how it looks
2. Click **Publish** button
3. Choose URL: `sites.google.com/view/crushify`
4. Click **Publish**

---

## 🔗 Option 3: Use Full External Hosting + Redirect

For the best experience with your custom HTML:

### Using GitHub Pages (Recommended)

1. **Create GitHub Repository**
   ```
   Repository name: crushify-website
   ```

2. **Upload Files**
   - Upload `website/index.html` to the repository
   - Rename to `index.html` in root

3. **Enable GitHub Pages**
   - Go to repository **Settings**
   - Scroll to **Pages** section
   - Select **main** branch, **/(root)** folder
   - Click **Save**

4. **Your Site is Live!**
   ```
   https://yourusername.github.io/crushify-website/
   ```

5. **Link from Google Site**
   - Create a simple Google Site
   - Add a button that redirects to your GitHub Pages URL

---

## 📋 Quick Copy-Paste Content for Google Sites

### Hero Text
```
Crushify 💕
Amplify Your Crush

Your AI-powered dating companion that helps you craft the perfect replies, 
analyze dating profiles, and boost your confidence in every conversation. 
Privacy-first, intelligent, and always by your side.
```

### Feature Descriptions

**AI Reply Generation**
Get contextual, witty replies powered by advanced AI. Just screenshot the conversation or type the message, and let Crushify craft the perfect response.

**Screenshot OCR**
Simply take a screenshot of any dating conversation. Our on-device OCR instantly extracts text while keeping your data private and secure.

**Profile Management**
Create individual workspaces for each match. Track conversations, store profile info, and get context-aware suggestions based on history.

**Profile Analysis**
Upload dating profile screenshots for AI-powered compatibility insights, personalized openers, and improvement suggestions.

**Bio Generator**
Create compelling dating profile bios optimized for Tinder, Bumble, Hinge, and more. Multiple styles and instant generation.

**150+ Date Ideas**
Discover curated date ideas filtered by category, budget, and duration. From adventures to romantic dinners, find the perfect activity.

---

## 🎨 Brand Colors for Google Sites

| Element | Color Code |
|---------|-----------|
| Primary Purple | `#764ba2` |
| Secondary Purple | `#667eea` |
| Accent Pink | `#f093fb` |
| Success Green | `#28a745` |
| Text Dark | `#333333` |
| Text Light | `#666666` |

---

## ✅ Publishing Checklist

- [ ] App icon uploaded
- [ ] Hero section with title and tagline
- [ ] Features section (6 features)
- [ ] How it works (3 steps)
- [ ] Privacy section (4 badges)
- [ ] Download/CTA section with Play Store link
- [ ] Footer with legal links
- [ ] Privacy Policy page created
- [ ] Terms of Service page created
- [ ] Site published and accessible
- [ ] Mobile preview checked
- [ ] All links working

---

## 🔗 Important Links to Include

| Page | Link |
|------|------|
| Google Play Store | `https://play.google.com/store/apps/details?id=com.cognizenai.crushify` |
| Privacy Policy | Link to your hosted privacy policy |
| Terms of Service | Link to your hosted terms |
| GitHub | `https://github.com/behinoo/Crushify` |
| Contact Email | `cognizenai@gmail.com` |

---

## 💡 Pro Tips

1. **Use High-Quality Images** - Upload screenshots of your app for visual appeal
2. **Mobile First** - Preview your site on mobile as most visitors will be on phones
3. **Fast Loading** - Keep images optimized and compressed
4. **SEO** - Add meta descriptions in Google Sites settings
5. **Analytics** - Connect Google Analytics to track visitors
6. **Custom Domain** - Consider adding a custom domain for professionalism

---

## 🆘 Need Help?

- **Google Sites Help**: [support.google.com/sites](https://support.google.com/sites)
- **GitHub Pages Guide**: [docs.github.com/pages](https://docs.github.com/pages)
- **Contact**: cognizenai@gmail.com

---

**Good luck with your Crushify website! 💕**
