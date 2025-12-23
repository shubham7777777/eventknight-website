# Event Knight Website

Premium event production website for college cultural festivals. Black + Gold design matching your brand identity.

## Quick Deploy to Netlify (30 minutes)

### Step 1: Setup Formspree (5 mins)
**IMPORTANT: This is where your form submissions go!**

1. Go to [formspree.io](https://formspree.io) and create free account
2. Click "New Form"
3. Name it "Event Knight Contact"
4. Copy your form endpoint (looks like: `https://formspree.io/f/xyzabc123`)
5. In `index.html`, find TWO places that say `YOUR_FORM_ID` (lines ~30 and ~350)
6. Replace both with your actual form ID

**Where notifications go:**
- All form submissions email to: **eventknightc@gmail.com**
- You get instant email notifications
- Check spam folder first time
- Reply manually from Gmail

### Step 2: Create GitHub Repository (5 mins)
```bash
# Navigate to the website folder
cd eventknight-website

# Initialize git
git init
git add .
git commit -m "Event Knight website launch"

# Create repo on GitHub and push
# (Create new repo at github.com first, then run:)
git remote add origin https://github.com/YOUR_USERNAME/eventknight-website.git
git branch -M main
git push -u origin main
```

### Step 3: Deploy to Netlify (10 mins)

1. Go to [netlify.com](https://netlify.com) and sign in with GitHub
2. Click "Add new site" → "Import an existing project"
3. Select GitHub and authorize
4. Choose your `eventknight-website` repository
5. Build settings (leave defaults):
   - Build command: (leave empty)
   - Publish directory: `.` 
6. Click "Deploy site"
7. Wait 2 minutes - your site is live at: `random-name-123.netlify.app`

### Step 4: Connect Custom Domain (5 mins)

1. In Netlify dashboard, go to Site settings → Domain management
2. Click "Add custom domain"
3. Enter: `eventknight.in`
4. Netlify will show you DNS records to add

**In Hostinger DNS settings, add these records:**

| Type | Name | Value (from Netlify) |
|------|------|---------------------|
| A | @ | 75.2.60.5 |
| CNAME | www | YOUR-SITE.netlify.app |

*Note: DNS propagation takes 24-48 hours*

### Step 5: SSL Certificate (Automatic)

Netlify automatically provisions SSL certificate. Just:
1. Go to Site settings → Domain management → HTTPS
2. Click "Verify DNS configuration"
3. Wait 1-5 minutes for certificate
4. HTTPS will be enabled automatically

### Step 6: Update Instagram (2 mins)
□ Go to Instagram profile settings
□ Update bio link to: eventknight.in
□ Post story announcing website launch

---

## What's Included

✅ **Premium Design** - Black + Gold matching your logo
✅ **Real Event Photos** - Your actual work showcased
✅ **Lead Capture Popup** - Triggers at 5sec or 50% scroll
✅ **Mobile Responsive** - Perfect on all devices
✅ **Contact Form** - Submissions to eventknightc@gmail.com
✅ **Instagram Integration** - Direct links to @event.knight
✅ **WhatsApp Button** - Click-to-chat
✅ **SEO Optimized** - Proper meta tags
✅ **Fast Loading** - Optimized images

---

## Form Notifications - How It Works

**When someone submits:**
1. Form data sent to Formspree
2. Email sent to: eventknightc@gmail.com
3. You get instant notification
4. Reply manually from Gmail

**Formspree Free Tier:**
- 50 submissions/month
- Email notifications
- Spam filtering
- Export to CSV

**To add more emails:**
1. In Formspree dashboard
2. Go to form settings
3. Add CC recipients

---

## Next Steps After Launch

### Immediate (First Week)
1. **Test Contact Form**
   - Submit test inquiry
   - Check if email arrives at eventknightc@gmail.com
   - Check spam folder if not in inbox

2. **Update Instagram**
   - Add website link to bio
   - Post announcement story
   - Share portfolio screenshots

3. **Google Analytics** (Optional)
   - Create account at analytics.google.com
   - Add tracking code to website
   - Monitor visitor behavior

### Short Term (First Month)
1. **SEO Setup**
   - Submit sitemap to Google Search Console
   - Create Google Business Profile
   - Get listed on Google Maps

2. **Content Updates**
   - Add more event photos as you do events
   - Get 2-3 testimonials from past clients
   - Update portfolio section

3. **Professional Email** (Optional)
   - Get Google Workspace (₹140/month)
   - Setup contact@eventknight.in
   - More professional than Gmail

### Long Term
- Blog posts for SEO (optional)
- Case studies of major events
- Video content from events
- Expand service offerings

---

## File Structure

```
eventknight-website/
├── index.html              # Main website file
├── images/                 # All event photos
│   ├── Event_Knight_Logo__1_.png
│   ├── 9bd11247... .JPEG   # Hero concert shot
│   ├── F904DBE5....JPG     # Lighting setup
│   ├── C727A3B0....JPG     # Daytime setup
│   └── ... (more photos)
├── README.md              # This file
└── QUICKSTART.md          # Quick deployment checklist
```

---

## Editing the Website

Since you know code:

1. Open `index.html` in VS Code
2. Make your changes
3. Commit and push:
   ```bash
   git add .
   git commit -m "Updated content"
   git push
   ```
4. Netlify auto-deploys in 1-2 minutes

### Common edits:
- **Add photos**: Put in `images/` folder, reference in HTML
- **Update text**: Search and replace in index.html
- **Change colors**: Edit the `<style>` section
- **Form endpoint**: Lines ~30 and ~350

---

## Cost Summary

**Year 1:**
- Domain (eventknight.in): ₹549 ✓ PAID
- Hosting (Netlify): ₹0 (free forever)
- SSL Certificate: ₹0 (automatic)
- Contact form (Formspree): ₹0 (50/month free)
- **Total: ₹549/year**

**Optional Upgrades:**
- Professional email: ₹1,680/year (Google Workspace)
- More form submissions: ₹400/month (Formspree Gold)
- Analytics: ₹0 (Google Analytics is free)

---

## Troubleshooting

**Form not working?**
- Did you replace YOUR_FORM_ID in BOTH places? (lines ~30 and ~350)
- Check Formspree dashboard for submissions
- Verify email in Formspree settings
- Check spam folder

**Domain not connecting?**
- Wait 24-48 hours for DNS propagation
- Verify DNS records in Hostinger match Netlify's
- Use whatsmydns.net to check propagation status

**Site not updating?**
- Push changes to GitHub: `git push`
- Netlify auto-deploys in 1-2 minutes
- Clear browser cache (Ctrl+Shift+R)

**Images not showing?**
- Check image paths in HTML
- Ensure images are in `images/` folder
- Verify image names match exactly (case-sensitive)

---

## Support

Need help?
- Email: eventknightc@gmail.com
- WhatsApp: +91 86683 40760
- Netlify docs: docs.netlify.com
- Formspree support: formspree.io/help

---

## Design Notes

**Color Scheme:**
- Primary: Black (#000000)
- Accent: Gold (#FFD700)
- Secondary: Purple/Pink gradients
- Based on your logo and actual event lighting

**Fonts:**
- Headings: Bebas Neue (bold, impactful)
- Body: Poppins (clean, readable)

**Features:**
- Lead capture popup (5 sec or 50% scroll)
- Scroll reveal animations
- Hover effects on cards
- Mobile-first responsive design
- Instagram feed integration

---

Built with ❤️ for Event Knight  
Stage it Right, With Event Knight
