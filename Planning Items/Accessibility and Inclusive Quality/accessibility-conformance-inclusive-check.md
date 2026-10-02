# Deliverable: Accessibility Conformance and Inclusive Quality Build

Improve the accessibility conformance and inclusive quality of your capstone website. Build from your Module 4 media and typography work and document evidence from automated checks, manual testing, remediation, and retesting.

## Test scope:
- index: Testing the home page is critical as all users will be landing there, must allow navigation to other pages
- local-events: There are many links present and it is similar to the coaches page so testing will be parallel there
- contact: Contact page is the most unique out of the rest and forms are important for accessibility

I have ruled out the schedule page and group classes page since the schedule cannot really be adjusted and already has relevant scopes, the group classes is a simple page with just info + one table and one image

## Semantic structure:
Condition(s): utilizing WAVE tool, axe DevTools, and Chrome DevTools
- WAVE tool identifies the structure looks correct for all three pages, landmarks are identifiable and headings are structured properly
- Native HTMl items are used primarily to allow for screen reader accessibility
- Page titles are relevant to page purpose, each using the format "Tacoma Figure Skating Club | *current page*"
- Links and buttons all have relevant associated text, no confusion present

## Keyboard and focus:
Condition(s): utilizing WAVE tool, Chrome DevTools, standard desktop view on Chrome
- WAVE tool displays keyboard navigation access/focus order to be logical, cycling through the navigation links and then buttons/links in logical order on the page
- Focus-visible has two layers allowing for visibility/accessibility on any background, maroon/white for contrast
- Skip needs to be implemented, currently there is no extra class to accommodate for that
- No keyboard traps, keyboard tabbing is continuous

## Zoom, reflow, text spacing, and contrast:
Condition(s): Zoom at 200% and narrow viewport using Chrome DevTools, Galaxy S20 Ultra View
- Page is readable and usable, no content overflows to the sides requiring a horizontal slide bar
- Reflow and text spacing is responsive, all text is readable and there are no present issues
- High contrast is available for state classes used on all link/form fields

## Forms and tables: labels, instructions, errors, required states, captions, headers, scope, and responsive table strategies are checked where applicable.
Condition: Standard desktop viewport on Chrome, only checking on contact.html page since no tables or forms are present on the other two pages
- Labels are present, relevant, and attached on the form
- Instructions should be specified better, placeholder text should be added
- aria-required is not yet implemented despite required state being utilized, required also needs to be indicted in-text on the page
- No current error feedback, requires implementation

- Table strategies N/A

## Media, motion, and alternatives:
Condition(s): Standard desktop viewport on Chrome, WAVE accessibility tool
- Logo is implemented as a background SVG, h1 is visually hidden near as a supplement for screen readers
- Background image for hero is decorative and requires no additional text to identify it
- All card images have simple alt text to allow screen readers to identify there is a logo there related to the surrounding card information
- No SVG labels needed 
- There is a figure caption for the video on the index.html but no transcripts or captions are needed since there is no audio
- Fallback link is available for the embedded video
- Reduced-motion is available, reducing transition and animation speeds

## Automated and manual evidence:
Conditions(s): axe DevTools v4.138.0, standard desktop viewport on Chrome
- axe DevTools:
    - Identified one color contrast issue with the inactive button on the home page, not urgent since the button is not needed but will reduce opacity to allow for better contrast
    - No other issues identified on all three pages
- Manual keyboard navigation:
    - All links are reachable via keyboard navigation, visually identifiable with the double layer focus-visible border
- Zoom/reflow check: all items usable and readable, no horizontal scrolling present
- Visual/semantic check: No visual issues

## Screen reader or accessibility-tree sampling: 
- Accessibility tree check: Accessibility labels need to be added to the heads of each page, currently missing
- Screen reader was utilized and all information seems to be listenable
- Hard to identify what could be missed when I am trying to catch all items but may not, accessible users may be wanted for proper testing of these tools

## Remediation log: document at least five findings with issue, evidence, impact, priority, fix, and retest result.


## Conformance summary: summarize what appears to conform, what was fixed, what remains limited, and what should be checked again before final release.


## AI disclosure: if used, document purpose, output considered, verification, and what changed.