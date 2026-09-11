# CSS Architecture Notes

## Layer Order

- I utilized the order of: 
- reset, base, components, utilities, states, overrides, and queries

## Token Decisions 

- I am using a ranging scale of blue hues based off the logo
    - I named each color according to their use case, 
        - Primary is a dark blue hue used for dark text, lines, or items that would normally be black on a typical webpage.
        - Important is a light blue used for links and buttons and to catch attention
        - Heading is another blue hue utilized for headings to stand out
        - Card is used for cards to show slight contrast between background and foreground
        - Surface is the top layer color used for the background of all elements
        - Debug has been implemented temporarily for debugging.
- I switched to using rem scaling for the styles so it will be easier to adapt into smaller views when I fixed it up for mobile first
    - Sizing scale was decided based on browser inspection using Chrome DevTools in mobile view

## Browser Checks

- I utilized Chrome DevTools in the responsive view and mobile viewport widths down to 320px and desktop viewport widths up to 1980px.
- I tested the keyboard navigation for focus-visible pseudo class usage

## CSS Ease

- The CSS felt a bit easier to maintain with the tokens, less variable with spacing and colors are easier accessible
- Trying out the utilities helps clean up the CSS a bit since a simple class can be added to the HTML instead, useful for changes that are obvious and easy to see

## AI Disclosure

This assignment as been completed independently without the use of any AI. Primary coding sources are MDN and given class resources. Source for site information is the Tacoma Twin Rinks site and the figure skating director, Elaine Jurun.
