# ✅ Launch Checklist - Djurförsäkringen

## PHASE 1: Domain Setup (DO NOW!)

### [ ] Step 1: Buy djurspar.se
- Go to: loopia.se or one.com
- Search: djurspar.se
- Purchase: 99 kr/year
- **Status:** ⏳ Waiting...

### [ ] Step 2: Verify You Own djurforsakringen.se
- Login to your registrar
- Confirm domain is active
- **Status:** ✅ You said you have this!

---

## PHASE 2: Deploy Website (30 minutes)

### [ ] Option A: Netlify (Recommended)
1. Go to: https://netlify.com
2. Sign up (free)
3. Click "Add new site" → "Deploy manually"
4. Drag folder: `/Users/jauza/DjurforsakringJamfor`
5. Site goes live instantly!

### [ ] Option B: Vercel
1. Go to: https://vercel.com
2. Similar process to Netlify

### [ ] Option C: GitHub Pages
1. Create GitHub account
2. Upload code
3. Enable Pages

**Choose ONE and complete it!**

---

## PHASE 3: Connect Domains (1 hour)

### [ ] Step 1: Connect djurforsakringen.se (Primary)
- In Netlify: Domain settings → Add custom domain
- Enter: djurforsakringen.se
- Get DNS records from Netlify
- Update at Loopia:
  ```
  A record: @ → 75.2.60.5
  CNAME: www → your-site.netlify.app
  ```
- Wait 1-24 hours for propagation

### [ ] Step 2: Setup djurspar.se Redirect
- In Loopia for djurspar.se
- URL Forwarding:
  - From: djurspar.se
  - To: https://djurforsakringen.se
  - Type: 301 Permanent

### [ ] Step 3: Test Both Domains
- [ ] Visit djurforsakringen.se
- [ ] Visit djurspar.se (should redirect)
- [ ] Visit www.djurforsakringen.se
- [ ] Check HTTPS works

---

## PHASE 4: Add Analytics (15 minutes)

### [ ] Step 1: Google Analytics
1. Go to: analytics.google.com
2. Create account
3. Get tracking code
4. Add to all HTML pages in `<head>`

### [ ] Step 2: Google Search Console
1. Go to: search.google.com/search-console
2. Add property: djurforsakringen.se
3. Verify ownership
4. Submit sitemap

---

## PHASE 5: Apply for Affiliate Programs (1 hour)

### [ ] Adtraction.com
- Swedish aggregator
- Has: Agria, If, Folksam
- Commission: 200-800 kr/signup
- **Status:** _____________

### [ ] TradeDoubler
- Major Swedish network
- Multiple insurance partners
- **Status:** _____________

### [ ] Direct Programs
- [ ] Agria.se affiliate program
- [ ] If.se partner program
- [ ] Folksam.se affiliate

---

## PHASE 6: Replace Placeholder Links (30 minutes)

Once you get affiliate links:

1. Open `/Users/jauza/DjurforsakringJamfor/compare.html`
2. Find line ~725: `const affiliateLinks = {`
3. Replace placeholder URLs with real tracking links
4. Example:
   ```javascript
   'Agria Djurförsäkring': 'https://track.adtraction.com/t/t?a=YOUR_ID&as=...'
   ```
5. Redeploy to Netlify (just drag and drop again!)

---

## PHASE 7: Marketing Launch (Week 1)

### [ ] SEO Foundation
- [ ] Add sitemap.xml
- [ ] Create robots.txt
- [ ] Add meta descriptions to all pages
- [ ] Submit to Google

### [ ] Content Creation
- [ ] Write 3 blog posts about pet insurance
- [ ] Create breed-specific pages
- [ ] Add customer testimonials (if you have any)

### [ ] Paid Advertising
- [ ] Set up Google Ads account
- [ ] Create 3-5 ad campaigns
- [ ] Budget: 500 kr/day to start
- [ ] Target keywords: "jämför djurförsäkring"

### [ ] Social Media
- [ ] Create Instagram: @djurspar
- [ ] Create Facebook page
- [ ] Post 2-3 times per week
- [ ] Share savings tips

---

## PHASE 8: Monitor & Optimize (Ongoing)

### Daily:
- [ ] Check Google Analytics
- [ ] Monitor conversions
- [ ] Respond to emails

### Weekly:
- [ ] Review ad performance
- [ ] Adjust budgets
- [ ] Create new content
- [ ] Check rankings

### Monthly:
- [ ] Calculate ROI
- [ ] Optimize conversion rate
- [ ] Expand content
- [ ] Test new marketing channels

---

## 💰 Revenue Tracking

### Month 1:
- Signups: _____
- Revenue: _____ kr
- Ad Spend: _____ kr
- Profit: _____ kr

### Month 2:
- Signups: _____
- Revenue: _____ kr
- Ad Spend: _____ kr
- Profit: _____ kr

### Month 3:
- Signups: _____
- Revenue: _____ kr
- Ad Spend: _____ kr
- Profit: _____ kr

---

## 🎯 Success Milestones

- [ ] First website visitor
- [ ] First comparison completed
- [ ] First insurance signup (commission!)
- [ ] 100 visitors/day
- [ ] 1,000 visitors/month
- [ ] 10,000 kr revenue/month
- [ ] 100,000 kr revenue/month
- [ ] Profitable business! 🎉

---

## 📞 Need Help?

If you get stuck on any step, just ask me and I'll help you through it!

**You've got this! 🚀**

---

**Current Status:** Ready to deploy! ✅
**Next Action:** Buy djurspar.se and deploy to Netlify
**Estimated Time to Launch:** 2-3 hours
