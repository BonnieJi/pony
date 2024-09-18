# Animated Images HTML Page

This HTML file demonstrates a simple webpage containing multiple images with absolute positioning and an animation using CSS keyframes. The main focus of this page is to showcase animations with various images placed at different positions on the screen.

## Files Required

- **HTML File:** The main HTML structure and layout of the page.
- **GIF Images:** The following images are referenced and need to be placed in the same directory as the HTML file:
  - `50125.gif`
  - `giphy.gif`
  - `50250.gif`
  - `1.gif`
  - `2.gif`

## How It Works

1. **Image Display:** The HTML file contains several `<img>` elements with various images. Each image is positioned absolutely within the browser window using inline CSS in the `style` attribute.
   - `50125.gif`, `giphy.gif`, `50250.gif`, and `1.gif` are placed at different corners of the screen.
   - The image with `id="flyingGif"` (`2.gif`) is animated to fly around the screen.

2. **Animation with CSS:** 
   - The animation is defined using the `@keyframes` rule inside a `<style>` block within the HTML file.
   - The animation, named `flyAllOver`, moves the image (`2.gif`) around the screen using a series of `translate()` transformations.
   - The `#flyingGif` is set to use this animation with `animation: flyAllOver 10s linear infinite;`, which means it will move around the screen infinitely with a 10-second duration.

## Setup Instructions

1. **Place Images:**
   - Save the referenced GIF images (`50125.gif`, `giphy.gif`, `50250.gif`, `1.gif`, and `2.gif`) in the same directory as this HTML file.

2. **Open the HTML File:**
   - Simply open the HTML file in a web browser to view the images and animation in action.

## Customization

- **Change Image Sources:** To use different images, replace the `src` attributes of the `<img>` tags with the paths to your desired images.
- **Adjust Image Positions:** Modify the `style` attributes of the `<img>` tags to change their positions on the screen.
- **Modify the Animation:** 
  - The animation is defined in the `@keyframes flyAllOver` rule. You can customize the positions and movement by editing the `transform: translate(x, y);` properties at various percentage points.
  - Adjust the duration and other properties of the animation by modifying the `animation` property applied to `#flyingGif`.

## Notes

- The inline CSS in this file is for demonstration purposes. For a more maintainable structure, you can move the CSS code into an external stylesheet.
- The images are positioned absolutely, so their placement will depend on the size of the viewport.
