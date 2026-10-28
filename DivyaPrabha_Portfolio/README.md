# Divya Prabha — Portfolio Website

A responsive, static portfolio website built with HTML, CSS, and vanilla JavaScript. It is based on the uploaded résumé and includes a local copy of the PDF for the résumé download link.

## Files

- `index.html` — portfolio content and page structure
- `styles.css` — responsive layout and visual design
- `script.js` — mobile navigation and dynamic footer year
- `assets/Divya_Prabha_Resume.pdf` — résumé download

## Run locally

Open `index.html` in a modern browser. No build step, package installation, or backend is required. For local development, VS Code's Live Server extension is also suitable.

## Publish online

Upload the complete folder to a GitHub repository and enable GitHub Pages, or drag the folder into a static hosting service such as Netlify. Keep the `assets` folder next to `index.html` so the résumé download works.

## Before publishing

- Confirm that the phone number, email, and LinkedIn URL are correct and that you want them public.
- Add GitHub/demo links to the project cards after you have public links available; they are not invented here because they were not listed in the résumé.
- Replace or update any project description that no longer reflects the current implementation.


## Separate academic sections

The portfolio has distinct Education, Certificates, and Achievements sections. Education reflects the B.E. Computer Science and Engineering degree from Dhanalakshmi College of Engineering (2022–2026) and CGPA 8.10/10. Certificates list the four Udemy courses named in the résumé: Generative AI Engineering, Prompt Engineering, Java OOP, and HTML/CSS. Achievements lists the 2nd-prize college paper presentation result.

Actual certificate documents were not included with the résumé. To link them, create `assets/certificates/`, copy the certificate PDFs or images there, and add a link to the appropriate `.certificate-card` in `index.html`.


## Schooling details to personalize

The Education section now includes separate Class XII (HSC) and Class X (SSLC) cards. The uploaded résumé did not contain the school names, boards, passing years, or results, so these are shown as clearly marked placeholders. Replace the bracketed values in `index.html` with your actual details before publishing.

Email links open a Gmail compose window in the browser addressed to prabhadivya934@gmail.com. Visitors may need to sign in to Gmail.
