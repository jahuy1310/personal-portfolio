# Gia Huy — Personal Web Portfolio (Extra-B)

A responsive, four-page **static website** built with HTML and CSS only. The visual style follows the first green/cream minimalist portfolio concept, personalized with Gia Huy's information and the supplied wildlife photograph.

## Pages

| File | Content |
|---|---|
| `index.html` | Home: short introduction, tagline, highlights |
| `about.html` | Biography, chosen profile photo, skills, education, goals |
| `projects.html` | Three cards: Personal Portfolio, Student Grade Book, Career Plan; each has a functioning Details link |
| `contact.html` | Email, GitHub and broad location, with icons |

## Folder structure

```text
Gia_Huy_Modern_Portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── styles.css
├── README.md
├── report.pdf
└── assets/
    ├── images/
    │   ├── profile-wildlife.jpg
    │   ├── project-portfolio.svg
    │   ├── project-gradebook.svg
    │   └── project-career.svg
    └── icons/
        └── favicon.svg
```

## How to use and test

1. Extract the ZIP file without changing the folder structure.
2. Open `index.html` in a web browser (Chrome, Edge or Firefox). Internet access is not required.
3. Test Home, About, Projects and Contact in the navigation bar; the active tab should be highlighted.
4. On `projects.html`, click the three **Details** buttons and confirm they scroll to the relevant descriptions.
5. Open Chrome DevTools (F12) → Toggle device toolbar and check desktop (1440px), tablet (768px) and mobile (390px). Confirm the menu, cards and images stay inside the viewport without horizontal scrolling.
6. Check links, image paths, hover/focus states and email/GitHub destinations.

## Design and implementation

- HTML5 semantic structure, one shared external `styles.css`, Flexbox/Grid responsive breakpoints.
- Green/cream palette, clear typography and spacing, same navigation and footer throughout.
- Individual page titles, meta descriptions, and a local SVG favicon.
- No JavaScript, external packages, external images, required internet access or frameworks.
- All three project cards link to relevant **on-page** details. Separate project source archives or code listings are not needed for this assignment.

## Content notes

- The profile photo is the wildlife photograph supplied by the student, not a picture of the student.
- Student Grade Book is a Python command-line app described using the supplied project README. The public portfolio does **not** include raw project ZIP files.
- Career Plan is based on the supplied personal career-plan document. Future dates and postgraduate education are aspirations, not completed qualifications.
- A phone number is intentionally not published on this sample site; email and GitHub provide contact methods.
- Customize any personal details before making the website public.
