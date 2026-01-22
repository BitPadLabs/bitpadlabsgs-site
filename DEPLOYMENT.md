# Deployment Guide

## Quick Start

1. **Test Locally**
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
   Visit http://localhost:4000

2. **GitHub Pages Setup**
   - Push to GitHub repository
   - Go to Settings → Pages
   - Set Source to "Deploy from a branch"
   - Select branch: `main` or `master`
   - Set folder: `/ (root)`
   - Save

3. **Custom Domain** (bitpadlabsgs.com)
   - Add CNAME file with `bitpadlabsgs.com`
   - Configure DNS:
     - A records pointing to GitHub Pages IPs:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153
     - CNAME record: www → <username>.github.io

4. **SSL Certificate**
   - GitHub Pages automatically provisions Let's Encrypt SSL
   - Check "Enforce HTTPS" in repository settings

## Pre-Deployment Checklist

- [x] All pages created (Home, Services, Capabilities, Team, News, Contact, About, Terms, Privacy)
- [x] NAICS codes updated
- [x] CAGE Code: 15LW1
- [x] UEI: WXU7TJ5MQJW4
- [ ] DUNS number (currently ##)
- [x] Team photos populated
- [x] Logo assets in place
- [x] SDVOSB badge added
- [x] News posts created
- [ ] Generate proper favicon.ico from frog logo
- [ ] Test all navigation links
- [ ] Test all internal page links
- [ ] Verify mobile responsiveness
- [ ] Test contact email link

## Post-Deployment

1. Submit to Google Search Console
2. Set up Google Analytics (if desired)
3. Monitor GitHub Actions for build status
4. Test all pages on live site
5. Verify SSL certificate

## Updating Content

- News posts: Add to `_posts/` folder with format `YYYY-MM-DD-title.md`
- Team members: Update `_data/team.yml`
- NAICS codes: Update `_data/naics.yml`
- Site config: Update `_config.yml`

## Support

For issues with Jekyll or GitHub Pages:
- https://docs.github.com/en/pages
- https://jekyllrb.com/docs/
