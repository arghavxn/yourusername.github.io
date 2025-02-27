# Arghavan Noori - Personal Portfolio

## Overview
This is a responsive personal portfolio website built with HTML, CSS, and vanilla JavaScript. The portfolio showcases my skills, projects, education, and experience as a Computer Science student and aspiring Software Developer & Product Manager.


## Features
- Mobile-first responsive design
- Clean and modern user interface
- Interactive navigation
- Project showcase with dynamic cards
- Skills section with icon visualization
- Timeline for work experience
- Contact form integrated with Formspree
- Downloadable resume

## Tech Stack
- HTML5
- CSS3 (Custom styling without frameworks)
- JavaScript (Vanilla)
- GitHub Pages (Hosting)
- Formspree (Contact form handling)

## Project Structure
```
portfolio/
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── Resume.pdf          # Downloadable resume
├── assets/             # All static assets
│   ├── css/
│   ├── js/
│   └── images/         # Project and profile images
└── thank-you.html      # Form submission confirmation page
```

## Setup and Local Development
1. Clone the repository:
   ```
   git clone https://github.com/arghavxn/arghavxn.github.io.git
   ```
2. Navigate to the project folder:
   ```
   cd arghavxn.github.io
   ```
3. Open `index.html` in your browser to view the website locally.

## Deployment
This portfolio is deployed using GitHub Pages. To deploy your own version:

1. Create a repository named `yourusername.github.io`
2. Push your code to the repository
3. GitHub will automatically deploy your site to `https://yourusername.github.io`

## Customization Guide
To customize this portfolio for your own use:

### Basic Information
1. Update personal information in `index.html`:
   - Name, title, and about section
   - Social links (GitHub, LinkedIn)
   - Contact information

### Projects
Add new projects by duplicating the project-card structure:
```html
<div class="project-card">
    <div class="project-image">
        <img src="path/to/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <div class="tags">
            <span class="tag">Technology</span>
        </div>
        <p>Project description goes here...</p>
        <ul class="project-card-highlights">
            <li>Key achievement or feature</li>
        </ul>
        <a href="https://github.com/yourusername/project" class="btn">GitHub</a>
    </div>
</div>
```

### Styling
The portfolio uses CSS variables for easy color customization:
```css
:root {
    --primary-color: #FFFFFF;
    --secondary-color: #000000;
    --accent-color: #FFB6C1;
    --text-color: #333333;
    --bg-color: #FFFFFF;
}
```
Update these values in the CSS to change the color scheme.

### Contact Form
The contact form uses Formspree. To configure it for your email:
1. Create an account at [Formspree](https://formspree.io/)
2. Create a new form and get your form ID
3. Replace the form action URL in the HTML:
   ```html
   <form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
   ```

## License
This project is available under the MIT License. Feel free to use it for your own portfolio with attribution.

## Credits
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Roboto Font
- [Formspree](https://formspree.io/) - Form Processing
- [DevIcons](https://github.com/devicons/devicon/) - Technology Icons

## Contact
If you have any questions or suggestions about this portfolio, feel free to contact me at:
- Email: your-email@example.com
- LinkedIn: [Arghavan Noori](https://www.linkedin.com/in/arghavan-noori/)
- GitHub: [arghavxn](https://github.com/arghavxn)
