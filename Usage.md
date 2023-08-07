# NoJS CSS framework

## 1. **Introduction**:

- **Brief Description**: NoJS is a lightweight CSS framework designed to be easy to use and customize. It includes a variety of components and utilities to help you build responsive, modern web applications.
- **Getting Started**: To use NoJS, simply include the `nojs.css` file in your HTML document. You can also customize the framework by modifying the variables in the `nojs-variables.css` file.
- **Browser Support**: NoJS is designed to work in all modern browsers, including Chrome, Firefox, Safari, and Edge.

## 2. **General Concepts**:

- **File Structure**: The `nojs/` directory contains all of the CSS files for the framework. The `nojs.css` file is the main stylesheet, while `nojs-variables.css` contains all of the custom properties used throughout the framework. The `nojs-components/` directory contains all of the component styles, while the `nojs-utilities/` directory contains all of the utility classes.
- **Using Themes**: NoJS does not include a theme system, but you can customize the framework by modifying the variables in the `nojs-variables.css` file.
- **CSS Custom Properties (Variables)**: NoJS uses a variety of custom properties to make it easy to customize the framework. These properties are defined in the `nojs-variables.css` file.

## 3. **Component Documentation**:

For each component:

### Buttons

- **Description**: Buttons are used to trigger an action or event.
- **Usage**: To use a button, simply add the `nojs-button` class to a `<button>` element.
- **Modifiers**: NoJS includes several modifier classes for buttons, including `nojs-button--primary`, `nojs-button--secondary`, and `nojs-button--danger`.
- **Options**: No additional options are available for buttons.
- **Examples**:

```html
<button class="nojs-button">Click me</button>
<button class="nojs-button nojs-button--primary">Click me</button>
<button class="nojs-button nojs-button--secondary">Click me</button>
<button class="nojs-button nojs-button--danger">Click me</button>
```
Sure, here's the updated Usage.md file with proper Markdown formatting:

# Forms

**Description:** Forms are used to collect user input.

**Usage:** To use a form, wrap your form elements in a `<form>` element with the `nojs-form` class.

**Modifiers:** NoJS includes several modifier classes for forms, including `nojs-form--stacked` and `nojs-form--inline`.

**Options:** No additional options are available for forms.

**Examples:**
```html
<form class="nojs-form">
  <label>
    Name:
    <input type="text" name="name">
  </label>
  <label>
    Email:
    <input type="email" name="email">
  </label>
  <button type="submit">Submit</button>
</form>

<form class="nojs-form nojs-form--stacked">
  <label>
    Name:
    <input type="text" name="name">
  </label>
  <label>
    Email:
    <input type="email" name="email">
  </label>
  <button type="submit">Submit</button>
</form>

<form class="nojs-form nojs-form--inline">
  <label>
    Name:
    <input type="text" name="name">
  </label>
  <label>
    Email:
    <input type="email" name="email">
  </label>
  <button type="submit">Submit</button>
</form>
```

# Navigation

**Description:** Navigation menus are used to help users navigate a website or application.

**Usage:** To use a navigation menu, wrap your menu items in a `<nav>` element with the `nojs-nav` class.

**Modifiers:** NoJS includes several modifier classes for navigation menus, including `nojs-nav--horizontal` and `nojs-nav--vertical`.

**Options:** No additional options are available for navigation menus.

**Examples:**
```html
<nav class="nojs-nav">
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<nav class="nojs-nav nojs-nav--horizontal">
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>

<nav class="nojs-nav nojs-nav--vertical">
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Contact</a>
</nav>
```

# Tables

**Description:** Tables are used to display tabular data.

**Usage:** To use a table, wrap your table elements in a `<table>` element with the `nojs-table` class.

**Modifiers:** NoJS includes several modifier classes for tables, including `nojs-table--striped` and `nojs-table--bordered`.

**Options:** No additional options are available for tables.

**Examples:**
```html
<table class="nojs-table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Email</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John Doe</td>
      <td>john@example.com</td>
    </tr>
    <tr>
      <td>Jane Doe</td>
      <td>jane@example.com</td>
    </tr>
  </tbody>
</table>

<table class="nojs-table nojs-table--striped">
  <thead>
    <tr>
      <th>Name</th>
      <th>Email</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John Doe</td>
      <td>john@example.com</td>
    </tr>
    <tr>
      <td>Jane Doe</td>
      <td>jane@example.com</td>
    </tr>
  </tbody>
</table>

<table class="nojs-table nojs-table--bordered">
  <thead>
    <tr>
      <th>Name</th>
      <th>Email</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John Doe</td>
      <td>john@example.com</td>
    </tr>
    <tr>
      <td>Jane Doe</td>
      <td>jane@example.com</td>
    </tr>
  </tbody>
</table>
```

# Utilities:

NoJS includes a variety of utility classes to help you style your content. Here are a few examples:

## Spacing Utilities

Add margin or padding to an element. Classes are in the format `{property}{sides}-{size}`.

- `{property}`: `m` for margin, `p` for padding
- `{sides}`: `t` for top, `b` for bottom, `l` for left, `r` for right, `x` for horizontal, `y` for vertical
- `{size}`: `0` for 0 units, `1` for 0.25 rem, `2` for 0.5 rem, ...

**Examples:**

- `mt-1`: Margin-top of 0.25 rem.
- `px-2`: Padding on the left and right of 0.5 rem.

## Text Utilities

Change the color, size, or weight of text. Classes are in the format `{property}-{value}`.

- `{property}`: `color`, `size`, or `weight`
- `{value}`: Any valid CSS value for the given property

**Examples:**

- `color-red`: Red text.
- `size-2`: Text with a font size of 1.25 rem.
- `weight-bold`: Text with a font weight of bold.

# Customization:

To customize NoJS, simply modify the variables in the `nojs-variables.css` file. You can also add new components or extend existing ones by modifying the styles in the `nojs-components/` directory.

# Frequently Asked Questions (FAQs):

**Q:** How do I use NoJS in my project?

**A:** Simply include the `nojs.css` file in your HTML document.

**Q:** Can I customize the colors in NoJS?

**A:** Yes, you can modify the color variables in the `nojs-variables.css` file.

**Q:** Does NoJS include a theme system?

**A:** No, NoJS does not include a theme system.

# Changelog:

Version 1.0.0: Initial release.

# Contributing & Feedback:

If you're interested in contributing to NoJS, please see the `CONTRIBUTING.md` file for guidelines. If you have any feedback or issues to report, please open an issue on the GitHub repository.

# Best Practices:

When using NoJS, it's best to follow these guidelines:

- Use the utility classes to style your content, rather than creating custom styles.
- Use the modifier classes to customize the appearance of components, rather than modifying the component styles directly.
- Keep your HTML markup clean and semantic.
- Test your application in multiple browsers to ensure compatibility.