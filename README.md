# Tailwind CSS Color Variables

## Overview

This project is a collection of color variables of Tailwind CSS, a utility-first CSS framework. Tailwind CSS provides an extensive set of predefined color classes, but it lacks the ability to easily access these colors in JavaScript or other CSS parts of the application. This repository aims to solve this problem by providing all the Tailwind CSS colors as CSS variables that can be used throughout your project.

## How to Use

### Installation

To use the Tailwind CSS color variables in your project, simply include the provided `colors.css` file in your HTML or import it in your CSS file.

### Accessing Colors

All colors are defined as CSS variables in the `:root` selector, and they follow the naming convention `--color-{colorName}-{shade}`. For example, the variable for the red color with a shade of 500 would be `--color-red-500`. You can use these variables in your styles like this:

```css
.element {
    background-color: var(--color-blue-300);
    color: var(--color-gray-800);
}
```

### Contributing

If you notice any issues with the color definitions or want to add more colors or shades, feel free to contribute to this project! Simply fork the repository, make your changes, and submit a pull request.

### License

This project is open-source and available under the [MIT License](LICENSE).

## Disclaimer

This project is not an official part of Tailwind CSS and is maintained by the community. The colors used in this project are sourced from the Tailwind CSS documentation and are subject to change if the official Tailwind CSS project updates its color palette.
