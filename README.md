# ELD Certifications Website

Professional website for ELD Certifications - Independent Regulatory Compliance & Certification Support.

## Files Structure

```
eld-certifications-website/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # JavaScript functionality
├── images/
│   ├── hero-truck.svg          # Hero section illustration
│   ├── compliance-illustration.svg  # Why section illustration
│   └── favicon.svg             # Browser favicon
└── README.md           # This file
```

## Deploying to GoDaddy

### Option 1: File Manager (Easiest)

1. Log in to your GoDaddy account
2. Go to **My Products** → Find your hosting plan → Click **Manage**
3. In cPanel, click **File Manager**
4. Navigate to `public_html` folder
5. Upload all files from this folder:
   - `index.html` goes directly in `public_html`
   - Create `css` folder and upload `styles.css`
   - Create `js` folder and upload `main.js`
   - Create `images` folder and upload all SVG files

### Option 2: FTP Upload

1. Get your FTP credentials from GoDaddy (Hosting → Manage → FTP)
2. Use an FTP client like FileZilla
3. Connect and upload all files to `public_html`

## Contact Form

The contact form uses a mailto: link to open the user's email client. For a more robust solution, you could:

1. Use a form service like Formspree (free tier available)
2. Set up a PHP mail handler (if your hosting supports PHP)
3. Use GoDaddy's built-in form tools

## Customization

### Colors (in css/styles.css)
- Primary Navy: `#003366`
- Accent Red: `#c41230`
- Modify the CSS variables at the top of the file

### Pricing
- Update prices in the pricing section of `index.html`

### Contact Email
- Change `info@eldcertifications.com` in:
  - `index.html` (multiple locations)
  - `js/main.js` (form handler)

## Browser Support

- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile responsive design included
