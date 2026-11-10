# Health-Monitoring-and-wellness

A responsive, static health information website that brings everyday health guidance, basic checkup references, care options, and appointment planning together in one place.

The frontend is built with plain HTML and CSS. It contains no JavaScript, framework, build step, database, or server-side logic.

## Project overview

Health Monitoring & Tracker is designed as an approachable starting point for people who want to learn about common viral illnesses, understand a few basic health measurements, recognize warning signs, and find a next step for care. The layout groups these topics into clear sections and works on desktop and mobile screens.

This project is a static frontend demonstration. It does not diagnose illness, monitor or save personal health readings, locate real hospitals automatically, or send appointment requests to a provider.

## Website sections

### Home and navigation

The landing area introduces the site and provides links to the health guide, checkup references, hospitals, and appointment form. Navigation links jump to sections on the same page.

### Common viral illnesses

The health guide contains short, general introductions to:

- Flu (influenza)
- COVID-19
- Dengue
- The common cold
- Viral stomach illness, including norovirus
- Respiratory syncytial virus (RSV)

Each illness card links to further information from a health authority. Symptoms can overlap, and the guide does not determine the cause of an illness.

### Simple health checks

The checkup section gives general adult reference information for:

- Blood pressure
- Body temperature
- Resting pulse
- Oxygen saturation, when measured with a pulse oximeter

It also gives examples of situations that may need medical attention. The values are general references and may not apply to children, pregnancy, people with chronic conditions, people at altitude, or anyone with a clinician-provided care plan. The page encourages users to consider symptoms and seek care when they feel seriously unwell, rather than relying on a number alone.

### Warning signs and medicine safety

Prominent notices describe emergency warning signs and call out medicine safety considerations, including dengue-related bleeding risk and aspirin use in children and teenagers with viral illness. This information is educational and is not a substitute for individualized guidance from a qualified health professional.

### Hospital listings

The hospital section demonstrates the presentation of government and private care options. Its current entries are examples, not verified facilities. The site does not currently use the visitor's location or provide live addresses, hours, availability, prices, or directions.

### Appointment form

The form collects a name, visit type, preferred date, and area in the browser and is configured with a placeholder `mailto:` action. It is not connected to a clinic, booking system, or backend. Replace the placeholder action and connect a secure appointment service before using it for real requests. Do not submit sensitive medical details through this demo form.

## Technology

- HTML5 for page content and semantic structure
- CSS for layout, colors, typography, and responsive behavior
- No JavaScript
- No package manager or compilation required
- Google Fonts are referenced online for DM Sans and Manrope; system fallbacks are provided by CSS

## Project structure

```text
.
├── README.md
└── outputs/
    ├── index.html
    └── styles.css
```

## Customization

- **Page content:** edit `outputs/index.html`.
- **Colors, spacing, and responsive layouts:** edit `outputs/styles.css`.
- **Hospital directory:** replace the sample hospital cards with verified local details and contact links.
- **Appointment requests:** replace the placeholder `mailto:` action with a properly secured booking integration.
- **Branding:** update the page title, header and footer in `outputs/index.html`; adjust styles in `outputs/styles.css` as needed.
- **Health information:** review all health text against current, authoritative sources and show the date of review when maintaining a production site.

## Accessibility and responsive design

The page includes a viewport setting for mobile devices, labelled form controls, descriptive navigation labels, and a CSS layout that adapts for smaller screens. The health reference table can scroll horizontally on narrow screens. When changing the design, preserve readable contrast, visible focus states, and meaningful labels for interactive controls.

## Health information disclaimer

The content is general educational information, not medical advice, diagnosis, or treatment. Reference ranges vary by person and measurement method. Consult a qualified health professional for personal concerns. For severe or rapidly worsening symptoms, contact local emergency services.

Hospital information in this demo is illustrative and should not be relied on to find care. Verify facility names, services, costs, and availability directly with a provider. External reference links may change over time.

## Future improvements

Possible next steps for a production version include a verified location-based hospital directory, a secure appointment booking workflow, user-controlled health record storage, localization, and a clinical review process for health content. These features are not included in the current static frontend.
