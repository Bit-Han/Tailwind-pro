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

- [](https://www.devwares.com/blog/create-animation-with-tailwind-css/)
- [Tailwind grid-How to use tailwind CSS grid templates in your project](https://www.devwares.com/blog/how-to-add-tailwind-css-grid-to-your-project/)
- [How to create a Beautiful Responsive Navigation bar Using Tailwind CSS](https://www.devwares.com/blog/how-to-create-a-beautiful-responsive-navbar-using-tailwind-css/)
- [Tailwind form-How to create and style a Responsive Form using Tailwind CSS](https://www.devwares.com/blog/how-to-create-and-style-a-responsive-form-using-tailwindcss/)
- [Tailwind CSS Flex: How to use Tailwind CSS Flex](https://www.devwares.com/blog/how-to-use-tailwind-css-flex/)
- [How to use tailwind css padding, margin and border in your project.](https://www.devwares.com/blog/how-to-use-tailwind-css-padding-margin-and-border-in-your-project/)
- [Tailwind CSS CDN-How to use the Tailwind CSS JIT CDN](https://www.devwares.com/blog/how-to-use-the-tailwind-css-JIT-CDN/)
- [How to set up your first Tailwind CSS Project](https://www.devwares.com/blog/setting-up-your-first-project-using-tailwind-css/)
- [How to use Tailwind CSS in HTML](https://www.devwares.com/blog/how-to-use-tailwind-css-in-HTML/)
- [Tailwind CSS table-How to Create Tailwind CSS tables](https://www.devwares.com/blog/how-to-create-tailwind-css-tables/)

Thank you!
