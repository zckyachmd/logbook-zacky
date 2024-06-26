# Day 06 - CSS, CSS Layout

---

## Learnings

- **Introduction to CSS:**

  - Understanding what CSS (Cascading Style Sheets) is and its role in web development.
  - The purpose of CSS in styling HTML elements to enhance the visual presentation of web pages.

- **Using CSS:**

  - **External CSS:** Linking an external CSS file using the `<link>` tag in the HTML `<head>`.
  - **Internal CSS:** Writing CSS within the `<style>` tag inside the HTML `<head>`.
  - **Inline CSS:** Adding CSS directly to an HTML element using the `style` attribute.

- **CSS Properties:**

  - Exploring various CSS properties such as `color`, `font-size`, `margin`, `padding`, `border`, `background`, etc.
  - Learning how to apply these properties to HTML elements to style them.

- **CSS Naming Conventions:**

  - **Atomic CSS:** A utility-first approach where each class applies a single style rule.
  - **BEM (Block, Element, Modifier):** A naming convention methodology that helps in writing maintainable and scalable CSS.

- **CSS Layouts:**
  - **Flexbox:** A layout model that allows responsive elements within a container to be automatically arranged depending upon screen size (flex direction, justify content, align items, etc.).
  - **Grid:** A layout system that allows creating complex web designs using a grid of rows and columns (grid template columns, grid template rows, grid gap, etc.).

## Challenges

- Grasping the differences and use cases for external, internal, and inline CSS.
- Learning and implementing the various CSS properties effectively.
- Understanding and applying different CSS naming conventions.
- Creating complex layouts using Flexbox and Grid.

## Documentation

### Introduction to CSS

- **CSS (Cascading Style Sheets):** A stylesheet language used to describe the presentation of a document written in HTML or XML. CSS enhances the visual appeal and user experience of web pages.

### Using CSS

- **External CSS:**
  - Linking an external stylesheet in the HTML document:
    ```html
    <link rel="stylesheet" href="styles.css" />
    ```
- **Internal CSS:**
  - Writing CSS within the `<style>` tag inside the HTML `<head>`:
    ```html
    <style>
      body {
        background-color: lightblue;
      }
    </style>
    ```
- **Inline CSS:**
  - Adding CSS directly to an HTML element using the `style` attribute:
    ```html
    <h1 style="color:blue;">Hello World</h1>
    ```

### CSS Properties

- Various CSS properties were explored, including:
  - `color`, `font-size`, `margin`, `padding`, `border`, `background`, etc.
- Application of these properties to HTML elements to style and enhance the web page appearance.

### CSS Naming Conventions

- **Atomic CSS:** Each class represents a single style rule for high reusability.
- **BEM (Block, Element, Modifier):** A methodology for creating reusable components and code sharing in front-end development:
  - **Block:** The main container (e.g., `.block`).
  - **Element:** A part of the block that performs a certain function (e.g., `.block__element`).
  - **Modifier:** A flag on a block or element (e.g., `.block--modifier` or `.block__element--modifier`).

### CSS Layouts

- **Flexbox:**

  - A flexible box layout model that provides an efficient way to lay out, align, and distribute space among items in a container.
  - Example of Flexbox usage:
    ```css
    .container {
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
    }
    ```

- **Grid:**
  - A powerful layout system optimized for two-dimensional layouts with rows and columns.
  - Example of Grid usage:
    ```css
    .container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-template-rows: repeat(2, 100px);
      gap: 10px;
    }
    ```

## Next Steps

- Practice creating more complex layouts using Flexbox and Grid.
- Experiment with various CSS properties to better understand their effects on elements.
- Continue refining CSS skills and learn about responsive design techniques.
- Implement CSS naming conventions in upcoming projects for better maintainability.

## References

- [Bearmentor Bootcamp Day 06 Documentation](https://github.com/bearmentor-community/bearmentor-bootcamp/blob/main/days/day-06.md)
