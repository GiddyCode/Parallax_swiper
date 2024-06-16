# Flutter Parallax Swiper 

## Overview

The Flutter Parallax Swiper is a swiper widget designed to enhance user interface interactions. This widget facilitates the creation of a horizontal swiper that showcases a series of images with mesmerizing parallax scrolling effects. You can tailor its functionality by specifying image URLs, enabling drag-to-scroll, adjusting viewport fractions, modifying padding, fine-tuning the parallax factor, and toggling options for foreground fading and background zoom.

---

Feel free to use or further customize this rephrased version to better suit your needs!


### Example 1: 
Using `ParallaxSwiper` with Default Values (Foreground Fading and Background Zoom Enabled):

```dart
ParallaxSwiper(
  images: [
    'image_url_1.jpg',
    'image_url_2.jpg',
    'image_url_3.jpg',
  ],
)
```
### Example 2: 
Using `ParallaxSwiper` with No Foreground Fading and No Background Zoom:

```dart
ParallaxSwiper(
  images: [
    'image_url_1.jpg',
    'image_url_2.jpg',
    'image_url_3.jpg',
  ],
  dragToScroll: true,
  viewPortFraction: 0.85,
  padding: EdgeInsets.all(16.0),
  parallaxFactor: 10.0,
  foregroundFadeEnabled: false, // Disable foreground image fading.
  backgroundZoomEnabled: false, // Disable background image zooming.
)
```
## Usage
```dart
ParallaxSwiper(
  images: [
    'img1.jpg',
    'img2.jpg',
    'img3.jpg',
  ],
  dragToScroll: true,
  viewPortFraction: 0.85,
  padding: EdgeInsets.all(16.0),
  parallaxFactor: 10.0,
  foregroundFadeEnabled: true,
  backgroundZoomEnabled: true,
)
```
## Configuration Parameters
- `padding (EdgeInsets)`: Define padding for the swiper.
- `parallaxFactor (double)`: Adjust the parallax factor to control scrolling effects.
- `images (List<String>)`: The list of image URLs to display.
- `foregroundFadeEnabled (bool)`: Toggle foreground image fading.
- `backgroundZoomEnabled (bool)`: Toggle background image zoom.
- `dragToScroll (bool)`: Enable or disable drag-to-scroll functionality.
- `viewPortFraction (double)`: Set the viewport fraction for image display.



## Contribution
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to create a pull request.

