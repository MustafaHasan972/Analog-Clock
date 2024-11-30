# Analog Clock

An aesthetically pleasing **Analog Clock** implemented using HTML, CSS, and JavaScript. This project demonstrates the functionality of a real-time analog clock with animated clock hands and dynamic updates every second. The design features a glowing effect and creative styling for the clock face and hands.

---

## Features

- **Real-Time Updates**: The clock displays the current time with smooth transitions for the hour, minute, and second hands.
- **Stylish Design**: A modern and vibrant glowing effect makes the clock visually appealing.
- **Dynamic Hour Markers**: Numeric hour indicators dynamically generated with JavaScript.
- **Second Ticks**: Detailed bar markers for seconds are dynamically created.
- **Animation Effects**: Background hue rotation provides a colorful and interactive design.

---

## File Structure

### 1. `index.html`

- Defines the structure of the analog clock, including:
  - `div.wrapper`: Container for the clock elements.
  - `div.bar-seconds`: Displays second ticks around the clock.
  - `div.number-hours`: Holds numeric hour markers.
  - `div.hands-box`: Contains the clock hands (hour, minute, and second).

### 2. `style.css`

- Handles the visual styling, including:
  - Layout and positioning of clock components.
  - Glowing effects for hands and markers.
  - Keyframe animation for the rotating background hue.

### 3. `app.js`

- Implements the functionality:
  - Dynamically generates hour numbers and second markers.
  - Calculates the position of the clock hands based on the current time.
  - Updates the clock hands every second to reflect real-time changes.

---

## How to Run

1. Clone or download the repository.
2. Open the `index.html` file in a web browser to view the analog clock in action.

---

## Customization

### Colors and Effects

- Modify the `background` property in `body` or `wrapper` in `style.css` to change the background color.
- Adjust the glowing effects by tweaking the `box-shadow` property in `style.css`.

### Clock Size

- Change the `width` and `height` properties in `.wrapper` and `.hands-box` in `style.css` to resize the clock.

---

## Future Improvements

- Add support for a digital time display below the clock face.
- Include options to switch between 12-hour and 24-hour formats.
- Implement themes for light and dark modes.

---

## Credits

Codehal
