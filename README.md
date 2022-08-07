# frontend-mentor-signup-form
Solution to the Frontend Mentor intro component with signup form challenge using HTML, SCSS, and JS.

Thank you for checking out my solution!

## The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - Any `input` field is empty. The message for this error should say *"[Field Name] cannot be empty"*
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Looks like this is not an email"*
  
  ## Built with

- Semantic HTML5 markup
- CSS custom properties
- SCSS
- Flexbox
- Mobile-first workflow

For the desktop version of the webpage, the content was centered on the page using flexbox. Flexbox was also used to place the form and heading/description block side by side.

Error icons were positioned inside the input field using `position: relative;` on the input field container and `position: absolute;` on the icons themselves.

Instead of using a media query, JS was used to apply `padding: 80px` and `height: auto;` to the `<main>` tag when the height of the content exceeds the height of the viewport.
