# HackSoc socials video

This is a 40 second promo video for telling freshers about HackSoc's regular social events.

## How to render this video

1. Start cloning this repo (it's a bit chunky so might take a minute or two)

2. Install blender (2.76 if possible, 2.78c should work too)
 * https://download.blender.org/release/

3. Open `video_new.blend` in blender

4. Configure GPU rendering for maximum performance
 * https://docs.blender.org/manual/en/dev/render/cycles/gpu_rendering.html

5. Play the animation to check that it works
 * The play button is at the bottom of the screen
 * Take care to check that the fluid simulation works (the pint glass filling with beer) as this depends on a cache that is checked-in to the git repo.
 * Take care to check that the soft-body simulation of the lose film on the film reels works correctly as this also depends on a checked-in cache.
 * Also check that the font is correctly loaded for all of the text elements in the animation (Roboto slab, as per this: https://www.fontsquirrel.com/fonts/roboto-slab)

6. Render!
 * Press CTRL-F12 to initiate the render. This should [after much rendering] create a file called `hacksoc_vieo.mp4`
