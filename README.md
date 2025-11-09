# AsuStar - Alternative Pinterest

Educational project for the final exam in Web Technologies. Pinterest-like application for viewing, saving, and sharing images.

## About the Project

AsuStar is a web application created to demonstrate skills in HTML, CSS, and JavaScript. The project is an alternative to Pinterest with the ability to view images, create accounts, save favorites, and work with external APIs.

## Key Features

### Authentication
- New user registration (Sign Up)
- Login to the system (Log In)
- User data storage in localStorage
- Personalized profiles with favorites display

### Image Management
- Image gallery viewing
- Image search by categories and keywords
- Filtering by categories (Anime, Art, Sport, Cars, Nature, Tech)
- Upload your own images
- Save to favorites
- Rating system (1-5 stars)

### Interface
- Responsive design for all devices
- Light and dark themes
- Smooth animations and transitions
- Intuitive navigation

### API Integration
- Using Unsplash API for image search
- Dynamic image loading by categories
- Real-time search results display

## Technologies

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla + jQuery)
- **Framework**: Bootstrap 5
- **API**: Unsplash API
- **Data Storage**: LocalStorage
- **Hosting**: GitHub Pages

## Project Structure

```
Alternative-Pinterest-Final/
├── index.html          # Main page with gallery
├── profile.html        # User profile page
├── detail.html         # Image detail page
├── upload.html         # Image upload page
├── about.html          # About us page
├── search.html         # Search page
├── style.css           # Main styles
├── script.js           # JavaScript logic
├── images/             # Local images
└── sound/              # Sound effects
```

## How to Use

### For Users

1. **Registration/Login**
   - Click the "Log-in" button in the top right corner
   - Select the "Sign Up" tab for registration or "Log In" tab to sign in
   - Fill out the form (name, email, password)

2. **Viewing Images**
   - The main page displays an image gallery
   - Use the search bar to search by keywords
   - Click category buttons (Anime, Art, Sport, etc.) to filter

3. **Working with Favorites**
   - Hover over an image and click the "Favorite" button
   - All saved images are available in your profile

4. **Rating Images**
   - Log in to the system
   - Use the stars on the image card to rate (1-5)
   - Your rating is saved and affects the overall rating

5. **Uploading Images**
   - Go to the "Upload" page
   - Fill out the form and upload an image
   - After uploading, the image will appear in the gallery

### For Developers

1. Clone the repository:
```bash
git clone https://github.com/alixx21/Alternative-Pinterest-Final.git
```

2. Open `index.html` in a browser

3. An API key is required to work with Unsplash API (a demo key is used in the project)

## Responsiveness

The project is fully adapted for:
- Desktops (1920px+)
- Tablets (768px - 1024px)
- Mobile devices (up to 768px)

## Dark Theme

Switching between light and dark themes is available through:
- Settings menu → Toggle Dark Mode
- Theme is saved in localStorage and restored on next visit

## Form Validation

All forms include validation:
- Email: format check
- Password: minimum 8 characters
- Phone: optional field with format validation
- Required fields: completion check

## Data Storage

All data is stored in browser localStorage:
- User data
- Favorite images (separately for each user)
- Image ratings
- Theme settings

## Deployment

**Live Site**: [https://Meirzhan1.github.io/Alternative-Pinterest-Final/](https://Meirzhan1.github.io/Alternative-Pinterest-Final/)

**Repository**: [https://github.com/Meirzhan1/Alternative-Pinterest-Final](https://github.com/Meirzhan1/Alternative-Pinterest-Final)

## Team

- **Meirzhan** - Frontend Developer
- **Alikhan** - Designer & UI

## Notes

- Project created for educational purposes
- Data is stored locally in the browser
- For production, it is recommended to use a server-side for data storage
- Unsplash API key in the project is for demonstration purposes

## Design Features

- Modern and clean interface
- Smooth animations and transitions
- Intuitive navigation
- High contrast for readability
- Dark theme support with correct colors

---

Created with ❤️ by team "Creatives" for the final Web Technologies project
