# 3D Contact Page

This project creates a 3D contact page using A-Frame.js, a powerful framework for building virtual reality experiences on the web.

## Project Overview

The 3D contact page displays the following information:

- **Name:** Aaron Lei
- **Image:** A profile picture
- **Title:** Coding Enthusiast
- **Contact Information:**
  - Email: @example.com
  - Phone: Don't wanna share
  - Discord: orange_ramune
- **Skills:** HTML, CSS, JavaScript
- **Education:** FreeCodeCamp
- **Misc Links:**
  - GitHub: [https://github.com/aaronsfunstuff](https://github.com/aaronsfunstuff)
  - Hack Club Scrapbook: [https://scrapbook.hackclub.com/AaronLei](https://scrapbook.hackclub.com/AaronLei)

## Technologies Used

- **HTML:** Structure of the page.
- **A-Frame.js:** Framework for creating 3D and VR experiences.
- **CSS:** Styling for the page.
- **JavaScript:** For additional functionality and interactivity.

## How It Was Made

1. **Setting Up the HTML Structure:**
   - A basic HTML document structure was created with a DOCTYPE declaration, head section, and body section.
   - The A-Frame library and other necessary scripts were included in the head and body sections.

2. **Creating the A-Frame Scene:**
   - An `<a-scene>` element was added to contain all the 3D elements.

3. **Adding a Background Plane:**
   - An `<a-plane>` element was added to serve as the background for the contact information, positioned at `0 0 -4` with a width of `8` and height of `18`.

4. **Displaying Text Elements:**
   - Multiple `<a-text>` elements were added to display various pieces of information like the name, title, contact details, skills, education, and links.
   - Each `<a-text>` element was positioned appropriately within the scene and styled with a white color and different scales.

5. **Adding an Image:**
   - An `<a-image>` element was used to display a profile picture, positioned at `-2.5 6.7 -3.9` with a width and height of `2`.

6. **Adding an Environment:**
   - An `<a-entity>` element with the `environment` component was added to create a surrounding environment with a preset named "yavapai".

7. **Styling the Page:**
   - A separate CSS file (`style.css`) was linked in the head section to apply additional styling to the HTML and A-Frame elements.

8. **Including Additional Scripts:**
   - The A-Frame library, environment component, and a custom JavaScript file (`script.js`) were included to handle any additional functionality and interactivity.

## How to Run the Project

1. Ensure you have an internet connection to load the A-Frame library and environment component.
2. Open the HTML file in a web browser.
3. The 3D contact page should display with all the information and links.

## Future Improvements

- Add interactivity to the text elements (e.g., make the links clickable).
- Enhance the visual design with more complex 3D models or animations.
- Improve accessibility by ensuring the text is readable in VR environments.

This project demonstrates the basics of creating a 3D contact page using A-Frame.js, providing a unique and engaging way to present contact information and links.
