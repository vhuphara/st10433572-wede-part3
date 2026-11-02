# Muramba PTY (LTD) Website Changelog

## Part 1: Feedback Implementation

The Part 1 assessment feedback was positive. The lecturer stated:

> Well done, you did a very good job.

No specific corrective changes were identified in the feedback provided. The project continued to develop through improvements to its styling, responsiveness and functionality.

## Part 2: CSS Styling and Responsive Design

**Date:** 2026

### Overview

Part 2 focused on improving the visual design, layout, responsiveness and usability of the Muramba PTY (LTD) website.

### Changes Made

#### 1. External CSS Stylesheet

- Used the external stylesheet `css/style.css`.
- Applied consistent styling across the website pages.
- Created reusable CSS classes for buttons, containers, sections, cards and layouts.

#### 2. Base Styling and Typography

- Added CSS reset and box-sizing rules.
- Improved default margins, spacing and typography.
- Used responsive typography where appropriate.
- Improved the visual hierarchy of headings and paragraphs.

#### 3. Layout and Visual Design

- Improved the header, navigation and footer.
- Used Flexbox and Grid for suitable layouts.
- Improved service cards, gallery layouts and content sections.
- Added consistent colours, borders, rounded corners, shadows and interactive states.

#### 4. Responsive Design

- Added responsive layouts for different screen sizes.
- Used media queries to adjust navigation, typography, images, cards, forms, buttons and footer layouts.
- Improved spacing and alignment on smaller screens.

#### 5. Responsive Images

- Used `srcset` and `sizes` for selected images.
- Applied lazy loading to suitable images.
- Used asynchronous image decoding where appropriate.
- Created resized image versions for selected assets.

#### 6. Accessibility

- Added skip-to-content links.
- Improved semantic HTML structure.
- Added visible keyboard focus states.
- Improved image alternative text and navigation states.
- Included reduced-motion support where implemented.

#### 7. Pages Updated

- `index.html`
- `about.html`
- `services.html`
- `gallery.html`
- `enquiry.html`
- `contact.html`

## Part 3: Functionality, Accessibility and Optimisation

**Date:** 2 November 2026

### Overview

Part 3 builds on the styling and responsive design completed in Part 2. The focus is on improving website functionality, customer interaction, accessibility and optimisation.

### Changes Made

#### 1. JavaScript

- Added or updated the shared JavaScript file at `js/script.js`.
- Implemented back-to-top behaviour where configured.
- Added smooth scrolling for supported in-page links.
- Added client-side form validation assistance.
- Added gallery lightbox functionality where configured.
- Added automatic copyright-year updating where configured.

#### 2. Enquiry and Contact Forms

- Improved the enquiry and contact form interfaces.
- Used HTML form validation to help users complete required fields.
- Added email-preparation functionality where implemented.

Forms using `mailto:` require the visitor's email application and do not provide server-side storage or automatic email delivery.

#### 3. SEO Improvements

- Reviewed page titles and meta descriptions.
- Added or reviewed search-engine metadata.
- Added structured data where implemented.
- Reviewed the homepage image metadata and loading behaviour.

#### 4. Accessibility and Usability

- Retained skip-to-content links and semantic page structure.
- Reviewed descriptive image alternative text.
- Reviewed keyboard focus and interactive controls.
- Prepared the website for testing at different viewport sizes.

#### 5. Documentation

- Updated `README.md` to document the project structure and implemented features.
- Updated `CHANGELOG.md` to record development changes.

### Testing

The following areas should be checked and the actual results recorded before submission:

- Navigation and page links.
- Responsive layouts.
- Image loading.
- Gallery interactions.
- Enquiry and contact form validation.
- Back-to-top button.
- Keyboard accessibility.
- Browser console errors.
- Live deployment.

Testing results must reflect the features actually tested.

### Version Control

Suggested commit messages:

```text
Update Part 2 CSS styling
Implement responsive layouts
Improve accessibility and navigation
Add Part 3 JavaScript functionality
Improve SEO metadata
Update project documentation
Test website before final submission
```

## Final Note

The changelog records the development history of the Muramba PTY (LTD) website. Features should only be described as completed when they have been implemented and verified.
## Part 3 - Adding Functionality and SEO
**Date:** 2 November 2026

### Added
- JavaScript functionality for the gallery lightbox and keyboard navigation.
- Back-to-top functionality and smooth scrolling for supported links.
- Client-side validation and feedback for the Contact and Enquiry forms.
- Email preparation for contact messages and transport enquiries.
- SEO metadata, including page titles, meta descriptions and relevant keywords.
- Homepage social-sharing metadata and structured data.

### Tested
- All six website pages and navigation links.
- Required-field and invalid-input handling on both forms.
- Email preparation through Outlook.
- Gallery lightbox, keyboard controls and back-to-top functionality.
- Footer copyright year display.

### Notes
- Contact and Enquiry forms prepare email drafts; users must send them manually.
- Form submissions are not stored in a database.
- The live website was checked after deployment.