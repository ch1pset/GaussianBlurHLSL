# GaussianBlurHLSL
A simple gaussian blur for use with OBS Studio using Custom Effects plugin

## Custom Effect (required)
https://obsproject.com/forum/resources/custom-effect.871/

## Instructions
Load `gaussian_blur.effect` using the Custom Effect filter for a source or scene.

To adjust blur, open `gaussian_blur.effect` with a text or code editor and adjust the paramters at the top.

- BLUR_SAMPLES - Size of the kernel, keep at 10 or lower for safety
- BLUR_OFFSET_SCALE - The distance between samples
- BLUR_INTENSITY - Amount of blur, diminishing returns after 2.0

Using a lower resolution than source increases blur, but lowers the quality of the blur. Likewise, higher resolution than source increases the quality of the blur.
