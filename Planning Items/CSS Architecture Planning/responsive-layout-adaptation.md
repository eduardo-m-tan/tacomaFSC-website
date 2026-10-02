# Responsive Layout Adaptation Documentation

## Changes implemented

### Grid patterns
- I was able to utilize the grid-patterns with intrinsic sizing for my card-container class and my hero-text class
    - The card-container uses minmax/min/clamp to decide when to change layout and spacing.
    - The hero-text uses the grid layout to decide how much spacing to give itself on the page, relative to it

### Subgrid
- I was able to use subgrid for my card class, allowing all the three divs (containing: title/image, description, and card-button) to align when sitting side by side

### Container Query Usage
- Container query was utilized for my nav hamburger to wide nav bar, it now expands if it has enough space to support all six nav menu option, but not otherwise 

### Content-driven breakpoints
- Breakpoints were converted to rem measurements rather than hard breaks at pixels, scaling of the wrapper class was also modified with clamp for smoother transitions

### User-preferences
- Simple reduced motion user preference query was implemented

### Fallback Strategy
- The widest media query has a support query to see if container-type: inline-size is supported, and if not, the nav will be expanded at that width.

### AI Disclosure
This assignment was completed independently without the use of any assistive AI. Sources are MDN and given class resources.