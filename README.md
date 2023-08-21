# 3D Toggle Switch
This project showcases a 3D toggle switch created using HTML and CSS. The toggle switch is designed with a unique 3D appearance, and it features interactive animations that respond to user interactions.

## Features
* <b>Interactive Toggle:</b> The toggle switch provides visual feedback when interacted with. It smoothly transitions between the on and off states.

* <b>3D Appearance:</b> The switch components are designed to create a 3D effect using gradient backgrounds, shadows, and animations.

* <b>Customizable Colors:</b> The hue of the toggle switch and its accent color can be easily adjusted by modifying the CSS variables.

## Usage
To use the 3D toggle switch in your project, follow these steps:
1. Include the provided `style.css` stylesheet in your HTML file's `<head>` section:
```html
<link rel="stylesheet" href="style.css">
```
2. Place the following HTML code in the `<body>` of your HTML file:
```html
<label class="switch">
  <input type="checkbox" checked />
  <div class="indicator left"></div>
  <div class="indicator right"></div>
  <div class="button"></div>
</label>
```
3. Customize the switch appearance by adjusting the CSS variables defined in the `style.css` file. You can modify colors, dimensions, and other properties according to your preferences.
```css
/* Example: Change the hue of the switch */
:root {
  --hue: 140deg;
}
```
4. Save both the HTML and CSS files in the same directory and open the HTML file in a web browser to see the 3D toggle switch in action.

## License
This project is licensed under the MIT License.

Feel free to use, modify, and distribute this code as needed while adhering to the terms of the MIT License.

## Preview
<img width="893" alt="Screenshot 2023-08-21 103810" src="https://github.com/Aarzoo75/3D-Toggle-Switch/assets/59678435/3a633c52-d368-4d7e-bd78-258478f47962">

<hr>

Designed and implemented by [Aarzoo](https://twitter.com/Aarzoo75). Inspired by various creative designs on the web.

For more details, enhancements, and contributions, visit the GitHub repository.

If you find this project helpful, consider giving it a ⭐ on GitHub!
