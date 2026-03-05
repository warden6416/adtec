# Adtec Digital Website - Migration from Wix

## File Structure
- index.html - Homepage (Sales + Support sections)
- documents-downloads.html - Documents and Downloads
- 4k-hevc-encode-decode-carriers.html - 4K HEVC product page
- afiniti-modular-frames.html - afiniti Frames page
- multiplexer-transport-carriers.html - Mux/Transport page
- secure-ip-transmission.html - Secure IP page
- afiniti-legacy-comparison.html - Legacy comparison
- distribution-partners.html - Partners
- support-request.html - Support form
- support-policy.html - Support policy
- sla-warranty-information.html - SLA/Warranty
- repair-services.html - Repair services
- terms.html - Terms and Conditions
- css/style.css - Stylesheet
- js/main.js - Navigation JS
- images/ - YOUR IMAGES GO HERE
- documents/ - YOUR PDFs/FIRMWARE GO HERE

## TO COMPLETE THE MIGRATION

### Step 1: Images
Download from Wix Media Manager into images/ folder:
- adteclogowhite.png (logo)
- AFN-1000.png, AFN-250.png, frames.png
- VEC/VDC carrier images
- SecureGateway.png, gateway images
- Mux product images
- afnlogo.png, digital.png
Then update each HTML file: replace placeholder divs with img tags.

### Step 2: Documents
Download ALL docs from Wix into documents/ folder.
Use filenames matching the href values in documents-downloads.html.

### Step 3: Logo
Replace logo-placeholder divs with img tags in each page.

### Step 4: Forms
Connect forms to a service (Formspree, Netlify Forms, etc.)

### Step 5: Deploy
Upload to Netlify, Vercel, or any web host.
Point adtecdigital.com DNS to new host.
