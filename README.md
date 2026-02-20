# Axiom Canine - Dog Training Website

A professional website for Axiom Canine, a dog training business in Jacksonville, FL.

## Features

- Single-page application with client-side routing
- Netlify Forms integration for contact form
- Mobile-responsive design
- Tailwind CSS styling
- Accessibility features

## Deployment to Netlify

### Prerequisites
- A Netlify account (sign up at [netlify.com](https://netlify.com))
- This repository pushed to GitHub

### Deployment Steps

1. **Connect to Netlify**
   - Go to [netlify.com](https://netlify.com) and sign in
   - Click "Add new site" → "Import an existing project"
   - Choose "GitHub" as your Git provider
   - Authorize Netlify to access your GitHub account
   - Select the `pmau45/automatic-fishstick` repository

2. **Configure Build Settings**
   - Netlify will auto-detect the `netlify.toml` configuration file
   - Build command: (leave empty - no build needed)
   - Publish directory: `.` (root directory)
   - Click "Deploy site"

3. **Enable Netlify Forms**
   - Forms are automatically detected and enabled via the `data-netlify="true"` attribute
   - After deployment, go to your site's dashboard → "Forms" to view submissions

4. **Custom Domain (Optional)**
   - In your site dashboard, go to "Domain settings"
   - Click "Add custom domain"
   - Follow the instructions to configure your DNS

## Local Development

Simply open the `Main` file in a web browser. No build process required.

## Form Submissions

Form submissions are handled by Netlify Forms. To view submissions:
1. Go to your Netlify site dashboard
2. Click on "Forms" in the navigation
3. Select the "intake" form to view all submissions

You can also set up email notifications for new submissions in the Netlify dashboard.

## Structure

- `Main` - Main HTML file with all content
- `netlify.toml` - Netlify configuration
- `thank-you.html` - Form submission confirmation page

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript (SPA routing)
- Lucide Icons
- Netlify Forms
