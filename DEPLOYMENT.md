# 🚀 Deployment Guide - Djurförsäkringen

## Your Domains Strategy

**Primary Domain:** djurforsakringen.se (SEO powerhouse)
**Marketing Domain:** djurspar.se (redirect to primary)

---

## Option 1: Deploy to Netlify (RECOMMENDED) ⭐

### Step 1: Sign up for Netlify
1. Go to: https://netlify.com
2. Click "Sign up" (use GitHub or Email)
3. Free plan is perfect!

### Step 2: Deploy Your Site
1. Click "Add new site" → "Deploy manually"
2. Drag and drop your entire `/DjurforsakringJamfor` folder
3. Wait 30 seconds - site is live!
4. You'll get URL like: `djurforsakringen.netlify.app`

### Step 3: Connect Your Domain (djurforsakringen.se)
1. In Netlify, click "Domain settings"
2. Click "Add custom domain"
3. Enter: `djurforsakringen.se`
4. Netlify will give you DNS settings

### Step 4: Update DNS at Loopia
1. Log in to Loopia.se
2. Go to your domain: djurforsakringen.se
3. DNS settings → Add these records:

```
Type: A
Name: @
Value: 75.2.60.5

Type: CNAME  
Name: www
Value: your-site.netlify.app
```

4. Save and wait 1-24 hours for DNS propagation

### Step 5: Setup djurspar.se Redirect
1. In Loopia, go to djurspar.se DNS settings
2. Add URL forwarding:
   - From: djurspar.se
   - To: https://djurforsakringen.se
   - Type: 301 Permanent Redirect

**Done! ✅**

---

## Option 2: Deploy to GitHub Pages (FREE)

### Step 1: Create GitHub Account
1. Go to: https://github.com
2. Sign up (free)

### Step 2: Create Repository
```bash
cd /Users/jauza/DjurforsakringJamfor

# Initialize git
git init
git add .
git commit -m "Initial commit - Djurförsäkringen comparison site"

# Create repo on GitHub (do this on github.com)
# Then connect:
git remote add origin https://github.com/YOUR-USERNAME/djurforsakringen.git
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to repo settings
2. Pages → Source: "main branch"
3. Site will be at: `YOUR-USERNAME.github.io/djurforsakringen`

### Step 4: Connect Custom Domain
1. In repo settings → Pages
2. Custom domain: `djurforsakringen.se`
3. Create file `CNAME` with content: `djurforsakringen.se`
4. In Loopia DNS:
```
Type: A
@ → 185.199.108.153
@ → 185.199.109.153
@ → 185.199.110.153
@ → 185.199.111.153

Type: CNAME
www → YOUR-USERNAME.github.io
```

---

## Option 3: Deploy to Vercel (EASY)

1. Go to: https://vercel.com
2. Sign up (free)
3. Import your folder
4. Connect domain in settings
5. Done!

---

## Testing Your Site

### Before Going Live:
- ✅ Test all pages work
- ✅ Test form submission
- ✅ Test on mobile
- ✅ Check all links
- ✅ Verify comparison tool works

### After Going Live:
- ✅ Test djurforsakringen.se loads
- ✅ Test djurspar.se redirects correctly
- ✅ Test www.djurforsakringen.se works
- ✅ Check SSL certificate (https)

---

## Next Steps After Deployment

1. **Add Google Analytics**
   - Get tracking code from analytics.google.com
   - Add to all pages

2. **Submit to Google**
   - Google Search Console
   - Submit sitemap

3. **Apply for Affiliate Programs**
   - Adtraction.com
   - TradeDoubler
   - Direct to insurance companies

4. **Start Marketing**
   - Google Ads
   - SEO content
   - Social media

---

## Need Help?

If you get stuck, come back and I'll help you troubleshoot!

**Estimated deployment time: 30 minutes**
**Cost: 0 kr (all free hosting!)**
