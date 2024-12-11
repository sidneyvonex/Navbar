# Menu Project

This repository contains a simple HTML and CSS project demonstrating a hover effect on a button. The project is designed to provide a visual zoom effect when a user hovers over the button, showcasing the use of CSS transformations.

## Features
- Interactive button with a hover zoom effect using CSS.
- Clean and minimalist design for demonstration purposes.
- Responsive and visually appealing.

## Files in This Repository
1. **index.html**: The main HTML file containing the structure of the webpage.
2. **stylesheet.css**: The CSS file defining the styles for the webpage, including the hover effect.
3. **background iamge.jpg**: The background image used in the project to enhance aesthetics.

## How It Works
The project applies the following CSS rule to the button:
```css
button:hover {
    transform: scale(1.3);
}
```
This causes the button to scale up by 30% when hovered over, creating a smooth zoom effect. To make the effect even more polished, a transition property is used:
```css
button {
    transition: transform 0.3s ease;
}
```

## How to Use
1. Clone or download this repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. Hover over the button to see the effect in action.

## Hosting
To view this project online, you can host it on GitHub Pages:
1. Upload the files to a GitHub repository.
2. Enable GitHub Pages under the repository settings.
3. Access the hosted project via the provided GitHub Pages URL.

## Preview
![Project Preview](background%20iamge.jpg)

## License
This project is open-source and available under the [MIT License](LICENSE).
