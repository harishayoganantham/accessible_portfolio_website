# Accessible multi-page portfolio

A starter portfolio with four pages: Home, About, Projects, and Contact.

## Run it
1. Extract the ZIP file.
2. Open `index.html` in a browser, or run a local static server from this folder (for example, `python -m http.server 8000`).
3. Visit `http://localhost:8000`.

## Personalize before submitting
- Replace every instance of `Your Name` with your preferred display name.
- Update the About page with your real background and skills.
- Replace sample project descriptions with your own work and add repository/demo links.
- Add your real contact details if you want them public.
- Update page titles, descriptions, and social metadata to match your content.

## Accessibility features
- Semantic `header`, `nav`, `main`, `section`, `article`, and `footer` landmarks.
- Skip link, descriptive page titles, and current-page navigation state.
- Keyboard-visible focus styles and a responsive navigation button with `aria-expanded` / `aria-controls`.
- Explicit form labels, native required/email validation, and an `aria-live` status message.
- Reduced-motion preference support and responsive layout.

## Important
The contact form is front-end validation only. It does not transmit or save messages. Connect it to a secure backend or reputable form provider before using it in production. This starter aims to support WCAG 2.2 AA practices, but automated/manual accessibility testing is still required; conformance is not guaranteed by the template alone.
