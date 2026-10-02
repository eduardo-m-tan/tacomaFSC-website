# CSS System Needs

## Repeated components

1. Cards
    - These are planned to be used variably but most likely for the coaches' information each having their own cards, each with a header, image, and paragraph
    - Styling will be made compatible to be with or without an image
2. Buttons
    - Buttons will be present on most pages directing the user to the correct pages and/or information
3. Navigation
    - Navigation bar will be present for both desktop/tablet view, hamburger menu for mobile but same state styles will be present
4. Tables
    - The schedules will all be posted within simple tables until support for a live schedule is implemented (not within class scope)
5. Media Blocks
    - Media blocks will be present to display images.


## Foundational decisions

- Primary coloring will lean towards simple black/white, blue hues found in the logo, and pink hue for a contrasting color
- Fonts expected to be used: Playfair Display, Montserrat, and Inter imported from google fonts
    - @import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap');
- Spacing will be variable dependent on display size, expecting a range of 4-8px between sections and 12-24px for padding, margins, or gaps.
- Container display width will be set to 90% while the max-widths will range with displays
    - Mobile: 600px
    - Tablet: 1024px
    - Desktop: 1440px
- Borders will be a standardized width, will be decided later with browser inspection during CSS implementation
- Focus will be utilized for buttons and links, with accessible options for focus-visible
- Links will be presented in the form of buttons and have states styling as well.

## Layout/Composition Needs

- Section spacing will be 4-8px
- Vertical mobile nav bar will be made usable for mobile view
- Container will be around body content to keep consistent width

## States 

- Hover states will exist for buttons, links, and navigation
- Focus active will be present on any forms
- Current page will use a higher contrast color to help user identify which page they're currently on
- Required/invalid form input will be needed when fields are missing
- Potential disabled state if fields are missing for the form (Pending JavaScript)

## Print needs

Print support is most likely going to be most important for the schedules pages, the current plan is to have one schedule for the rink's class and other session times, and another regarding events held at other ice rinks.

## Risk note(s)

- The homepage is likely to become messy if not planned properly, lots of images can become cluttered and messy quickly if not spaced and styled well.
