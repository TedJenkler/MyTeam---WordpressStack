# MyTeam - WordpressStack

## Table of Contents
1. [Breakpoints](#breakpoints)
2. [Accessibility (a11y)](#accessibility-a11y)
   - [Keyboard Navigation](#keyboard-navigation)
   - [ARIA Roles](#aria-roles)
   - [Alt Text for Images](#alt-text-for-images)
   - [Accessibility Testing with Axe](#accessibility-testing-with-axe)
   - [Accessibility Testing with WAVE](#accessibility-testing-with-wave)

---

## Breakpoints

These are the breakpoints used in the project, targeting various device screen widths:

- **320px**: Very small smartphones (portrait)
- **360px**: Small smartphones (portrait)
- **375px**: Small-medium smartphones (portrait)
- **390px**: Small-medium smartphones (portrait)
- **414px**: Small smartphones (portrait)
- **480px**: Smaller smartphones (portrait)
- **540px**: Small-medium smartphones
- **568px**: Medium smartphones (portrait)
- **600px**: Larger smartphones or small tablets (portrait)
- **640px**: iPhone 5/5s (landscape)
- **667px**: iPhone 6/7/8 (portrait)
- **750px**: iPhone 6/7/8 Plus (portrait)
- **800px**: Small tablets (landscape)
- **834px**: iPad Mini (portrait)
- **1024px**: Tablets (portrait) or small laptops
- **1194px**: Larger tablets or smaller desktops
- **1200px**: Desktop or large tablets
- **1280px**: Standard laptops or desktops
- **1366px**: Laptops or small desktops
- **1512px**: Large laptops or desktop screens
- **1536px**: Large desktop monitors
- **1600px**: Large desktops or wide laptops
- **1920px**: Full HD monitors
- **2560px**: Ultra-wide or 4K displays

---

## Accessibility (a11y)

### Keyboard Navigation

- I have ensured that all links are tabbable, allowing users to easily navigate through the site.

### ARIA Roles

I have added ARIA attributes to enhance accessibility for screen readers and assistive technologies. Specifically, the following improvements were made:

- **`aria-label`**: Added to custom components, like pricing, to provide clear and descriptive labels, ensuring assistive technologies can accurately communicate the purpose of each component.  
- **`aria-describedby`**: Used to associate form fields with error messages or additional instructions, offering users contextual guidance during interactions.  
- **`aria-live="polite"`**: Implemented for error messages to ensure they are dynamically announced to users by assistive technologies without interrupting their workflow.  

These additions make the interface more inclusive and improve the overall user experience for all users, including those relying on assistive tools.

### Alt Text for Images

- I have added `alt` text on all images that aren't used as background images, ensuring that screen readers can interpret them for better accessibility.

### Alt Text for Images

- I have added `alt` text on all images that aren't used as background images, ensuring that screen readers can interpret them for better accessibility.

### Accessibility Testing with Axe

- I have tested the site using the Axe DevTools browser extension to identify and resolve accessibility issues. The testing ensures compliance with WCAG 2.1 AA standards.
- All detected issues from Axe have been reviewed and addressed where applicable to improve the overall accessibility of the site.

### Accessibility Testing with WAVE

- I have tested the site using the WAVE Web Accessibility Evaluation Tool to identify potential accessibility issues.  
- While WAVE flagged the contrast on the "About" buttons as insufficient, I decided to retain the current color scheme for design consistency and brand identity.  
- To balance aesthetics and accessibility, I ensured that all other interactive elements meet contrast requirements and implemented additional accessibility features to enhance the overall user experience.  
