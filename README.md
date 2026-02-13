# SaaS Wise Solutions - Landing Page

## Local Preview

Open `index.html` in your browser:
```bash
open index.html
```

## Deploy to Netlify

### Option 1: Drag & Drop (fastest)
1. Go to https://app.netlify.com
2. Sign up / log in
3. Drag the entire `saaswisesolutions` folder onto the deploy area
4. Your site is live instantly at a Netlify subdomain

### Option 2: Git-based Deploy (recommended for updates)
1. Create a GitHub repository
2. Push this project to it:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/saaswisesolutions.git
   git push -u origin main
   ```
3. In Netlify, click "Add new site" > "Import an existing project"
4. Connect your GitHub repo
5. Deploy settings: publish directory = `/` (leave default)
6. Click "Deploy site"

## Connect Your Domain (saaswisesolutions.com)

1. In Netlify dashboard, go to **Domain management** > **Add a domain**
2. Enter `saaswisesolutions.com`
3. Netlify will give you nameserver addresses (e.g., `dns1.p01.nsone.net`)
4. Go to your domain registrar and update the nameservers to point to Netlify's
5. SSL is automatically provisioned once DNS propagates (usually a few minutes to a few hours)

## Contact Form

The contact form uses **Netlify Forms** (free tier: 100 submissions/month). No backend code needed. Form submissions appear in your Netlify dashboard under **Forms**.

## Customizing Content

- **Text/copy**: Edit directly in `index.html`
- **Colors**: Modify the Tailwind config in the `<script>` tag at the top of `index.html`
- **Styles**: Edit `styles.css` for custom animations and effects
- **Social links**: Update the `href="#"` placeholders in the footer

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Netlify (hosting + forms)
