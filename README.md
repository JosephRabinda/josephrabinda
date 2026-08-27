# Joseph's Computer Science Student Profile

A modern, responsive portfolio website built with **HTML5, CSS3 and Vanilla JavaScript**.

## Run locally
1. Download and extract the project.
2. Open `index.html` in a browser, or use VS Code with the Live Server extension.
3. Add your images and CV to the folders shown below.

## Main folders
- `assets/images/profile.jpg` — hero profile photo
- `assets/images/about.jpg` — About Me photo
- `assets/images/background.jpg` — hero technology background
- `assets/images/logo.png` — favicon/logo file
- `assets/images/gallery/` — gallery photos
- `assets/documents/cv.pdf` — downloadable CV

## Editing your information
- **Name and title:** edit `index.html`, especially the Hero and About sections.
- **Personal details:** edit the `details-grid` and `personal-list` sections.
- **Skills:** change `data-progress="80"` and the visible percentage text in `index.html`.
- **Projects:** duplicate a `.project-card` and edit its title, description, tags and links.
- **Social links:** replace every `href="#"` with your real profile URL.
- **Colours:** change the CSS variables at the top of `css/style.css`.
- **Background image:** replace `assets/images/background.jpg`.

## Contact form
The project uses FormSubmit. In `index.html`, replace:

`https://formsubmit.co/your-email@example.com`

with your actual FormSubmit email address. On the first submission, FormSubmit will normally send an activation email. Confirm it to activate delivery.

Do not publish sensitive API keys or passwords in the website.

## Gallery
Add your photos as:
- `photo-1.jpg`
- `photo-2.jpg`
- `photo-3.jpg`
- `photo-4.jpg`

inside `assets/images/gallery/`. To add more, duplicate a `.gallery-item` in `index.html`.

## Privacy
Your student number, date of birth and other private details are intentionally not displayed by default. Only add information you are comfortable making public.
