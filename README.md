# @mendezrein Portfolio Links Page
https://mendezrein.github.io/landing/

This is a personal portfolio links page for **Reinaldo Mendez**, a performance graphic designer. It features social media links, skills visualization, and a rotating dashed ring around the profile picture.

---

## Features

- **Profile Section**
  - Display name, subtitle, and visitor counter.
  - Profile picture with a rotating dashed ring effect.

- **Links Section**
  - Quick access to Behance, Instagram, LinkedIn, and GitHub.
  - Hover effects for interactive feedback.

- **Skills Section**
  - Shows proficiency bars for Photoshop, Illustrator, After Effects, AI Image/Video, Programming, and Excel.
  - Animated progress bars.

- **SEO Ready**
  - Meta tags for description, keywords, and author.

- **Hidden Watermark**
  - ASCII watermark included in HTML comments, visible only in the source/inspector.

---

## Usage

1. Clone or download this repository.
2. Replace `profile.jpg` with your own profile image.
3. Update links in the `.link-container` to your social media profiles.
4. Open `index.html` in any browser.

---

## Customization

- **Profile Ring**
  - Modify `.profile-pic::before` for dash style, color, thickness, and animation speed.

- **Skills**
  - Adjust the `data-value` attribute for each `.skill-fill` to reflect your proficiency.

- **Visitor Counter**
  - Currently generates a random number between 1–3 per minute.
  - Can be replaced with a backend counter if desired.

---

## Technologies

- HTML5
- CSS3 (Flexbox, Animations)
- JavaScript (for skill bar animation and visitor count)
- Google Fonts: Montserrat
- Favicon service for social icons

---

## License

This project is open-source. You may use and modify it for personal or portfolio purposes.
