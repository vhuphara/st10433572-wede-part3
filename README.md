# Muramba PTY (LTD) Website

## Project Overview

Muramba PTY (LTD) is a transport and logistics company website developed to provide customers with information about the company's services and allow potential customers to make enquiries.

The website was developed in stages. Part 1 focused on the website structure, Part 2 improved the styling and responsive design, and Part 3 focused on further functionality, usability, accessibility and website optimisation.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Responsive Web Design
- Google Fonts

## Website Pages

The website contains the following pages:

- Home (`index.html`)
- About Us (`about.html`)
- Services (`services.html`)
- Gallery (`gallery.html`)
- Request a Quote (`enquiry.html`)
- Contact (`contact.html`)

## Part 2: CSS Styling and Responsive Design

Part 2 improved the website's visual presentation, layout, responsiveness and usability.

### CSS Styling

- Added an external stylesheet at `css/style.css`.
- Improved typography, spacing and page layouts.
- Added consistent colours, buttons, borders and shadows.
- Improved navigation, cards, service sections and footer styling.
- Added hover effects and keyboard focus indicators.

### Responsive Design

Responsive CSS layouts were developed for desktop, tablet and mobile screens.

Media queries were used to adjust navigation, typography, images, service sections, gallery layouts, forms, buttons and footer content.

### Responsive Images

Selected images use `srcset`, `sizes`, lazy loading and asynchronous image decoding where appropriate.

### Accessibility

The website includes semantic HTML, skip-to-content links, descriptive image alternative text and visible keyboard focus states.

## Part 3: Functionality and Improvements

Part 3 builds on the existing website structure and responsive styling.

### JavaScript Functionality

The shared JavaScript file is located at `js/script.js`.

Depending on the functionality implemented and tested, it supports features such as:

- Back-to-top button behaviour.
- Smooth scrolling for in-page links.
- Client-side form validation assistance.
- Gallery lightbox interactions.
- Automatic updating of the displayed copyright year.

### Search Engine Optimisation

The website includes page titles and descriptions intended to help search engines understand the content of each page. Structured data and other metadata are included where implemented.

### Forms and Customer Enquiries

The enquiry and contact pages provide fields for customers to enter their details and describe their requirements. Form validation helps users identify missing or invalid information.

**Note:** If the forms use `mailto:` links, they prepare an email in the visitor's email application. They do not independently store submissions or send emails from a server.

### Accessibility and Usability

The website retains its skip-navigation link, semantic page structure, descriptive image text and keyboard focus indicators. Interactive features should be tested with a keyboard and at different screen sizes.

## Project Structure

```text
Muramba/
├── index.html
├── about.html
├── services.html
├── gallery.html
├── enquiry.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   ├── Logo.png
│   ├── hero.jpeg
│   ├── hero-400.jpg
│   ├── hero-800.jpg
│   └── other website images
├── README.md
└── CHANGELOG.md
```

The image filenames shown are examples of the project's image assets. The actual folder contents may differ.

## Testing

The website should be tested on desktop, tablet and mobile screen sizes.

Testing should include:

- Navigation links and page loading.
- Image loading and gallery interactions.
- Form validation.
- Back-to-top button behaviour.
- Keyboard accessibility.
- Browser console errors.
- Horizontal scrolling and responsive layouts.
- Live website functionality after deployment.

Record actual results in the testing checklist or testing document. Do not mark untested features as successful.

## Deployment

Live website: https://muramba.netlify.app/

## Part 3: Adding Functionality and SEO

### Overview

Part 3 improves the Muramba PTY (LTD) website by adding JavaScript functionality, form validation, search engine optimisation (SEO) and usability improvements.

### JavaScript functionality

The website includes the following interactive features:

- A gallery lightbox that allows users to view images in a larger format.
- Keyboard controls for navigating gallery images and closing the lightbox.
- A back-to-top button to help users return to the top of a page.
- Smooth scrolling for supported in-page links.
- JavaScript form validation and feedback messages.
- Automatic updating of the footer copyright year.

### Forms

The Contact form collects the customer's name, email address, phone number, subject and message. The Enquiry form collects transport requirements, including the service requested, collection location, delivery location, preferred date and items to be transported.

Both forms validate input and prepare an email in the user's email application. The customer must review and send the email manually. The forms do not currently store submissions in a database.

### Search Engine Optimisation

SEO improvements include:

- Unique page titles and meta descriptions.
- Relevant keywords describing Muramba's transport and logistics services.
- Image alternative text where appropriate.
- Canonical and social-sharing metadata on the homepage.
- Structured data on the homepage.
- Responsive page layouts and clear navigation.

### Testing

The following functionality was tested on the deployed website:

- All six website pages load and navigation links work.
- Contact form required fields and invalid email validation.
- Enquiry form required fields, invalid email and past-date validation.
- Preparation of contact and transport enquiry emails in Outlook.
- Enquiry confirmation details.
- Gallery lightbox and keyboard controls.
- Back-to-top button and footer copyright year.

### Technologies Used

- HTML5
- CSS3
- JavaScript
- Visual Studio Code
- Git and GitHub
- Netlify hosting

### Limitations

The forms use email preparation through the user's email application. They do not automatically send messages or save customer submissions on a server. A backend service would be needed for automatic submission processing and storage.

### References

Google Search Central (n.d.) *SEO Starter Guide*. Available at: https://developers.google.com/search/docs/fundamentals/seo-starter-guide (Accessed: 2 November 2026).

Mozilla Developer Network (MDN) (n.d.) *HTML forms*. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms (Accessed: 2 November 2026).

Mozilla Developer Network (MDN) (n.d.) *JavaScript*. Available at: https://developer.mozilla.org/en-US/docs/Web/JavaScript (Accessed: 2 November 2026).

World Wide Web Consortium (W3C) (n.d.) *Web Content Accessibility Guidelines (WCAG) 2.2*. Available at: https://www.w3.org/TR/WCAG22/ (Accessed: 2 November 2026).

The deployed website should be checked after the final changes have been published.

## References

Mozilla Developer Network (MDN) (n.d.) *CSS: Cascading Style Sheets*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 2 November 2026).

Mozilla Developer Network (MDN) (n.d.) *Responsive design*. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design (Accessed: 2 November 2026).

Mozilla Developer Network (MDN) (n.d.) *HTML: HyperText Markup Language*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML (Accessed: 2 November 2026).

Google (n.d.) *Google Fonts*. Available at: https://fonts.google.com/ (Accessed: 2 November 2026).
