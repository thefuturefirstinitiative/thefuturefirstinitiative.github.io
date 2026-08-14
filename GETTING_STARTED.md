# The Future First Initiative Website

## Overview
This is a professional, responsive website for The Future First Initiative, a gun-violence prevention campaign focused on educational facilities.

## Website Structure

### Pages
- **index.html** - Home page with mission overview and call-to-action
- **team.html** - Team page with leadership bios and values
- **get-involved.html** - Get Involved + Events page with opportunities, upcoming events, and contact form

### Assets
- **assets/logo.png** - Your organization logo (replace this with your actual logo)
- **assets/team-photos/** - Folder for team member photos (to be added)

## How to Get Started

### 1. Add Your Logo
1. Replace `assets/logo.png` with your actual logo file
2. The logo will automatically appear in the navigation and throughout the site

### 2. Customize Content
Edit the HTML files to add your content:

**index.html:**
- Update hero section headline and description
- Edit mission section cards
- Modify any text content

**team.html:**
- Add team member names, roles, and bios
- Replace placeholder images with actual team photos by creating a `team-photos` folder in `assets/`

**get-involved.html:**
- Update event dates and details
- Modify volunteer and partnership descriptions
- Add real event information and registration links

### 3. Update Colors
The site uses three main colors defined in `styles.css`:
- Primary (Dark Red): `#6c0202`
- Secondary (Orange): `#ff6600`
- Tertiary (Brownish-Red): `#b5695e`

To change colors, edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6c0202;
    --secondary-color: #ff6600;
    --tertiary-color: #b5695e;
}
```

### 4. Add Team Photos
1. Create a `team-photos` folder in the `assets` directory
2. Replace the placeholder `<div class="member-image placeholder">` with:
```html
<div class="member-image">
    <img src="assets/team-photos/name.jpg" alt="Team Member Name">
</div>
```

### 5. Setup Forms
The contact form and event registration buttons currently show placeholder alerts. To integrate real functionality:
- Replace form submission handling in `script.js`
- Connect to an email service or form backend
- Update event registration links

## Features

✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
✅ **Mobile Navigation** - Hamburger menu for mobile devices
✅ **Smooth Animations** - Hover effects and transitions throughout
✅ **Accessibility** - Semantic HTML and keyboard navigation
✅ **Professional Layout** - Modern grid-based design
✅ **Easy to Customize** - Well-organized code with clear sections

## File Guide

### HTML Files
- Clean semantic structure
- Easy to find and edit content sections
- Comments marking major sections

### CSS (styles.css)
- Organized by section
- CSS variables at the top for easy customization
- Mobile-first responsive design
- Uses flexbox and grid layouts

### JavaScript (script.js)
- Mobile menu functionality
- Active page highlighting
- Form submission handling
- Smooth scroll behavior

## Deployment

To publish your website on GitHub Pages:
1. Push your changes to the main branch
2. Go to GitHub repository Settings
3. Enable GitHub Pages for the main branch
4. Your site will be live at: `https://thefuturefirstinitiative.github.io`

## Tips

- **Colors**: The brand colors are carefully chosen and used throughout. Consider this palette when adding new images or graphics.
- **Images**: All images should be optimized for web (compressed)
- **No AI Images**: As requested, only use real photos and graphics
- **Mobile First**: Always test changes on mobile devices
- **Accessibility**: Use descriptive alt text for all images

## Support

For questions about editing or customizing this site, refer to the HTML comments and CSS section headers. Each major section is clearly labeled.

---

Built with ❤️ for gun violence prevention
