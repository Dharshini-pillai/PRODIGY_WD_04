DHARSHINI - Web Developer Portfolio
This project is a clean, modern, single-page portfolio designed to showcase a web developer's skills, experience, and projects. It is built with HTML, CSS, and basic JavaScript to ensure smooth performance and a professional look.

The entire application is self-contained in a single file for easy setup and deployment.

🚀 Getting Started
Prerequisites
A modern web browser (Chrome, Firefox, Safari, Edge, etc.).

Installation and Setup
Save the Code: Copy the entire code block provided (HTML structure, CSS <style> block, and JavaScript <script> block) and save it as a single file named index.html.

Add Photo: The hero section currently uses a placeholder image. To personalize it, replace the src attribute in the <img class="profile-photo"> tag with the path or URL of your professional photo.

Open in Browser: Double-click the saved index.html file to launch the portfolio locally.

🏗️ Project Structure & Content
This portfolio is structured using clear, semantic HTML sections, making it easy to navigate and update.

Section ID	Purpose	Key Content
Header	Sticky Navigation	Logo (DHARSHINI.dev) and navigation links with smooth scroll functionality.
#home	Hero Introduction	Headline, short summary, profile photo placeholder, and a primary Call-to-Action (CTA).
#about	Education & Experience	Detailed developer background using a clean timeline layout.
#skills	Technical Expertise	A grid of Skill Cards detailing frontend and backend technologies.
#projects	Work Showcase	A dark-themed section using a grid layout for project cards, including links to live demos and GitHub repos.
#contact	Contact Form	A simple contact form setup with a basic JavaScript handler (requires backend integration for actual email delivery).
Footer	Social Links	Copyright information and links to professional social platforms (LinkedIn, GitHub).

Export to Sheets
✨ Design & Technology
Styling (<style> Block)
Custom Properties (CSS Variables): Used for managing colors (--primary-color, --dark-bg) for easy theme customization.

Layout: Utilizes Flexbox (for navigation, hero content) and CSS Grid (for the Skills and Projects sections) for a modern, responsive layout.

Aesthetics: Features a dark background for the hero and projects sections (--dark-bg: #1a1a2e;) combined with a strong primary blue (#007bff) for accents.

Responsiveness: The layout is designed to adjust gracefully across different screen sizes.

Interactivity (<script> Block)
The JavaScript is lightweight and focuses on two core user experience enhancements:

Smooth Scrolling: All internal navigation links (#home, #about, etc.) smoothly animate the page to the target section when clicked.

Contact Form Handler: Provides a basic event listener for the form submission, displaying an alert to the user and clearing the form fields. (Note: To actually send emails, this would require integration with a backend service like Formspree, Netlify Forms, or a custom API endpoint).

✍️ Customization
To make this your own, focus on updating these key areas:

Personalize Content: Replace all placeholder text in the timeline, skills descriptions, and project cards with your real information.

Media: Replace the placeholder images in the Hero and Projects sections with your actual photo and project screenshots.

Links: Update all empty href="#" attributes in the navigation, buttons, and social links with your actual professional URLs.
