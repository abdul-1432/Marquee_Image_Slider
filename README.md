# Marquee Image Slider


Marquee Image Slider is a lightweight and customizable image slider library for your web projects. It provides an elegant way to showcase a collection of images in a smooth and visually appealing manner. With Marquee Image Slider, you can easily create captivating image sliders to enhance the user experience on your website.

## Features

- **Responsive Design:** Marquee Image Slider adapts to various screen sizes, ensuring a seamless viewing experience on both desktop and mobile devices.

- **Smooth Transitions:** Enjoy smooth and eye-catching image transitions that captivate your audience and make your images stand out.

- **Customization Options:** Customize the slider's appearance, transition effects, navigation controls, and more to match your website's design and style.

- **Keyboard and Touch Support:** Users can navigate through the slider using keyboard shortcuts and touch gestures for increased accessibility.

- **Auto-play:** Enable auto-play mode to automatically cycle through images at a specified interval, creating a dynamic slideshow effect.

- **Thumbnail Navigation:** Provide thumbnail images below the main slider for quick navigation to specific slides.

## Getting Started

1. Include the Marquee Image Slider CSS and JavaScript files in your HTML:

   ```HTML
   <link rel="stylesheet" href="path/to/marquee-slider.css">
   <script src="path/to/marquee-slider.js"></script>
   ```

2. Create an HTML element to hold the slider:

   ```HTML
   <div class="marquee-slider">
       <!-- Your slide images will go here -->
   </div>
   ```

3. Initialize the Marquee Image Slider:

   ```html
   <script>
       const slider = new MarqueeImageSlider('.marquee-slider', {
           // Configuration options here
       });
   </script>
   ```

## Configuration Options

- `images`: An array of image URLs to be displayed in the slider.
- `transition`: The type of transition effect (e.g., fade, slide, zoom).
- `autoplay`: Enable or disable auto-play mode.
- `autoplayInterval`: The interval between slide transitions in auto-play mode.
- `Show thumbnails`: Display thumbnail navigation below the slider.
- `thumbnail size`: The size of the thumbnail images.
- ... (additional customization options)

## Example

```javascript
const slider = new MarqueeImageSlider('.marquee-slider', {
    images: [
        'image1.jpg',
        'image2.jpg',
        'image3.jpg',
        // Add more image URLs here
    ],
    transition: 'slide',
    autoplay: true,
    autoplay interval: 5000,
    show thumbnails: true,
    thumbnails: 80
});
```

## Contributions

Contributions are welcome! If you find a bug or have suggestions for improvements, please submit an issue or a pull request to the [GitHub repository](https://github.com/abdul-1432/Marquee_Image_Slider).

## License

Marquee Image Slider is licensed under the [MIT License](LICENSE).

---

Feel free to use Marquee Image Slider to create stunning image sliders that engage your website, visitors. We hope you enjoy using this library! If you have any questions or need assistance, please don't hesitate to contact us at (contact@example.com)[mailto:gafoor.mngr@gmail.com].
