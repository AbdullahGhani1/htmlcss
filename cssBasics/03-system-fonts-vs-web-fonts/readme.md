# Fonts

You can explore and choose from a wide range of fonts at [Google Fonts](https://fonts.google.com/)

In this example, we'll use the Poppins font, which can be added to your project in two different ways: via the HTML `<head>` or directly in your CSS file.

- Before linking your stylesheet, include the following `<link>` tags in the `<head>` section of your HTML file to load the Poppins font from Google Fonts:

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap"
  rel="stylesheet"
/>
```

- Alternatively, you can import the Poppins font directly within your CSS file using the @import rule:

```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap");
```
