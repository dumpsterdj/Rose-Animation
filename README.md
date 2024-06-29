# Rose Animation

A beautiful animated rose created using pure HTML and CSS.

## Features

- **Pure CSS Animation:** The rose is animated using only CSS keyframes and transitions.
- **Detailed Styling:** Various parts of the rose, including petals, leaves, and thorns, are styled to give a realistic appearance.
- **Responsive Design:** The animation is centered and adapts to different screen sizes.

## Getting Started

### Prerequisites

- A modern web browser to view the animation.
- Basic understanding of HTML and CSS (optional, if you want to modify the code).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dumpsterdj/rose-animation.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd rose-animation
   ```
3. **Open `index.html` in your web browser:**
   ```bash
   open index.html
   ```

### File Structure

- `index.html`: The main HTML file containing the structure of the rose animation.
- `styles.css`: The CSS file with all the styles and animations for the rose.

### Customization

Feel free to customize the animation by editing the `styles.css` file. You can change colors, sizes, and animations to suit your preferences.

### CSS Breakdown

Here's a quick overview of how the different parts of the rose are styled and animated:

- **Petals:** Positioned using absolute coordinates and animated with keyframes to simulate blooming.
- **Leaves:** Styled with gradients and positioned to look natural.
- **Thorns:** Created using CSS borders to mimic the sharp look of thorns.
- **Background and Text:** Simple styling for the background and any additional text you might want to add.

### Keyframe Animations

The petals are animated to simulate blooming using keyframes like `@keyframes bloom2`, `@keyframes bloom3`, etc. These animations control the rotation, position, and color changes over time.

Example of a bloom animation:
```css
@keyframes bloom2 {
  50% {
    transform: rotate(-90deg);
    top: 200px;
    left: 100px;
  }
  100% {
    transform: rotate(-60deg);
    top: 252px;
    left: 50px;
    background: #45199d;
    box-shadow: 0px 0px 0px rgba(148, 163, 245, 0.5);
  }
}
```

### Contributing

If you have suggestions for improving the animation or want to report a bug, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

Created by [dumpsterdj](https://github.com/dumpsterdj).

## Acknowledgments

- Inspired by the beauty of nature and the potential of CSS animations.
- Fonts by [Google Fonts](https://fonts.google.com/).
