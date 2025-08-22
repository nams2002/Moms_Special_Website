# Mom's Special Kitchen Website

A modern, responsive website for Mom's Special Kitchen featuring a warm, homely design with soft colors and intuitive navigation.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Warm Color Scheme**: Cream, pastel green, pastel pink, and yellow colors
- **Hero Section**: Eye-catching header with call-to-action
- **About Section**: Heartwarming description of the kitchen's philosophy
- **Menu Section**: Beautiful display of menu items with categorized images
- **Contact/Order Section**: Multiple ordering options (Zomato, Swiggy, WhatsApp)
- **Social Media Integration**: Footer with social media links
- **Smooth Animations**: Interactive elements and smooth scrolling

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Poppins)

## Local Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:3000`

## Deployment to Vercel

### Option 1: Using Vercel CLI

1. Install Vercel CLI globally:
   ```bash
   npm install -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy the project:
   ```bash
   vercel
   ```

4. Follow the prompts to configure your deployment

### Option 2: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign up or log in to your account
3. Click "New Project"
4. Import your Git repository or upload the project files
5. Vercel will automatically detect the project type and deploy it

## Customization

### Contact Information
Update the contact details in `index.html`:
- WhatsApp number: Replace `91XXXXXXXXXX` with your actual number
- Phone number: Replace `+91 XXXXXXXXXX` with your actual number
- Email: Replace `info@momsspecial.com` with your actual email

### Social Media Links
Update the social media links in the footer section of `index.html`

### Menu Images
Replace the menu images in the `images` folder with your actual menu images

### Colors
Modify the CSS custom properties in `styles.css` to change the color scheme:
```css
:root {
    --cream: #FFF8E7;
    --pastel-green: #E8F5E8;
    --pastel-pink: #FFE4E6;
    --pastel-yellow: #FFF9C4;
    /* ... other colors */
}
```

## File Structure

```
moms-special-kitchen/
├── images/
│   ├── logo.jpg
│   ├── menu page 1.jpg
│   └── menu page 2.jpg
├── index.html
├── styles.css
├── script.js
├── package.json
├── vercel.json
└── README.md
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

MIT License - feel free to use this template for your own projects!
