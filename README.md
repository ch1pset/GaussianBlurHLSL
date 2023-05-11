# GaussianBlurHLSL
A simple gaussian blur for use with OBS Studio using Custom Effects plugin

## Custom Effect (required)
https://obsproject.com/forum/resources/custom-effect.871/

## Instructions
Load `gaussian_blur.effect` using the Custom Effect filter for a source or scene.

To adjust blur, open `gaussian_blur.effect` with a text or code editor and adjust the paramters at the top.

- NUM_SAMPLES - Number of samples taken
- BLUR_AMOUNT - Adjusts size of blur offset, a higher offset may require higher samples
- RES_X - Horizontal source resolution
- RES_Y - Vertical source resolution

Using a lower resolution than source may improve performance, but lowers the quality of the blur.
