# Layout Risk and Breakpoint Inventory

## Layout patterns: list at least five layout patterns in your capstone, such as hero, navigation, card grid, table, form, media/text split, sidebar, or resource list.

- Hero
- Navigation
- Card grids
- Table
- Form

## Content risks: identify long headings, long links, dense cards, tables, forms, embedded media, or other content likely to break layouts.

- Hero - content struggles to fit with narrow viewports 
- Navigation - cannot fit all html links on the top bar without overflow off the page for some tablet sized viewports
- Card grids - content needs to be adaptable for each page and intended layout
- Table - lots of overflow on table, forced to use horizontal scrollbar

## Breakpoint reasons: name at least three places where layout may need to change and explain the content-based reason.

- Navigation - need to be able to fit a "contact" link on the nav bar for wider views, sizing of nav boxes needs to accomodate this 
- Card grids - currently, the grids would be disrupted by addition of more cards on certain pages but it needs to stay adaptable
- Table - lots of overflow on the schedule table, bad user experience for mobile viewers

## Container-query candidates: identify at least one component that may appear in different-width contexts.

- Card grids are the primary items I believe could be adaptable depending on the container width
- Table depending on how it was fixed as well, checkbox option to choose which day to display has potential

## Logical-property opportunities: list at least three physical properties or layout assumptions you can replace with flow-relative CSS.

- The labels for my form currently have a margin-bottom value that could be swapped for a block-end value
- Padding-top added to card images can utilize padding-block-start instead
- Width is used along the media queries and could potentially use inline-size instead

## Preference/fallback needs: identify one user preference or feature-support issue your layout should account for.

- Some properties like inline or block spacing are not supported by older browsers, may need fallback properties
- I plan to add animations later on and a reduced motion option would be good in that case
- High contrast option may help as well since the text on background image may be difficult to see