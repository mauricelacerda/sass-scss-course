# How CSS Works: A Look Behind the Scenes

_An in-depth view on the inner workings of CSS and how it gets applied to HTML documents._

## Three Pillars to Write Good HTML and CSS

..._and build good websites_

### Responsive design

_**Definition:** Building responsive layouts mean designing applications that work, look and feel good across all devices, screen sizes and bandwidths_

- Fluid layouts
- Media queries
- Responsive images
- Correct units
- Desktop-first vs. mobile-first strategies

### Maintainable and scalable code

_**Definition:** Writing code that is/has:_

- Clean
- Easy to understand
- Modular and reusable
- Supports growth and scalability
- Well organized files and folders
- Logical and well written class names
- Nice architecture and structure

### Performance

_**Definition:** Writing code that is fast and efficient_

- Less HTTP requests
- Less code
- Compressed/ minified code
- Use a CSS Preprocessor
- Less images/ media files
- Compressed, properly sized images/ media files

## CSS Behind the Scenes

1. Load HTML

2. Parse HTML

   _1. Build Document Object Model_

3. Load CSS

4. Parse CSS

   _1. Resolve conflicting CSS declarations (cascade)_

   _2. Process final CSS values_

5. CSS Object Model

6. Build Render Tree

7. Website rendering: _the visual formatting model_

8. Final rendered website

## How CSS is Parsed: The Cascade and Specificity

```css
.my-class /* selector */ {
  /* declaration block */
  color: blue; /* declaration */
  text-align: center; /* declaration */
  font-size: 20px; /* declaration */
  /* property: value */
}
```
