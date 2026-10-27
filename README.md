# Bahij Issa | Business & Data Analysis Portfolio

**Connecting business needs, data insights, and practical solutions.**

This personal portfolio introduces Bahij Issa’s professional background across business analysis, data analytics, and business strategy. It brings an introduction, a detailed resume, a downloadable CV, and direct contact options into one website, giving prospective employers and collaborators a clear starting point for a conversation.

## Purpose and audience

Evaluating a professional background involves more than reading a job title. Visitors need context about experience, education, skills, and how to take the next step.

The portfolio brings that information together so readers can move from a quick introduction to a fuller review of Bahij’s background, keep a copy of his CV, and reach out through their preferred channel. It is intended for people considering employment opportunities or professional collaboration with Bahij.

The resume describes experience in software product business analysis, sales and inventory analysis, e-commerce optimization, and client demonstrations and training. These are areas of Bahij’s professional experience; the website presents that background rather than providing analytical tools or services within the application.

## What visitors can do

| Visitor need | How the portfolio helps |
| --- | --- |
| Understand Bahij’s professional focus | The home page introduces his work in business analysis, data analytics, and business strategy, with direct routes to his resume and portfolio. |
| Review his qualifications | The resume brings together education, professional and extracurricular experience, awards, languages, and tools. |
| Keep a CV for later review | A PDF download is available directly from the resume page. |
| Find project updates | The portfolio provides a dedicated destination for future case studies and currently directs visitors to the resume for experience details. |
| Start a conversation | Email, telephone, and LinkedIn links are available on the contact page; the home page also links to GitHub. |
| Browse on different screen sizes | Responsive layouts and a collapsible mobile menu support navigation on desktop and mobile devices. |

## The visitor journey

1. **Get oriented.** The home page introduces Bahij and offers three next steps: view his work, read his resume, or contact him.
2. **Explore the background.** The About page provides a brief introduction, while the Resume page presents the detailed professional profile.
3. **Review and retain.** Visitors can read the resume online or download the PDF for later reference or sharing.
4. **Check project availability.** The Portfolio page identifies case studies as forthcoming and points to the resume in the meantime.
5. **Connect.** Visitors can open their email application, use the telephone link, or continue to LinkedIn.

The site uses direct page navigation and requires no account. Contact links hand off to the visitor’s chosen application or an external profile.

## Current scope

The current release is a professional profile and resume website. Its main navigation includes Home, About, Resume, Portfolio, and Contact.

Detailed project case studies have not yet been published: the Portfolio page displays “Projects coming soon.” Additional experience and detail pages remain in the repository, but currently serve as short signposts to the resume and portfolio rather than complete case studies or service descriptions.

The Contact page uses direct links rather than an on-site submission form. A PHP contact handler remains from the original template but is not connected to the current page.

## Technology and architecture

The application is a static website: the browser loads HTML pages, shared styles, JavaScript, images, and the CV PDF. There is no application build step, database, account system, or required backend for the current experience.

- **HTML5 and CSS3** provide the content and presentation, with Bootstrap 5 supporting responsive layouts.
- **JavaScript** handles shared interactions such as mobile navigation and scroll controls.
- **Bootstrap Icons, AOS, and Typed.js** provide icons, entrance animations, and the rotating role text on the home page.
- **Google Fonts** supplies Roboto, Poppins, and Raleway through external stylesheet requests.

Template libraries including Swiper, GLightbox, Isotope, imagesLoaded, PureCounter, and Waypoints are also bundled. Their presence does not mean the current site offers a populated project gallery, sliders, or analytical dashboards.

## Run locally

### Requirements

Use Git to clone the repository, Python 3 to run the local preview server, and a modern web browser. No package installation, API keys, or environment configuration is required.

### Setup

```sh
git clone https://github.com/Bijox/bahij-issa.github.io.git
cd bahij-issa.github.io
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) to view the website. If the repository is already on your computer, open a terminal in its folder and run only the Python command.

Save edits and refresh the browser to see changes. Stop the server with `Ctrl+C`. Internet access is needed to load Google Fonts and visit external profiles; site assets and the CV are stored locally.

## Maintaining and publishing the site

Edit the HTML pages to update profile content. The detailed resume is in `resume.html`, and its downloadable document is `assets/files/Bahij-Issa-CV.pdf`; keep both versions consistent when updating professional information.

Shared styling lives in `assets/css/main.css`, and shared browser interactions live in `assets/js/main.js`. Navigation and footers are repeated across the HTML pages, so changes to these elements should be applied consistently.

Before publishing, preview the main navigation, mobile menu, CV download, and contact links. When case studies are ready, replace the portfolio placeholder with the actual project content.

The site can be hosted by a static hosting service such as GitHub Pages. Publish the HTML files and `assets/` directory together, preserving relative paths. The local Python server is for previewing; it is not required on the hosting service. The unused PHP handler is not needed for the current contact experience.

## Connect with Bahij

- [LinkedIn](https://www.linkedin.com/in/bahij-issa/)
- [GitHub](https://github.com/Bijox)
- [Email](mailto:bahijissa8@gmail.com)
