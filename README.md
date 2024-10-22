# Login Interface Tutorial with Modern CSS Validation

Welcome to this tutorial where we explore how to create a **Login Interface** using **Modern CSS** to achieve form validation that was previously only possible with JavaScript. This project started with a design in Figma and was transformed into a functional interface using CSS without any JavaScript.

![Project Cover](./portada.jpg)

## Project Overview

In this project, we demonstrate how to use modern CSS techniques such as:

- **CSS pseudo-classes** like `:valid` and `:invalid`
- The new **`transition-behavior: allow-discrete`** property that allows smooth transitions between `display: none` and `display: block`
- Using **`opacity`** transitions in combination with `display` to create smooth fade-in and fade-out animations for validation messages

### What we've achieved:

1. **Form validation** using CSS, without the need for JavaScript.
2. **Smooth animations** for validation feedback, including transitions for error messages.
3. **Interactive Login Interface** that responds to user input in real-time with CSS-based validation.
4. **Responsive design** for optimal use across different devices.

## Features

- **Email and Password Validation:** The form uses modern CSS to validate email and password fields. Error messages appear smoothly when the input is invalid.
- **Button State Handling:** The submit button becomes enabled only when the form fields are valid.
- **CSS-only Solution:** No JavaScript was used in the validation logic—everything is done purely with CSS!

### CSS Techniques Used:

- **CSS pseudo-classes** (`:valid`, `:invalid`, `:not(:placeholder-shown)`)
- **Transitions with `transition-behavior: allow-discrete`** to manage discrete properties like `display`.
- **Opacity transitions** for smooth appearance of validation messages.

## How to Use

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Open `index.html` in your browser to see the login interface in action.

3. Modify the CSS file (`styles.css`) to customize the form and validation messages as needed.

## Conclusion

This project shows the power of modern CSS to handle what was once considered only achievable with JavaScript. With new properties like `transition-behavior` and pseudo-classes, we can now create interactive, accessible forms using CSS alone!
