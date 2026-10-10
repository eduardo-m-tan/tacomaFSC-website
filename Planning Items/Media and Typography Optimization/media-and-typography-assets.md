# Media and Typography Assets Inventory/Provenance Check

## Images: list each image, purpose, source, license/permission, original format, current format, current dimensions, and expected display size
## Alt text plan: mark each image as informative, decorative, functional, or complex, and draft the alt text or alternative treatment.

- Hero Image:
    - Background graphic for decorative purposes only
    - Source: unsplash, https://unsplash.com/photos/a-group-of-people-skating-on-an-ice-rink-923mxIxfbns https://unsplash.com/@nktalya 
    - Free/open licensing 
    - Original Format: JPG
    - Current Format: WEBP
    - File dimensions: 1440px wide
    - Expected display size: Full viewport width
    - No alt text needed for decorative background graphic
- Upcoming Events Posters
    - October_ShowcasePoster
        - Graphic poster for an event being advertised on page
        - Source: Figure Skating Club Director
        - Permission: Figure Skating Club Director
        - Original Format: PNG
        - Current Format: PNG
        - Current Dimensions: 1254px * 1254px
        - Expected Display Size: Max of 300px wide, potential need for 2x, 3x compatibility
        - Alt text: "Poster for the Costume Showcase Party on Ice Event"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed
    - December_ShowcasePoster
        - Graphic poster for an event being advertised on page
        - Source: Figure Skating Club Director
        - Permission: Figure Skating Club Director
        - Original Format: PNG
        - Current Format: PNG
        - Current Dimensions: 1440px * 1734px
        - Expected Display Size: Max of 300px wide, potential need for 2x, 3x compatibility
        - Alt text: "Poster for the Holiday Tradition on Ice Event"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed
- Learn-To-Skate Image
    - Image showing young skaters learning from an instructor
    - Source: unsplash, https://unsplash.com/photos/2-children-in-red-jacket-and-black-pants-playing-ice-hockey-mNLTL_8IU3g https://unsplash.com/@shklyaevmax 
    - Free/open licensing
    - Original Format: JPG
    - Current Format: PNG
    - Current Dimensions: 1920px * 1280px
    - Expected Display Size: Max of 1200px wide
    - Alt text: "Image of young skaters learning to skate from an ice skating instructor"
    - Further alt description not necessary as image is mostly decoration.
- Coaching Images:
    - coach-elaine-jurun.webp
        - Image of Figure Skating Director
        - Sourced from Figure Skating Director
        - Permission: Elaine Jurun
        - Original Format: PNG
        - Current Format: Webp
        - Current dimensions: 400px * 400px
        - Expected display size: 300px * 300px
        - Alt text: "Image of figure skating director, Elaine Jurun"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed
    - coach-sample-1.webp
        - Stock image of figure skater
        - Sourced from Unsplash, https://unsplash.com/photos/a-young-female-figure-skater-performs-on-ice-YFWqyOENE2o?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText
        - Permission: Free/open licensing
        - Original Format: PNG
        - Current Format: Webp
        - Current dimensions: 400px * 400px
        - Expected display size: 300px * 300px
        - Alt text: "Image of basics coach, Jessica jones"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed
    - coach-sample-2.webp
        - Stock image of figure skater
        - Sourced from Unsplash, https://unsplash.com/photos/woman-performing-on-ice-skate-field-OcbZXVd0PIM?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText
        - Permission: Free/open licensing
        - Original Format: PNG
        - Current Format: Webp
        - Current dimensions: 400px * 400px
        - Expected display size: 300px * 300px
        - Alt text: "Image of freestyle coach, Paulina Paloma"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed
- Local Events Card Images:
    - ice-crystal-classic-2026
        - Logo image from Portland Ice Skating Club competition site
        - Source: PISC Site
        - Permission: From Club Director
        - Original/Current Format: PNG
        - Current Dimensions: 400px * 400px
        - Expected Display Size: Max of 300px wide, potential need for 2x, 3x compatibility
        - Alt text: "Image of Ice Crystal Classic Logo"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed
    - bremerton-cheers-for-fears-2026
        - Poster image from Bremerton FSC EntryEeze Site
        - Source: Bremerton FSC
        - Permission: From Club Director
        - Original/Current Format: PNG
        - Current Dimensions: 815px * 1054px
        - Expected Display Size: Max of 300px wide, potential need for 2x, 3x compatibility
        - Alt text: "Image of Cheers for Fears Poster"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed
    - isu-grand-prix-logo
        - Image of ISU grand prix series logo
        - Source: Open source image 
        - Permission: Open source
        - Format: PNG
        - Current Dimensions: 250px * 283px
        - Expected Display Size: Max of 300px wide, potential need for 2x, 3x compatibility
        - Alt text: "Image of ISU Grand Prix Series logo"
        - Further alt description not necessary as the card the image lays on has the rest of the information needed

## Media: list any audio, video, animation, or embed with caption, transcript, control, motion, fallback, and privacy notes.

- Logo SVG Files
    - Logo used for header, hidden text header present to operate with screen readers.

## Typography: list fonts, source, license, fallback stack, weights/styles used, and loading strategy.

- Fonts used: Inter, Montserrat, Open Sans
- Source of Fonts: Google Fonts
- Licensing: Creative Commons: CC BY-SA 4.0, SIL Open Font License
- Font stack used for body: 'Inter', 'Open Sans', 'Arial', sans-serif
- Font stack used for headers: 'Montserrat', 'Helvetica', 'Arial', sans-serif
- 700 weight used for headers, 400 weight used for body text
- Fonts imported via given Google Fonts URL

## Optimization risks: identify the three assets most likely to affect performance, accessibility, or layout shift.

- The background hero image has the highest resolution, currently, leading to the highest performance issues to come.
- The posters on the home page are also much larger resolution than needed, leading to performance issues.
- Later implementation of planned Learn-to-Skate image could potentially be an issue as well, it is quite high resolution.

## Evidence plan: name the checks you will run for file size, dimensions, responsive behavior, loading, and accessibility.

- For file size checks, I will use Google DevTools with the different DPR options, different device options, and also the Lighthouse tool. For accessibility, screen readers will be used.