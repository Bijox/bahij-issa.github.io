# Bahij Issa — Portfolio

A static, multi-page portfolio based on BootstrapMade's Personal template.
There is no package manager, compilation step, or JavaScript framework.

## Structure

- `index.html`: personalized home page and animated role description.
- `about.html`, `resume.html`, `portfolio.html`, `contact.html`: main content pages.
- `portfolio-details.html`, `services.html`, `service-details.html`: template project and service pages.
- `starter-page.html`: template for adding a page.
- `assets/css/main.css`: shared styles, including theme variables near the top.
- `assets/js/main.js`: navigation, scroll behavior, animations, sliders, and portfolio filtering.
- `assets/img/`: profile, background, project, and other images.
- `assets/vendor/`: bundled third-party libraries; prefer making custom changes in the shared CSS/JS files.
- `assets/scss/`: explanatory text only; Sass sources are not included.
- `forms/contact.php`: contact endpoint requiring an additional PHP email library.

Each page loads its own copies of the shared navigation/footer markup and references
the same styles and scripts. Navigation changes must currently be repeated across pages.

## Local preview

From this directory:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. This serves the static site; it does not execute PHP.
Most pages still contain template names, sample contact details, and placeholder copy.
Review these before publishing.

## Contact form

The form cannot send email as checked in. `forms/contact.php` expects
`assets/vendor/php-email-form/php-email-form.php`, which is not included, and its
recipient is still `contact@example.com`. The bundled `validate.js` only handles
the browser-side submission and response display.

To enable sending, provide the required library and configure the recipient and
mail transport on PHP-capable hosting, or replace the endpoint with a form service.
Keep credentials out of public files and add server-side validation and spam protection.
Static hosting alone cannot run this PHP endpoint.

## Suggested next improvements

1. Personalize all pages and make their navigation consistent with the home page.
2. Configure and verify contact delivery before presenting the form as working.
3. Give content images meaningful alternative text and form fields visible labels.
4. If the site grows, use shared layout templates to avoid duplicating headers and footers.
5. Load optional vendor libraries only on pages that use them, updating their shared
   JavaScript initialization at the same time.

Preserve the original template attribution and consult `Readme.txt` for its license link.
