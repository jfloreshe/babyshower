# Baby Shower Landing Page

A simple and elegant static landing page for a baby shower invitation.

## Setup Instructions

### 1. Add Your Video
- Place your video file in the root directory
- Update line 78 in `index.html` with your video filename:
  ```html
  <source src="your-video.mp4" type="video/mp4">
  ```

### 2. Add RSVP Link
- Update line 84 in `index.html` with your confirmation link:
  ```html
  <a href="YOUR_LINK_HERE" class="btn-confirmar">Confirmar Asistencia</a>
  ```
  You can use:
  - Google Forms URL
  - WhatsApp link: `https://wa.me/1234567890?text=Confirmo%20mi%20asistencia`
  - Email: `mailto:your-email@example.com?subject=Confirmación Baby Shower`

### 3. Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push this code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Baby shower landing page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Under "Source", select "main" branch and "/" root folder
5. Click Save
6. Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Features

- ✨ Responsive design (works on mobile and desktop)
- 🎥 Autoplay video on page load
- 💖 Beautiful gradient design
- 📱 Mobile-friendly
- ⚡ Fast loading
- 🎨 Easy to customize

## Customization

You can easily customize colors in the `<style>` section:
- Main gradient: Lines 14-15
- Heading color: Line 41
- Button gradient: Line 67

## Browser Support

The video will autoplay on modern browsers. Note: Most browsers require videos to be muted for autoplay to work.
