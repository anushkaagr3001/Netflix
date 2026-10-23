# Netflix Landing Page Clone

A front-end recreation of the Netflix India landing page built with **HTML and CSS**. The project focuses on recreating the familiar dark theme, hero section, feature highlights, FAQ accordion, email sign-up areas, and footer layout.

> **Note:** This is a learning/portfolio project inspired by Netflix's public landing page. It is not affiliated with or endorsed by Netflix. It does not implement real authentication, subscriptions, or video streaming.

## Features

- **Hero section:** Background image with a dark overlay, Netflix logo, language button, sign-in button, headline, and email sign-up form.
- **Feature sections:** Four alternating text-and-image sections describing TV viewing, offline downloads, watching across devices, and kids' profiles.
- **FAQ accordion:** Expandable FAQ items implemented with HTML radio inputs and CSS selectors, without JavaScript.
- **Email sign-up UI:** Email input and “Get Started” button shown in the hero and FAQ sections.
- **Footer navigation:** Multiple columns of informational links and a language selector.
- **Dark visual theme:** Black background, white text, grey FAQ panels, and red call-to-action buttons.
- **Image assets:** Local PNG assets are used for the logo, hero background, feature illustrations, and language dropdown icon.

## Tech Stack

- **HTML5** for page structure and form elements.
- **CSS3** for layout, styling, flexbox, background overlays, and FAQ accordion interactions.
- **PNG assets** for the visual elements.

No JavaScript framework, backend, database, or build tool is required.

## Project Structure

```text
netflix-main/
├── index.html          # Main landing page markup
├── netflix.css         # Page styles and layout
├── logo.png            # Netflix logo image
├── header-image.png    # Hero background image
├── feature-1.png       # TV feature illustration
├── feature-2.png       # Download feature illustration
├── feature-3.png       # Multi-device feature illustration
├── feature-4.png       # Kids profile feature illustration
├── down-icon.png       # Language dropdown icon
└── w.png               # Additional image asset
```

## Run Locally

This is a static website, so you do not need to install packages.

### Option 1: Open the HTML file

1. Download or clone this repository.
2. Keep `index.html`, `netflix.css`, and the image assets in the same directory.
3. Open `index.html` in a browser.

### Option 2: Use VS Code Live Server

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

The page should open in your browser using a local development address.

## How It Works

### Page layout

The page is organized into four main areas:

1. **Header / hero:** A full-viewport background image is darkened with a CSS linear gradient. Navigation and the central call-to-action are positioned over it.
2. **Feature rows:** Each row uses Flexbox to place explanatory text beside an image. The order alternates between rows.
3. **FAQ:** Each question is a label associated with a hidden radio input. When selected, a CSS selector expands the matching answer panel and rotates the plus symbol.
4. **Footer:** Informational links are arranged in columns, followed by a language button and a country label.

### Styling techniques used

- CSS reset using the universal selector
- Flexbox for navigation, feature rows, sign-up forms, and footer columns
- `linear-gradient()` overlay on the hero background
- `background-size: cover` and `background-position: center`
- CSS transitions for FAQ expansion and icon rotation
- Relative asset paths for images

## Current Limitations

This repository contains a **static UI only**. The following elements are visual demonstrations and are not connected to a real service:

- The **Sign in** button does not authenticate a user.
- The email form does not create an account or submit data to a backend.
- The language buttons do not change the page language.
- Footer links use placeholder `#` destinations.
- FAQ answers currently contain placeholder text.
- There is no movie catalogue, streaming player, payment system, or subscription management.
- No responsive behavior should be assumed beyond the styles actually defined in `netflix.css`.

## Ideas for Improvement

- Add media queries for smaller screens and improve mobile spacing.
- Replace placeholder FAQ answers with original, accurate copy.
- Add accessible labels and clearer keyboard focus states to interactive controls.
- Connect the email form to a backend only if a real sign-up flow is intended.
- Replace placeholder footer links with appropriate destinations.
- Add JavaScript or a component framework only if the project grows beyond a static page.
- Add a screenshot of the page to the repository README.

## Learning Outcomes

This project is useful for practicing:

- Semantic HTML structure
- CSS layout and Flexbox
- Background images and overlays
- Form styling
- CSS-only accordion interactions
- Organizing static assets in a front-end project

## Author

**Anushka Agrawal**  
B.Tech Information Technology student, Noida Institute of Engineering & Technology (2024–2028).

Update this section if the repository belongs to a different author.

## Disclaimer

Netflix is a trademark of its respective owner. This project is created for educational and portfolio purposes only. It is not an official Netflix product and does not provide Netflix content or services.

## License

No license file was present in the supplied project. Add a `LICENSE` file if you intend to specify terms for reuse or distribution.
