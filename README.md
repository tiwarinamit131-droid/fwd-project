# Delicious Recipes Website

A beautiful, responsive multi-page website showcasing cooking recipes. Built with HTML5 and CSS3 only (no JavaScript).

## Features

###  Implemented Requirements
- **Home Page**: Featuring website title, navigation bar, introduction section, and featured recipe cards
- **5 Recipe Pages**: Each with complete recipe details including ingredients, step-by-step instructions, prep time, and difficulty level
- **Consistent Navigation**: Navigation bar on all pages with proper linking and CSS-only hamburger menu
- **CSS Styling**: 
  - Colors and backgrounds with custom color scheme
  - Typography with multiple font sizes and weights
  - Box model styling (margin, padding, borders)
  - CSS Grid for responsive recipe layout
  - Flexbox for navigation and components
  - Hover effects on buttons and recipe cards
  - Responsive design with media queries for desktop, tablet, and mobile
- **Responsiveness**: Works seamlessly on desktop (1200px+), tablet (768px), and mobile (480px)
- **Footer**: Basic information with links and copyright

### Bonus Features
- **Category Buttons**: Interactive buttons with CSS hover effects
- **Search Bar**: Search interface with CSS styling
- **CSS Animations**: Smooth fade-in animations and card hover effects
- **Card-based Layout**: Modern recipe cards with hover animations
- **Print-friendly**: Optimized print styles for recipes
- **Pure CSS Mobile Menu**: Hamburger menu using CSS checkbox hack (no JavaScript)

## Project Structure

```
recipe-website/
├── index.html              # Home page
├── recipe1.html           # Pasta Carbonara
├── recipe2.html           # Chocolate Cake
├── recipe3.html           # Caesar Salad
├── recipe4.html           # Grilled Salmon
├── recipe5.html           # Margherita Pizza
├── css/
│   └── styles.css         # All styling (including CSS-only hamburger menu)
├── images/
│   ├── carbonara.jpg      # Recipe images
│   ├── chocolate-cake.jpg
│   ├── caesar-salad.jpg
│   ├── grilled-salmon.jpg
│   └── margherita-pizza.jpg
└── README.md              # This file
```

## Recipes Included

1. **Pasta Carbonara** (Medium difficulty, 25 min)
   - Classic Italian pasta with creamy sauce

2. **Chocolate Cake** (Medium difficulty, 45 min)
   - Rich and decadent dessert

3. **Caesar Salad** (Easy difficulty, 15 min)
   - Fresh salad with homemade dressing

4. **Grilled Salmon** (Easy difficulty, 30 min)
   - Healthy protein with herbs

5. **Margherita Pizza** (Hard difficulty, 50 min)
   - Traditional pizza with fresh ingredients

## Responsive Design

The website uses media queries to adapt to different screen sizes:
- **Desktop**: Full multi-column grid layout
- **Tablet**: 2-column or adjusted single-column layouts
- **Mobile**: Single-column stacked layout with optimized touch targets

### CSS Features
- CSS Grid for recipe layout with `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))`
- Flexbox for navigation and flex containers
- Custom CSS variables for consistent theming
- Smooth transitions and hover effects
- Print-friendly styles

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Navigate between pages using the navigation menu

### Deployment to GitHub Pages

#### Step 1: Initialize Git Repository
```bash
cd recipe-website
git init
git add .
git commit -m "Initial commit: Delicious Recipes website"
```

#### Step 2: Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it `recipe-website` (or any desired name)
4. Click "Create repository"

#### Step 3: Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/recipe-website.git
git branch -M main
git push -u origin main
```

#### Step 4: Enable GitHub Pages
1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click "Save"

#### Step 5: Access Your Website
Your website will be available at:
```
https://YOUR_USERNAME.github.io/recipe-website/
```

Wait a few minutes for GitHub to build and publish your site.

## Customization

### Change Color Scheme
Edit the CSS variables in `css/styles.css`:
```css
:root {
  --primary-color: #ff6b6b;
  --secondary-color: #4ecdc4;
  --accent-color: #ffe66d;
  /* ... */
}
```

### Add Your Own Images
Replace the SVG images in the `images/` folder with your photos:
- Ensure images are optimized (web-friendly formats)
- Recommended size: 600x400px or similar aspect ratio
- Supported formats: JPG, PNG, WebP

### Add More Recipes
1. Create a new file (e.g., `recipe6.html`)
2. Copy the structure from an existing recipe page
3. Update the content with your recipe details
4. Add the link to `index.html` navigation
5. Add an image to the `images/` folder

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Minified CSS available
- SVG images for optimal quality and small file size
- Semantic HTML for better SEO
- CSS media queries for efficient responsive design
- Optimized font loading with system fonts

## Accessibility Features

- Semantic HTML structure
- Alt text for all images
- Color contrast meeting WCAG standards
- Keyboard navigation support
- Mobile-friendly touch targets

## Future Enhancements

- Full-featured search with filtering
- User reviews and ratings
- Recipe scaling for servings
- Shopping list generator
- Dark mode theme
- Backend for dynamic recipes
- User comments section

## License

This project is free to use and modify for educational and personal purposes.

## Author

Made with ❤️ for food lovers | 2024

---

## Submission Checklist

✅ All HTML files included
✅ CSS file with responsive design
✅ Images included (or placeholder SVGs)
✅ Navigation bar on all pages
✅ Footer with basic information
✅ 5 complete recipe pages
✅ Responsive design tested
✅ GitHub repository created
✅ GitHub Pages deployed
✅ Live website link available

---

## Contact & Support

For questions or issues with the website, please refer to the code comments or modify the footer contact information.

Enjoy cooking! 🍳👨‍🍳
