# Habibi Swipe Website

Complete HTML/CSS website matching your app's gold/black theme.

## Files Included

- `index.html` - Home/Landing pag
- `privacy-policy.html` - Privacy Policy (Required for App Store)
- `terms-of-service.html` - Terms of Service
- `support.html` - Help & Support page
- `style.css` - Shared stylesheet with your app's theme

## Design Features

✅ Matches your app's gold/black theme (#B8860B gold, #0A0A0A black)  
✅ Fully responsive (mobile, tablet, desktop)  
✅ Modern, clean design  
✅ Gold gradient overlays (matching app design)  
✅ Professional navigation and footer  
✅ Easy to read legal pages  

## Setup Instructions

### Option 1: Quick Deploy (Recommended)

1. **Upload to your hosting:**
   - Upload all files to your web hosting (habibiswipe.com)
   - Make sure all files are in the root directory or a subdirectory

2. **Test the pages:**
   - Visit: https://habibiswipe.com
   - Visit: https://habibiswipe.com/privacy-policy.html
   - Visit: https://habibiswipe.com/terms-of-service.html
   - Visit: https://habibiswipe.com/support.html

### Option 2: Free Hosting (GitHub Pages, Netlify, Vercel)

1. **GitHub Pages:**
   - Create a new repository
   - Upload all files
   - Enable GitHub Pages in repository settings
   - Your site will be at: `username.github.io/repository-name`

2. **Netlify:**
   - Go to netlify.com
   - Drag and drop the `website` folder
   - Your site will be live instantly
   - Add custom domain (habibiswipe.com) in settings

3. **Vercel:**
   - Go to vercel.com
   - Import your project
   - Deploy instantly

## Customization

### Update Download Buttons

In `index.html`, replace the placeholder download buttons with actual App Store and Google Play badges:

```html
<!-- Replace these with actual badge images -->
<a href="[App Store URL]" class="download-btn app-store">
    <img src="app-store-badge.png" alt="Download on App Store">
</a>
```

Download badges from:
- App Store: https://developer.apple.com/app-store/marketing/
- Google Play: https://play.google.com/intl/en_us/badges/

### Update Links

All internal links use relative paths (`/privacy-policy.html`). If you host in a subdirectory, update paths accordingly.

### Add Your Logo

Replace the text logo with your actual logo image:
```html
<a href="/" class="logo">
    <img src="logo.png" alt="Habibi Swipe">
</a>
```

## App Store Requirements

✅ Privacy Policy page - **REQUIRED**  
✅ Terms of Service page - Recommended  
✅ Contact information - support@habibiswipe.com  
✅ Professional appearance  

## Testing Checklist

Before going live:
- [ ] All pages load correctly
- [ ] All links work
- [ ] Mobile responsive (test on phone)
- [ ] Privacy Policy is publicly accessible
- [ ] Contact email works
- [ ] Download buttons link to correct app stores (when ready)

## Notes

- The website uses your app's exact color scheme
- All legal content is already included
- Mobile-responsive design
- Fast loading (no external dependencies)
- SEO-friendly structure

## Support

If you need help:
- Email: support@habibiswipe.com
- Website: https://habibiswipe.com

---

**Ready for App Store submission!** 🚀

