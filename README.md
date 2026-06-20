# tek-ms-ds

![npm version](https://img.shields.io/npm/v/tek-ms-ds)
![license](https://img.shields.io/npm/l/tek-ms-ds)

A lightweight **Vanilla TypeScript** design system exposing utility CSS classes and CSS custom properties.

## Installation

```bash
npm install tek-ms-ds
```

## Usage

### Via import (bundler)

```ts
import 'tek-ms-ds/dist/style.css';
```

### Via HTML

```html
<link rel="stylesheet" href="node_modules/tek-ms-ds/dist/style.css" />
```

## Available Classes

### Colors

| Class           | Description                              |
|-----------------|------------------------------------------|
| `.text-primary` | Applies the primary color to text        |
| `.bg-primary`   | Applies the primary color as background  |

## CSS Custom Properties

You can override the design tokens in your own project :

```css
:root {
  --color-primary: #your-color;
}
```

## Example

```html
<p class="text-primary">Hello world</p>
<div class="bg-primary">Hello world</div>
```

## Local Development

```bash
# Install dependencies
npm install

# Start demo
npm run dev

# Build
npm run build
```

## License

MIT


livraisaon

 mise à jour du packge json 
   "version": "v1.0.5",
 npm i
 git add .
 git commit -m "chore:v1.0.5"
git tag v1.0.5
git push origin v1.0.5
