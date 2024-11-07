
# football-icons

A curated collection of football team logos in SVG format — plus the CSS for easier integration into your web pages. See the demo for examples.

## Usage

To use the football icons in your project, first import the CSS:

```html
<link rel="stylesheet" href="/path/to/football-icons/css/football-icons.min.css" />
```

For using the icons inline with text, add the classes `.football-icon` and `.football-icon-xx` (where `xx` is the team code) to an empty `<div>` element. Example:

```html
<div class="football-icon football-icon-uc-sampdoria"></div>
```

This will display the logo of the specified football team. You can apply this to any element, and it will set the correct background properties for you:

```css
background-size: contain;
background-position: 50%;
background-repeat: no-repeat;
```

Make sure to set the appropriate size for the icon, typically in a 4:3 ratio for proper scaling.

## Development

After cloning the project, install the dependencies:

```bash
yarn
```

Then you can build the project and serve it locally:

- To build `.scss` files:

  ```bash
  yarn build
  ```

- To serve it on `localhost:8000`:

  ```bash
  yarn start
  ```

If you only need specific teams in the CSS file, you can remove unnecessary icons from the `_football-icons-list.scss` file and rebuild it.

## Credits

A huge thank you to **Lipis** for the inspiration and for creating the amazing `flag-icons` library that served as the foundation for this project. Lipis's work at [lipis.dev](https://lipis.dev) continues to inspire developers like me.

```
