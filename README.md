## WhitneyWrks CSS Framework Instructions

### Screenshot
![App Screenshot](https://i.imgur.com/5n4A8Xs.png)

![App Screenshot](https://i.imgur.com/QR6xr2J.png)

![App Screenshot](https://i.imgur.com/lv7tOIt.png)

### Getting Started

1. Download the CSS framework files from the [GitHub repository](https://github.com/alexa-whitney/ACS3320-CSS-Framework).
2. Include the CSS file in your HTML document by adding the following line inside the `<head>` tag:

   ```html
   <link
     rel="stylesheet"
     type="text/css"
     href="path_to_your_css/whitneywrks.css"
   />
   ```

### Usage

Here's a basic HTML template that includes the WhitneyWrks framework:

```html
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Your Page Title</title>
    <link
      rel="stylesheet"
      type="text/css"
      href="path_to_your_css/whitneywrks.css"
    />
  </head>
  <body>
    <!-- Navigation Bar -->
    <div class="navbar">
      <!-- Navbar content goes here -->
    </div>

    <!-- Main Content -->
    <div class="container main">
      <section class="whitney-card">
        <!-- Your section content goes here -->
      </section>
    </div>

    <!-- Page Footer -->
    <div class="page-footer">
      <!-- Footer content goes here -->
    </div>
  </body>
</html>
```

#### Components and Classes

1.  Navigation Bar
    Use the .navbar class to style your navigation bar:

    ```html
    <div class="navbar">
      <ul>
        <li><a href="#">Home</a></li>
        <!-- Add more navigation items here -->
      </ul>
    </div>
    ```

2.  Headings:
    Apply the .whitney-card class to sections that you want to highlight with the card style:

    ```html
    <section class="whitney-card">
      <h1>Main Heading</h1>
      <h2>Subheading</h2>
      <!-- Additional content -->
    </section>
    ```

3.  Buttons
    Use <button> elements for clickable actions, styled automatically by the framework:

    ```html
    <button>Click Me!</button>
    ```

4.  Forms
    Wrap your form elements with .form-group for proper spacing and alignment:

    ```html
    <form>
    <div class="form-group">
        <label for="name">Name:</label>
        <input type="text" id="name" placeholder="Enter your name" />
    </div>
    <!-- Add more form elements here -->
    </form>
    ```

5.  Footer
    Structure your footer with the .page-footer class:

    ```html
    <div class="page-footer">
        <div class="footer-content">
            <!-- Footer content such as links and information -->
        </div>
    </div>
    ```

#### Typography

The CSS framework provides a set of predefined typography styles that you can use. Here's how to apply them:

1. Add the appropriate class to the HTML element you want to style. For example, to apply a heading style, use the `h1`, `h2`, `h3`, etc. classes:

   ```html
   <h1 class="h1">Heading 1</h1>
   <h2 class="h2">Heading 2</h2>
   <h3 class="h3">Heading 3</h3>
   ```

2. Customize the typography styles by modifying the corresponding CSS classes in the framework file.

### Customization

You can customize the CSS framework to suit your project's needs. Here are some ways to do it:

1. Modify the existing CSS classes in the framework file to change the default styles.
2. Add your own CSS classes and styles to extend the framework's functionality.
3. Override the framework styles by adding your own CSS rules in a separate stylesheet.

### Examples

To help you get started, the CSS framework repository includes an example file (css_framework_starter.html) that demonstrate how to use the framework in different scenarios.

### Contributing

If you encounter any issues or have suggestions for improvement, feel free to contribute to the CSS framework by submitting a pull request on the GitHub repository.
