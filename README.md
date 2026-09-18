# NTE Construction Website

## Project Overview

NTE Construction is a fictional residential home renovation company based in Gauteng, South Africa. The website was developed to provide homeowners with information about the company's renovation services and to encourage potential customers to submit enquiries.

The website was created as part of the web development assignment and demonstrates HTML, CSS and responsive web design principles.

## Organisation

**Company:** Nkhutsane Trading Enterprise
**Trading Name:** NTE Construction
**Industry:** Residential Home Renovations
**Location:** Gauteng, South Africa
**Founded:** 2015

NTE Construction was founded by James Malose Teffo and is currently controlled by Director Lesetja Teffo. The company focuses on providing residential renovation services to homeowners.

## Website Goals

The main goals of the website are to:

* Generate qualified renovation enquiries.
* Build credibility for NTE Construction.
* Showcase the company's renovation services.
* Provide clear information about the business.
* Make it easy for potential customers to contact the company.
* Provide a responsive experience on desktop, tablet and mobile devices.

## Target Audience

The primary target audience is homeowners in Johannesburg, Pretoria and surrounding Gauteng areas who are interested in residential renovations.

The website is designed for customers looking for services such as:

* Kitchen renovations
* Bathroom renovations
* Living room renovations
* Bedroom renovations
* Exterior renovations
* Complete home renovations

## Website Pages

The website contains five main pages:

### Home

The Home page introduces NTE Construction, explains why customers should choose the company and provides calls-to-action for requesting a quotation and viewing services.

### About

The About page provides information about the company's history, mission, vision and values.

### Services

The Services page displays the renovation services offered by NTE Construction. It also includes the company's renovation process.

### Enquiry

The Enquiry page contains a form that allows potential customers to provide their contact details and project requirements.

### Contact

The Contact page provides office and location information together with a map and contact information.

## Technologies Used

The website was developed using:

* HTML5
* CSS3
* CSS Grid
* CSS Flexbox
* CSS Media Queries
* Responsive Images
* GitHub for version control

## Part 2 – CSS Styling

An external CSS stylesheet was created and linked to all website pages.

The stylesheet is located in:

```text
CSS/styles.css
```

CSS variables were used to maintain consistent colours and styling throughout the website.

The main colours include:

* Primary Blue: `#0525f4`
* Dark Blue: `#071a52`
* White: `#ffffff`
* Black: `#111111`
* Light Grey: `#f4f6fa`

## Typography

The website uses a clean sans-serif font for readability.

Responsive typography was implemented using CSS `clamp()` functions. This allows headings to adjust according to the screen size.

Examples include:

* H1 headings
* H2 headings
* H3 headings
* Paragraph text
* Section labels

## CSS Layout

CSS Grid and Flexbox were used to create the website layouts.

### CSS Grid

Grid is used for:

* Hero section
* Feature cards
* Services
* Mission and vision
* Values
* Process steps
* Contact sections
* Footer

### Flexbox

Flexbox is used for:

* Navigation
* Navigation links
* Hero buttons
* Form elements
* Call-to-action sections
* Information items

## Visual Styling

The website uses several CSS visual effects, including:

* Background colours
* Borders
* Border radius
* Box shadows
* Hover effects
* Transitions
* Active navigation styling
* Focus effects on form fields

Hover effects were added to navigation links, buttons, service cards, feature cards and contact cards.

## Responsive Design

The website was designed to work on different screen sizes.

Three main responsive layouts were implemented:

### Desktop

The desktop layout uses multiple columns for sections such as the services, features and footer.

### Tablet

A media query is used at:

```css
@media (max-width: 900px)
```

The layout changes to fewer columns and the hero section changes to a single-column layout.

### Mobile

A media query is used at:

```css
@media (max-width: 600px)
```

On mobile devices:

* Navigation links wrap onto multiple lines.
* Content changes to single-column layouts.
* Service cards become one column.
* Feature cards become one column.
* Forms become one column.
* Contact sections become one column.
* Footer content becomes one column.
* Buttons expand to the available width.

An additional breakpoint was created for very small devices:

```css
@media (max-width: 380px)
```

## Responsive Images

Images are sized using responsive CSS rules so that they can adapt to different screen sizes.

The service images use:

```css
width: 100%;
object-fit: cover;
```

This helps images fit within their containers while maintaining an appropriate visual presentation.

## Feedback and Changes from Part 1

The following improvements were made during Part 2:

| Change            | Description                                             |
| ----------------- | ------------------------------------------------------- |
| External CSS      | Created and linked an external `styles.css` stylesheet. |
| Typography        | Added consistent heading, paragraph and label styling.  |
| Layout            | Added CSS Grid and Flexbox layouts.                     |
| Navigation        | Improved navigation styling and added hover effects.    |
| Buttons           | Added styled buttons with hover transitions.            |
| Service cards     | Added structured service cards with responsive layouts. |
| Forms             | Styled the enquiry form and added focus effects.        |
| Responsive design | Added tablet and mobile media queries.                  |
| Images            | Added responsive image sizing and object-fit styling.   |
| Footer            | Added a structured responsive footer.                   |
| Visual effects    | Added borders, shadows, transitions and hover effects.  |

## Testing

The website should be tested at different screen sizes to ensure that the layout remains usable and readable.

### Desktop Testing

Recommended test size:

**1440 × 900**

### Tablet Testing

Recommended test size:

**768 × 1024**

### Mobile Testing

Recommended test size:

**390 × 844**

Testing should check:

* Navigation
* Text readability
* Images
* Buttons
* Service cards
* Forms
* Contact information
* Footer
* Page spacing
* Responsive layout

## Screenshots

Screenshots demonstrating the responsive design should be stored in the `screenshots` folder.

Recommended screenshots:

```text
screenshots/
├── desktop-home.png
├── tablet-home.png
└── mobile-home.png
```

The screenshots provide evidence that the website was tested at different screen sizes.

## GitHub Version Control

GitHub was used to store and manage the project files.

Descriptive commits should be made throughout development.

Examples of commit messages:

```text
Initial Part 2 CSS styling
Added responsive desktop layout
Added tablet media query
Added mobile media query
Improved service card styling
Added responsive images
Updated README and changelog
Final Part 2 testing
```

## Changelog

### Part 2

* Created external CSS stylesheet.
* Added CSS variables for consistent colours.
* Added typography styling.
* Added CSS Grid layouts.
* Added Flexbox layouts.
* Added hover and focus effects.
* Added responsive tablet layout.
* Added responsive mobile layout.
* Added extra-small device breakpoint.
* Improved image responsiveness.
* Improved service, contact and enquiry layouts.
* Added responsive footer.
* Added README documentation.
* Added testing and screenshot evidence.

## References

The following resources were used for learning and understanding HTML and CSS concepts:

* MDN Web Docs – HTML
* MDN Web Docs – CSS
* MDN Web Docs – CSS Grid
* MDN Web Docs – CSS Flexbox
* MDN Web Docs – CSS Media Queries
* W3Schools – HTML and CSS reference material

## Conclusion

The NTE Construction website demonstrates the use of HTML and CSS to create a professional and responsive residential renovation website.

Part 2 focuses on external CSS styling, typography, Grid and Flexbox layouts, visual styling and responsive design for desktop, tablet and mobile devices.
