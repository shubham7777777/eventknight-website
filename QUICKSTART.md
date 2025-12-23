# QUICK START - Deploy in 30 Minutes

## IMMEDIATE TASKS (Do this NOW)

### 1. Setup Formspree (5 mins)
□ Go to formspree.io
□ Sign up (free)
□ Create new form
□ Name it "Event Knight Contact"
□ Copy the form endpoint
□ Edit index.html line 343, replace YOUR_FORM_ID with your ID
□ Save file

### 2. Create GitHub Repo (5 mins)
□ Go to github.com
□ Click "New repository"
□ Name: eventknight-website
□ Make it Public
□ Don't add README (we have one)
□ Copy the git commands shown

### 3. Push to GitHub (2 mins)
Open terminal in this folder and run:
```bash
git init
git add .
git commit -m "Event Knight website launch"
git remote add origin https://github.com/YOUR_USERNAME/eventknight-website.git
git branch -M main
git push -u origin main
```

### 4. Deploy to Netlify (10 mins)
□ Go to netlify.com
□ Sign in with GitHub
□ Click "Add new site" → "Import an existing project"
□ Choose GitHub → Select eventknight-website repo
□ Click "Deploy site" (leave all settings default)
□ Wait 2 minutes for deployment
□ Your site is live at: random-name-123.netlify.app

### 5. Connect Domain (5 mins)
□ In Netlify: Site settings → Domain management
□ Click "Add custom domain"
□ Enter: eventknight.in
□ Netlify will show DNS records

**Go to Hostinger DNS settings and add:**
- A record: @ → 75.2.60.5
- CNAME: www → your-site-name.netlify.app

□ Save changes
□ Wait 24-48 hours for DNS to propagate
□ HTTPS will auto-enable once DNS is configured

### 6. Update Instagram (2 mins)
□ Go to Instagram profile settings
□ Update bio link to: eventknight.in
□ Post story announcing website launch

---

## LATER TASKS (This week)

### Content Updates
□ Add 6-9 real event photos to Portfolio section
□ Get 2-3 testimonials from past clients
□ Update About section with team info (if needed)

### SEO Setup
□ Create Google Search Console account
□ Submit sitemap (eventknight.in/sitemap.xml - create later)
□ Create Google Business Profile
□ List business on Google Maps

### Analytics
□ Setup Google Analytics
□ Add tracking code to website
□ Monitor first week traffic

### Professional Email (optional, costs ₹140/month)
□ Get Google Workspace
□ Setup contact@eventknight.in
□ Forward to Gmail for now

---

## TROUBLESHOOTING

**Form not working?**
- Check Formspree endpoint is correct in index.html
- Verify email in Formspree settings

**Domain not connecting?**
- Wait 24-48 hours for DNS propagation
- Check DNS records in Hostinger match Netlify's requirements
- Use whatsmydns.net to check propagation

**Site not updating?**
- Push changes to GitHub
- Netlify auto-deploys in 1-2 minutes
- Clear browser cache

**Need help?**
- Netlify docs: docs.netlify.com
- Formspree support: formspree.io/help
- DNS issues: Check Hostinger support

---

## SUCCESS CHECKLIST

After completing all immediate tasks, you should have:
✓ Website live on Netlify subdomain
✓ Contact form working
✓ Domain pointing to site (takes 24-48 hours)
✓ HTTPS enabled
✓ Instagram bio updated

**Time to first client inquiry: Usually within first week!**

---

## PRICING REMINDER

Current costs:
- Domain: ₹549/year ✓ PAID
- Everything else: FREE

You're spending ₹1.50/day to have a professional website. That's less than a cup of tea.

First client project will pay for 10+ years of this domain.
