# HackSoc socials video

This is a 40 second promo video for telling freshers about HackSoc's regular social events.

## How to render this video

1. Install blender (2.76 if possible, 2.78c should work too)
 * https://download.blender.org/release/

2. Open `video_new.blend` in blender

3. Configure GPU rendering for maximum performance
 * https://docs.blender.org/manual/en/dev/render/cycles/gpu_rendering.html

4. Play the animation to check that it works
 * The play button is at the bottom of the screen
 * Take care to check that the fluid simulation works (the pint glass filling with beer) as this depends on a cache that is checked-in to the git repo.
 * Take care to check that the soft-body simulation of the lose film on the film reels works correctly as this also depends on a checked-in cache.

5. Render!
 * Press CTRL-F12 to initiate the render. This should [after much rendering] create a file called `hacksoc_vieo.mp4`
