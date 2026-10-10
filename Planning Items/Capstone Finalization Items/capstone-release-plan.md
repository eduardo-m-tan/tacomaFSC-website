# Capstone Release Plan

Confirm the scope of your final capstone and create a release plan. This step helps you identify what must be finished, what can be simplified, and what evidence already exists.

## Final page list: pages that will be included in the submitted capstone.
Page list has stayed consistent, including:
- index.html - Home landing page with a call to action hero, intro section, rink events section, and visiting information section
- group-class.html - Group classes page to help users understand group class offerings
- schedule.html - Extended schedule to see weekly sessions
- coaches.html - Page to give descriptors for each coach and a contact link
- local-events.html - Page to show local events external to the ice rink
- contact.html - Page for people to contact the club board regarding any questions

## Must-fix list: up to eight issues that block release quality, with priority and owner/action.
- Replace placeholder images - was pending photos from director and never received them
    - Use other placeholder images and text for the meantime while waiting for approval of real coaching staff
    - Priority: medium-high, developer will implement changes

## Evidence already complete: list evidence from Modules 1-6 that can be reused in the final package.
- accessibility-conformance-inclusive-check.md
    - Accessibility checks are still valid and accurate
- metadata-inventory.md
    - Metadata checks are still valid and accurate

## Evidence still needed: release checks, published URL checks, validation, links, performance, compatibility, or technical defense items still missing.
- W3C check re-completed on all HTML pages and the CSS
- All published URLs are operational
- Lighthouse check completed:
    - Performance: 96
        - Improved by removing embedded video and creating a more optimized hero image
    - Accessibility: 100
    - Best Practices: 100
    - SEO: 100
- axe DevTools found no issues
- Responsiveness is still in tact

## Scope decisions: features, pages, polish, or stretch goals you will defer so the final release stays focused.
- Images were intended to be added to bottom of home page for visiting section but received late
    - Images will be add at a later release

## Release plan: what you will complete before submission.
- Replace the placeholder images, remove embedded video, optimized hero image sizing
