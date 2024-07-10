# Including Atkinson Hyperlegible Font in Your HTML Website

To include the Atkinson Hyperlegible font in your HTML website, follow these instructions:

## Step 1: Define the Font Faces in CSS

First, you need to define the `@font-face` rule in your CSS file. This rule tells the browser where to find the font files and how to apply them.

```css
@font-face {
    font-family: 'Atkinson Hyperlegible';
    src: url('https://cdn.jsdelivr.net/gh/rysto3/AtkinsonFont@main/font-files/web/WOFF2/Atkinson-Hyperlegible-Regular-102a.woff2') format('woff2');
    font-weight: 400;
    font-style: normal;
}

@font-face {
    font-family: 'Atkinson Hyperlegible';
    src: url('https://cdn.jsdelivr.net/gh/rysto3/AtkinsonFont@main/font-files/web/WOFF2/Atkinson-Hyperlegible-Italic-102a.woff2') format('woff2');
    font-weight: 400;
    font-style: italic;
}

@font-face {
    font-family: 'Atkinson Hyperlegible';
    src: url('https://cdn.jsdelivr.net/gh/rysto3/AtkinsonFont@main/font-files/web/WOFF2/Atkinson-Hyperlegible-Bold-102a.woff2') format('woff2');
    font-weight: 700;
    font-style: normal;
}

@font-face {
    font-family: 'Atkinson Hyperlegible';
    src: url('https://cdn.jsdelivr.net/gh/rysto3/AtkinsonFont@main/font-files/web/WOFF2/Atkinson-Hyperlegible-BoldItalic-102a.woff2') format('woff2');
    font-weight: 700;
    font-style: italic;
}
```

## Step 2: Apply the Font to Your Website

After defining the `@font-face` rules, you can apply the font to your website by specifying the `font-family` in your CSS selectors.

```css
body {
    font-family: 'Atkinson Hyperlegible', sans-serif;
}
```

You can also apply the font to specific elements as needed:

```css
h1, h2, h3, h4, h5, h6 {
    font-family: 'Atkinson Hyperlegible', sans-serif;
}

p {
    font-family: 'Atkinson Hyperlegible', sans-serif;
    font-weight: 400; /* Regular */
}

em {
    font-family: 'Atkinson Hyperlegible', sans-serif;
    font-style: italic;
    font-weight: 400; /* Italic */
}

strong {
    font-family: 'Atkinson Hyperlegible', sans-serif;
    font-weight: 700; /* Bold */
}

strong em {
    font-family: 'Atkinson Hyperlegible', sans-serif;
    font-style: italic;
    font-weight: 700; /* Bold Italic */
}
```

## Step 3: Example HTML

Here's a basic example of how to use the font in your HTML file:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atkinson Hyperlegible Font Example</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph with the Atkinson Hyperlegible font.</p>
    <p><em>This text is italic.</em></p>
    <p><strong>This text is bold.</strong></p>
    <p><strong><em>This text is bold and italic.</em></strong></p>
</body>
</html>
```

By following these steps, you can include and use the Atkinson Hyperlegible font in your HTML website. Make sure to link your CSS file in your HTML document correctly.

# What is this?
The Atkinson Hyperlegible font was created by The Braille Institute to provide greater legibility and readability for low vision readers. The font is named after The Braille Institute's founder, J. Robert Atkinson. 

The font focuses on letterform distinction to increase character recognition, ultimately improving readability. 

# Why do you love this font?
My Mom became legally blind as an adult, and seeing the extra effort she has to go through each day in order to read things has made me interested in improving accessibility. 

I wanted to use this font as the primary font on a lot of projects I work on, including my website(s). Rather than self-hosting the font, I wanted to be able to use a service like JSDelivr to make it load as quickly as possible. Hosting it here on GitHub not only allows me to do exactly that, it allows me to further spread the word about this font. 

# How exactly does this font make it easier for people to read it?
This font has unambiguous, distinctive elements and sometimes unexpected forms with the goal of increasing character recognition. 
![Image demonstrating Atkinson Hyperlegible when blurred to simulate low vision](https://cdn.jsdelivr.net/gh/rysto3/AtkinsonFont@main/images/Atkinson-Blur.webp "Atkinson Hyperlegible Blur")

![Image demonstrating Times New Roman when blurred to simulate low vision](https://cdn.jsdelivr.net/gh/rysto3/AtkinsonFont@main/images/TNR-Blur.webp "Times New Roman")

You can learn more about the font in [the PDF provided by The Braille Institute](https://cdn.jsdelivr.net/gh/rysto3/AtkinsonFont@main/BIA_AtkinsonHyperlegible_Specimen-8.5x11_240202-ACC.pdf)