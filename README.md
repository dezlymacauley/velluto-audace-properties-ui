# Velluto Audace Properties - User Interface
_______________________________________________________________________________
## About

The user interface for a real estate website called
`Velluto Audace Properties`

The following technologies are used:
1. HTML
2. Tailwind CSS
3. Bun (Package Management)
4. Vite (Build Tool)

_______________________________________________________________________________
## Installation instructions

##### Requirements:
- Bun

1. Clone the repo
```sh
git clone https://github.com/dezlymacauley/velluto-audace-properties-ui.git
``` 

2. Enter the directory and use `bun` to install the project dependencies
```sh
cd velluto-audace-properties-ui
bun install
```
_______________________________________________________________________________
Create a `main.css` file in the root of your project

```sh
touch ./main.css
```

Add these lines inside the file:
```css
@import "tailwindcss";
```
_______________________________________________________________________________
Replace the contents of the `index.html` file with this

./index.html
```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="./main.css" rel="stylesheet">
</head>

<body>
  <h1 class="
    bg-purple-700 text-white
    text-3xl font-bold
  ">
    The Maverick Amorist
  </h1>
</body>

</html>
```
_______________________________________________________________________________
