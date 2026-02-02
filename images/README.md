# Portfolio Images Folder

## Folder Structure

```
images/
├── projects/          # Project thumbnail images
├── profile/           # Your profile/headshot photos
└── assets/            # Other design assets (icons, logos, etc.)
```

## Image Guidelines

### Project Thumbnails (`images/projects/`)
- **Recommended size**: 1200x750px (16:10 aspect ratio)
- **Format**: JPG or PNG
- **File naming**: Use descriptive names like:
  - `inventory-management.jpg`
  - `ecommerce-website.jpg`
  - `mobile-app-design.png`
  - `corporate-website.jpg`

### Profile Photos (`images/profile/`)
- **Recommended size**: 800x800px (square)
- **Format**: JPG or PNG
- **File naming**: 
  - `profile.jpg` - Main profile photo
  - `about-photo.jpg` - Photo for about section

### Assets (`images/assets/`)
- Icons, logos, and other design elements
- Any additional graphics you want to use

## How to Use

1. **Add your images** to the appropriate folders
2. **Update the HTML** to reference your images:
   ```html
   <img src="images/projects/your-project.jpg" alt="Project Name">
   ```

## Current Setup

The portfolio currently uses:
- **Gradient placeholders** for project thumbnails (colorful backgrounds with emoji icons)
- **CSS-based profile circle** in the hero section

You can replace these with your actual images by updating the HTML file.
