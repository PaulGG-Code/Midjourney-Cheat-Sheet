# Midjourney-Cheat-Sheet

## Midjourney Parameter List Cheatsheet

### Basic Parameters

    --aspect or --ar: Change the aspect ratio of a generation. Eg: --ar 2:3
        --ar 1:1 Default aspect ratio.
        --ar 5:4 Common frame and print ratio.
        --ar 3:2 Common in print photography.
        --ar 7:4 Close to HD TV screens and smartphone screens.
    --chaos <number 0–100>: Change how varied the results will be. Higher values produce more unusual and unexpected generations.
    --no: Negative prompting, remove plants from the image.
    --quality <.25, .5, 1, or 2> or --q <.25, .5, 1, or 2>: How much rendering quality time you want to spend. The default value is 1. Higher values cost more and lower values cost less.
    --seed <integer between 0–4294967295>: The Midjourney bot uses a seed number to create a field of visual noise, like television static, as a starting point to generate the initial image grids. Seed numbers are generated randomly for each image but can be specified with the --seed or --sameseed parameter. Using the same seed number and prompt will produce similar ending images.
    --stop <integer between 10–100>: Use the --stop parameter to finish a Job partway through the process. Stopping a Job at an earlier percentage can create blurrier, less detailed results.
    --style <4a, 4b or 4c>: Switch between versions of the Midjourney Model Version 4
    --stylize <number> or --s <number>: Parameter influences how strongly Midjourney’s default aesthetic style is applied to Jobs.
    --uplight: Use an alternative “light” upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image is less detailed and smoother.
    --upbeta: Use an alternative beta upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image has significantly fewer added details.

Model Version Parameters

    --niji: An alternative model focused on anime style images.
    --hd: Use an early alternative Model that produces larger, less consistent images. This algorithm may be suitable for abstract and landscape images.
    --test: Use the Midjourney special test model.
    --testp: Use the Midjourney special photography-focused test model.
    --version <1, 2, 3, 4 or 5> or --v <1 2, 3, 4 or 5>: Use an earlier version of the Midjourney algorithm. The current algorithm (V5) is the default setting.

Upscaler Parameters

    --uplight: Use an alternative “light” upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image is less detailed and smoother.
    --upbeta: Use an alternative beta upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image has significantly fewer added details.
    --upanime: Use an alternative upscaler trained to work with the --niji Midjourney Model.

Other Parameters

    --creative: Modify the test and testp models to be more varied and creative.
    --iw: Sets image prompt weight relative to text weight. The default value is --iw 0.25.
    --sameseed: Seed values create a single large random noise field applied across all images in the initial grid. When --sameseed is specified, all images

### Image Generation Cheatsheet

Here are some common styles of image generation and their characteristics:

| Style | Description |
| ----- | ----------- |
| 8k | Lighting tends to be more extreme; colors even more saturated and computer-generated looking than "high definition" |
| cinematic | Shadows tend to be more extreme (though not darker); objects a bit thicker; more poster-like |
| high definition | Shadows are lightened; more fanciful and saturated colors |
| ultra photorealistic | Similar to "fine ultra-detailed realistic" |
| Hasselblad H6D | Sharper focus on subject; shadows are deepened |
| fine ultra-detailed realistic | Can be a bit grainy and "ropey" but increases detail generation |
| color grading | Extreme variations in hue; vibrant but not over-saturated colors |
| depth of field | Sharp focus on subject, background and foreground blurred |
| film lighting | Limited lighting sources; backlighting common; deep shadows cast by light sources |
| rim lighting | Slightly stronger lighting effect than "film lighting," but very similar results |
| intricate | Tends toward non-realistic "crafts" and "pattern" type designs. |
| realism | Artistic realism. Backgrounds tend to be more uniform; subject looks more like a painting; more objects with subject |
| photography | Subject tends to have a little area of objects around it with little else in the background |
| rendered for IMAX | More complex subject with very directional lighting and subdued saturation |
| tilt-shift | Like "depth of field," but from above or with high angle |
| motion-blur | Speed lines. May render as if wind is blowing |
| 35mm film | More vibrant colors, but muted saturation, detailed with additional foreground and/or background elements |
| synthwave | An electronic music microgenre that is based predominantly on the music associated with action, science-fiction, and horror film soundtracks of the 1980s |
| duotone |  Illustration made from a single original with two different colours at different screen angles |
| 1990s point and click 16bit adventure game | An amazing 16 bit game 1990's style |
| 32-bit isometric | 32-bit pixel art |
| diagramatic drawming | A plan, sketch, drawing, or outline designed to demonstrate or explain how something works or to clarify the relationship between the parts of a whole. |
| watercolor sketch | watercolor work that's completed quickly, with a loose, informal style |
| stained glass window | glass that has been coloured and cut into various shapes to form pictures or patterns, used especially in church windows |
| patchwork collage | a layering fabric for the design as an art style quilt |
| op art | Or Optical art, it use shapes, colours and patterns in special ways to create images that look as if they are moving or blurring. |
| colorful | having much or varied colour; bright |
