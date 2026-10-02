# Accessibility Test Plan

## Pages to test: list at least three capstone pages or page types and why each matters.
- Home page: Home page is going to be the landing page for all users, allowing proper navigation from here is important
- Group classes: Group classes would be the next step for any new skater so making it accessible for users first landing on the site is important
- Contact us: Contact is important for any floating questions, requests, bugs, or suggestions.
## Structure checks: landmarks, headings, page titles, links, buttons, and native HTML decisions.
- Nav is located within header, landmarks are structured and available Header(Logo/Navigation), Main, and Footer
- Headings are clear and present, placed for describing page structure of:
    - h1: Hidden under logo to allow for screen reader accessibility
    - h2: Used to describe sections of each page
    - h3: Used for card headings
- Page titles are present, each taking the format of (Tacoma Figure Skating Club | *current page*)
- Some links may need aria labels since they are presented as buttons but not using the button object
- Page utilizes native HTML decently, one change needs to be made for card information (remove h4 items)
## Keyboard checks: focus order, visible focus, skip links if used, current page state, and keyboard traps.
- Keyboard navigation check completed in Chrome for wide desktop view, tab/shift+tab, all nav links are accessible with focus-visible, order is logical with page flow
## Visual checks: zoom/reflow, text spacing, contrast, line length, and responsive conditions.
- Completed via Chrome DevTools responsive view, main content is readable in all views, horizontal scrollbar present for schedule as an exception.
## Complex content checks: forms, tables, images, SVGs, audio/video, embeds, or motion where applicable.
- Forms: labels are present for each form field given, aria-labels may be needed for specificity of each field, aria-required to be added
- Tables: All table heads are labeled with their scopes also added in.
- Images have alt descriptions available
- Only SVGs utilized are the logo placed as a background image, h1 is in place for screen readability
- Video has no captions needed, there is a description underneath the video, also it is the only embed placed
- Motion reduction available for transitions and such
## Tool plan: name at least one automated checker and at least three manual checks you will perform.
- Will utilize the axe DevTools to analyze accessibility, manual checks include Chrome DevTools utilizing different screens of different widths and DPRs, utilizing a screen reader to listen to page content, and ensure colors are properly contrasted.
## Evidence plan: describe how you will document findings, fixes, retests, and remaining limitations.
- Findings will be documented by describing tools and conditions used, fixes and retests will be documented in commits within GitHub and limitations will be documented in their own separate sheet.