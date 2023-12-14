# Tailwind CSS Project

> These are projects built with the Tailwind CSS framework.

[![NPM](https://img.shields.io/npm/v/cdbreact.svg)](https://www.npmjs.com/package/cdbreact)
![npm](https://img.shields.io/npm/dm/cdbreact)

## Install

npm install -D tailwindcss
npx tailwindcss init

### add path to all your template

```jsx
module.exports = {
	content: ["./src/**/*.{html,js}"],
	theme: {
		extend: {},
	},
	plugins: [],
};
```

### add the the directives

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### start your Tailwind build environment

```
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

## Usage

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Tailwind tables</title>
		<link rel="stylesheet" href="style.css" />
	</head>
	<body></body>
</html>
```

## Documentation

You can check out some blog posts that help explain these better below

You can check out some blog posts that help explain these better below

- [Tailwind animation-How to create Tailwind CSS Animation](https://www.devwares.com/blog/create-animation-with-tailwind-css/)
- [Tailwind grid-How to use tailwind CSS grid templates in your project](https://www.devwares.com/blog/how-to-add-tailwind-css-grid-to-your-project/)
- [How to create a Beautiful Responsive Navigation bar Using Tailwind CSS](https://www.devwares.com/blog/how-to-create-a-beautiful-responsive-navbar-using-tailwind-css/)
- [Tailwind form-How to create and style a Responsive Form using Tailwind CSS](https://www.devwares.com/blog/how-to-create-and-style-a-responsive-form-using-tailwindcss/)
- [Tailwind CSS Flex: How to use Tailwind CSS Flex](https://www.devwares.com/blog/how-to-use-tailwind-css-flex/)
- [How to use tailwind css padding, margin and border in your project.](https://www.devwares.com/blog/how-to-use-tailwind-css-padding-margin-and-border-in-your-project/)
- [Tailwind CSS CDN-How to use the Tailwind CSS JIT CDN](https://www.devwares.com/blog/how-to-use-the-tailwind-css-JIT-CDN/)
- [How to set up your first Tailwind CSS Project](https://www.devwares.com/blog/setting-up-your-first-project-using-tailwind-css/)
- [How to use Tailwind CSS in HTML](https://www.devwares.com/blog/how-to-use-tailwind-css-in-HTML/)
- [Tailwind CSS table-How to Create Tailwind CSS tables](https://www.devwares.com/blog/how-to-create-tailwind-css-tables/)
- [How to create Tailwind CSS Components for your Website](https://www.devwares.com/blog/how-to-create-tailwind-css-components-for-your-website/)
- [Tailwind 3.0 is finally available. here are all the major changes](https://www.devwares.com/blog/tailwind-3.0-is-finally-out/)
- [How to set up your first Tailwind CSS Project](https://www.devwares.com/blog/setting-up-your-first-project-using-tailwind-css/)
- [Why is tailwind css better than other css framework](https://www.devwares.com/blog/why-tailwind-css-is-good/)
- [10 tailwind CSS templates and themes](https://www.devwares.com/blog/tailwind-css-10-templates-and-themes/)
- [How to add tailwind CSS colors and Fonts to your project](https://www.devwares.com/blog/how-to-add-tailwind-css-colors-and-fonts-to-your-project/)
- [Differences between Tailwind CSS and SASS](https://www.devwares.com/blog/differences-between-tailwind-css-and-sass/)
- [Differences Between Tailwind CSS and Bootstrap](https://www.devwares.com/blog/diffrences-between-tailwind-css-and-bootstrap/)
- [10 Awesome projects built with Tailwind CSS](https://www.devwares.com/blog/awesome-10-projects-built-with-tailwind/)
- [How to use Tailwind css Width](https://www.devwares.com/blog/Tailwind-width/)

  
  ## Tailwind CSS Classes
  - [Tailwind CSS Z-index](https://www.devwares.com/tailwindcss/classes/Z-index/)
  - [Tailwind Align Items](https://www.devwares.com/tailwindcss/classes/tailwind-align-items/)
  - [Tailwind Align Self](https://www.devwares.com/tailwindcss/classes/tailwind-align-self/)
  - [Tailwind CSS Classes](https://www.devwares.com/tailwindcss/classes/index/)
  - [Tailwind Animation](https://www.devwares.com/tailwindcss/classes/tailwind-animation/)
  - [Tailwind Background Attachment](https://www.devwares.com/tailwindcss/classes/tailwind-background-attachment/)
  - [Tailwind Background Clip](https://www.devwares.com/tailwindcss/classes/tailwind-background-clip/)
  - [Tailwind Background Color](https://www.devwares.com/tailwindcss/classes/tailwind-background-color/)
  - [Tailwind CSS Background Image](https://www.devwares.com/tailwindcss/classes/tailwind-background-image/)
  - [Tailwind CSS Background Origin](https://www.devwares.com/tailwindcss/classes/tailwind-background-origin/)
  - [Tailwind CSS Background Position](https://www.devwares.com/tailwindcss/classes/tailwind-background-position/)
  - [Tailwind CSS Background Repeat](https://www.devwares.com/tailwindcss/classes/tailwind-background-repeat/)
  - [Tailwind CSS Background Size](https://www.devwares.com/tailwindcss/classes/tailwind-background-size/)
  - [Tailwind Border Collapse](https://www.devwares.com/tailwindcss/classes/tailwind-border-collapse/)
  - [Tailwind Border Radius](https://www.devwares.com/tailwindcss/classes/tailwind-border-radius/)
  - [Tailwind Border Radius](https://www.devwares.com/tailwindcss/classes/tailwind-border-spacing/)
  - [Tailwind CSS Border Width](https://www.devwares.com/tailwindcss/classes/tailwind-border-width/)
  - [Tailwind CSS Box Shadow Color](https://www.devwares.com/tailwindcss/classes/tailwind-box-shadow-color/)
  - [Tailwind CSS Content](https://www.devwares.com/tailwindcss/classes/tailwind-content/)
  - [Tailwind CSS Box Shadow](https://www.devwares.com/tailwindcss/classes/tailwind-box-shadow/)
  - [Tailwind Display](https://www.devwares.com/tailwindcss/classes/tailwind-display/)
  - [Tailwind CSS Fill](https://www.devwares.com/tailwindcss/classes/tailwind-fill/)
  - [Tailwind CSS Flex Direction](https://www.devwares.com/tailwindcss/classes/tailwind-flex-direction/)
  - [Tailwind CSS Flex Grow](https://www.devwares.com/tailwindcss/classes/tailwind-flex-grow/)
  - [Tailwind CSS Flex Shrink](https://www.devwares.com/tailwindcss/classes/tailwind-flex-shrink/)
  - [Tailwind CSS Flex wrap](https://www.devwares.com/tailwindcss/classes/tailwind-flex-wrap/)
  - [Tailwind CSS Flex](https://www.devwares.com/tailwindcss/classes/tailwind-flex/)
  - [Tailwind CSS Floats](https://www.devwares.com/tailwindcss/classes/tailwind-floats/)
  - [Tailwind Font Family](https://www.devwares.com/tailwindcss/classes/tailwind-font-family/)
  - [Tailwind CSS Font size](https://www.devwares.com/tailwindcss/classes/tailwind-font-size/)
  - [Tailwind CSS Font Weight](https://www.devwares.com/tailwindcss/classes/tailwind-font-weight/)
  - [Tailwind CSS Gap](https://www.devwares.com/tailwindcss/classes/tailwind-gap/)
  - [Tailwind Grid Auto Columns](https://www.devwares.com/tailwindcss/classes/tailwind-grid-auto-columns/)
  - [Tailwind Grid Auto Rows](https://www.devwares.com/tailwindcss/classes/tailwind-grid-auto-rows/)
  - [Tailwind Grid Auto Flow](https://www.devwares.com/tailwindcss/classes/tailwind-grid-auto-flow/)
  - [Tailwind Grid Column Start/End](https://www.devwares.com/tailwindcss/classes/tailwind-grid-column/)
  - [Tailwind Grid Row Start/End](https://www.devwares.com/tailwindcss/classes/tailwind-grid-row/)
  - [Tailwind Grid](https://www.devwares.com/tailwindcss/classes/tailwind-grid/)
  - [Tailwind CSS Hyphens](https://www.devwares.com/tailwindcss/classes/tailwind-hyphens/)
  - [Tailwind Height](https://www.devwares.com/tailwindcss/classes/tailwind-height/)
  - [Tailwind CSS Invisibility](https://www.devwares.com/tailwindcss/classes/tailwind-invisible/)
  - [Tailwind CSS Justify Content](https://www.devwares.com/tailwindcss/classes/tailwind-justify-content/)
  - [Tailwind CSS Justify-items](https://www.devwares.com/tailwindcss/classes/tailwind-justify-items/)
  - [Tailwind CSS Justify Self](https://www.devwares.com/tailwindcss/classes/tailwind-justify-self/)
  - [Tailwind CSS Letter-spacing](https://www.devwares.com/tailwindcss/classes/tailwind-letter-spacing/)
  - [Tailwind CSS Line Clamp](https://www.devwares.com/tailwindcss/classes/tailwind-line-clamp/)
  - [Tailwind CSS Line-height](https://www.devwares.com/tailwindcss/classes/tailwind-lineheight/)
  - [Tailwind CSS List Style Position](https://www.devwares.com/tailwindcss/classes/tailwind-list-style-position/)
  - [Tailwind CSS List Style Type](https://www.devwares.com/tailwindcss/classes/tailwind-list-style-type/)
  - [Tailwind CSS Max-Height](https://www.devwares.com/tailwindcss/classes/tailwind-max-height/)
  - [Tailwind CSS Min-Height](https://www.devwares.com/tailwindcss/classes/tailwind-min-height/)
  - [Tailwind Margin](https://www.devwares.com/tailwindcss/classes/tailwind-margin/)
  - [Tailwind CSS Max-Width](https://www.devwares.com/tailwindcss/classes/tailwind-max-width/)
  - [Tailwind CSS Min-Width](https://www.devwares.com/tailwindcss/classes/tailwind-min-width/)
  - [Tailwind CSS Object Position](https://www.devwares.com/tailwindcss/classes/tailwind-object-positions/)
  - [Tailwind CSS Object Fit](https://www.devwares.com/tailwindcss/classes/tailwind-object-fit/)
  - [Tailwind CSS Opacity](https://www.devwares.com/tailwindcss/classes/tailwind-opacity/)
  - [Tailwind CSS Order](https://www.devwares.com/tailwindcss/classes/tailwind-order/)
  - [Tailwind CSS Overflow](https://www.devwares.com/tailwindcss/classes/tailwind-overflow/)
  - [Tailwind CSS Overscroll Behaviour](https://www.devwares.com/tailwindcss/classes/tailwind-overscroll-behaviour/)
  - [Tailwind Padding](https://www.devwares.com/tailwindcss/classes/tailwind-padding/)
  - [Tailwind CSS Place-content](https://www.devwares.com/tailwindcss/classes/tailwind-place-content/)
  - [Tailwind CSS Place-items](https://www.devwares.com/tailwindcss/classes/tailwind-place-items/)
  - [Tailwind CSS Place-self](https://www.devwares.com/tailwindcss/classes/tailwind-place-self/)
  - [Tailwind CSS Position](https://www.devwares.com/tailwindcss/classes/tailwind-position/)
  - [Tailwind CSS Rotate](https://www.devwares.com/tailwindcss/classes/tailwind-rotate/)
  - [Tailwind CSS Scale](https://www.devwares.com/tailwindcss/classes/tailwind-scale/)
  - [Tailwind CSS Screen Reader](https://www.devwares.com/tailwindcss/classes/tailwind-screen-readers/)
  - [Tailwind CSS Skew](https://www.devwares.com/tailwindcss/classes/tailwind-skew/)
  - [Tailwind CSS Stroke Width](https://www.devwares.com/tailwindcss/classes/tailwind-stroke-width/)
  - [Tailwind CSS Stroke](https://www.devwares.com/tailwindcss/classes/tailwind-stroke/)
  - [Tailwind CSS Text Color](https://www.devwares.com/tailwindcss/classes/tailwind-text-color/)
  - [Tailwind CSS Text Decoration Style](https://www.devwares.com/tailwindcss/classes/tailwind-text-decoration-style/)
  - [Tailwind CSS Text-align](https://www.devwares.com/tailwindcss/classes/tailwind-text-align/)
  - [Tailwind CSS Text Decoration Thickness](https://www.devwares.com/tailwindcss/classes/tailwind-text-decoration-thickness/)
  - [Tailwind CSS Text Decoration](https://www.devwares.com/tailwindcss/classes/tailwind-text-decoration/)
  - [Tailwind CSS Transform Origin](https://www.devwares.com/tailwindcss/classes/tailwind-transform-origin/)
  - [Tailwind CSS Text Indent](https://www.devwares.com/tailwindcss/classes/tailwind-text-indent/)
  - [Tailwind CSS Transform](https://www.devwares.com/tailwindcss/classes/tailwind-transform/)
  - [Tailwind CSS Translate](https://www.devwares.com/tailwindcss/classes/tailwind-translate/)
  - [Tailwind CSS Vertical Align](https://www.devwares.com/tailwindcss/classes/tailwind-vertical-align/)
  - [Tailwind CSS Whitespace](https://www.devwares.com/tailwindcss/classes/tailwind-whitespace/)
  - [Tailwind CSS Width](https://www.devwares.com/tailwindcss/classes/tailwind-width/)
  - [Tailwind CSS Word Break](https://www.devwares.com/tailwindcss/classes/tailwind-word-break/)
  - [Tailwind Border Color](https://www.devwares.com/tailwindcss/classes/tailwind-border-color/)

Thank you!
