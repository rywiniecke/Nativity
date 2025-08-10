# Image Organization Guide

This folder contains all images used in the Pflugerville Nativity Display website.

## Folder Structure

### `/nativity-displays/`
- Individual nativity scene photos
- Different cultural and artistic nativity sets
- Close-up shots of unique pieces
- **Naming convention:** `nativity-[description]-[year].jpg`
- **Example:** `nativity-italian-ceramic-2024.jpg`

### `/events/`
- General event photos showing crowds, venue setup
- Overall event atmosphere shots
- Venue exterior and interior photos
- **Naming convention:** `event-[location/description]-[year].jpg`
- **Example:** `event-main-hall-2024.jpg`

### `/volunteers/`
- Photos of volunteers in action
- Setup and teardown activities
- Community involvement shots
- **Naming convention:** `volunteer-[activity]-[year].jpg`
- **Example:** `volunteer-setup-decorating-2024.jpg`

### `/music/`
- Musical performance photos
- Performers and instruments
- Audience enjoying performances
- **Naming convention:** `music-[performer/type]-[year].jpg`
- **Example:** `music-choir-performance-2024.jpg`

### `/crafts/`
- Children's craft activities
- Completed craft projects
- Craft stations and supplies
- **Naming convention:** `craft-[activity]-[year].jpg`
- **Example:** `craft-children-nativity-scene-2024.jpg`

### `/refreshments/`
- Food and cookie displays
- Refreshment tables
- People enjoying treats
- **Naming convention:** `refreshment-[type]-[year].jpg`
- **Example:** `refreshment-cookie-table-2024.jpg`

### `/hero-carousel/`
- High-quality images for the homepage carousel
- Featured shots that represent the event well
- **Requirements:** High resolution (1920x1080 or larger)
- **Naming convention:** `hero-[number]-[description].jpg`
- **Example:** `hero-01-nativity-scene.jpg`

### `/gallery/`
- Curated photos for the main gallery section
- Best representative images of the event
- **Requirements:** Consistent quality and composition
- **Naming convention:** `gallery-[number]-[description].jpg`
- **Example:** `gallery-01-beautiful-nativity.jpg`

### `/backgrounds/`
- Background images for headers and sections
- Textured or pattern images
- **Naming convention:** `bg-[purpose]-[description].jpg`
- **Example:** `bg-page-header-christmas.jpg`

## Image Guidelines

### File Formats
- **Primary:** `.jpg` for photos
- **Secondary:** `.png` for images with transparency
- **Web optimization:** Consider WebP format for better compression

### Size Recommendations
- **Hero carousel:** 1920x1080px or larger
- **Gallery images:** 800x600px minimum
- **Card images:** 500x400px minimum
- **Thumbnails:** 300x200px

### Quality Standards
- High resolution for hero and featured images
- Good lighting and clear subjects
- Consistent color grading when possible
- Avoid blurry or poorly lit photos

### File Naming Best Practices
- Use lowercase letters and hyphens
- Include year for easy organization
- Be descriptive but concise
- Avoid spaces and special characters

## Usage Notes

When adding images to HTML files, use relative paths:
```html
<img src="images/nativity-displays/nativity-italian-ceramic-2024.jpg" alt="Italian ceramic nativity">
```

For responsive images, consider multiple sizes:
```html
<img src="images/gallery/gallery-01-beautiful-nativity.jpg" 
     srcset="images/gallery/gallery-01-beautiful-nativity-800w.jpg 800w,
             images/gallery/gallery-01-beautiful-nativity-500w.jpg 500w"
     alt="Beautiful nativity display">
```

## Backup and Version Control
- Keep original high-resolution copies
- Consider using Git LFS for large image files
- Maintain a backup of all original photos
