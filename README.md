# CSS Tooltip Navigation - Pure CSS Implementation

<!-- ![Project Screenshot](screenshot.png) -->

## Overview

This project showcases a navigation menu with CSS-only tooltips that appear above navigation items on hover without any JavaScript dependency.

## Project URL

[https://roadmap.sh/projects/tooltip-ui](https://roadmap.sh/projects/tooltip-ui)

## Demo

<!-- ![Gallery Preview](.screenshot.png) -->

> **Live Demo:** [https://nurf21.github.io/tooltip-ui/](https://nurf21.github.io/tooltip-ui/)

## Features

- **Pure CSS implementation**: No JavaScript required
- **Responsive design**: Works on various screen sizes
- **Modern UI elements**:
  - Gradient backgrounds
  - Smooth hover effects
  - Tooltip arrows for visual connection

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/nurf21/tooltip-ui
   ```
2. Open `index.html` in any modern browser
3. Hover over the navigation items to see different tooltip animations

## Implementation Details

The tooltips are created using these CSS techniques:

1. **Positioning**:
   - `position: absolute` for tooltips relative to navigation items
   - `bottom: calc(100% + 15px)` to position above the item
   - `left: 50%` and `transform: translateX(-50%)` for horizontal centering

2. **Animations**:
   - `transition` properties for smooth hover effects
   - `opacity` and `visibility` for fade effects
   - `transform` properties for movement and scaling

3. **Tooltip Arrow**:
   - Created with CSS borders
   - Positioned absolutely at the bottom of the tooltip

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.