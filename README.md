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


## Midjourney Tips and Trick

### Instructions:

- Choose your subject: Think about the person or character you want to create an image of. It could be a celebrity, a historical figure, a fictional character, or even yourself.
- Imagine the scene: Envision a setting that reflects the personality or traits of your subject. Is it a peaceful meadow, a bustling city street, or a fantastical kingdom?
- Describe the details: Use descriptive language to paint a picture of your subject in the scene. What are they wearing? What's their facial expression? Are there any objects or creatures around them?
- Specify camera settings: Select the camera and lens you want to use, and set the aperture, ISO, and shutter speed to capture the image the way you envision it.
- Choose the aspect ratio: Decide on the aspect ratio that best suits your image.
- Adjust the quality and visual settings: Choose the quality and visual settings that best suit your needs.
- Generate the image: Once you've specified all the details, use the midjourney AI image generator to bring your vision to life.

**Example 1:**

  - Subject: A mermaid
  - Scene: A rocky shore at sunset
  - Details: `The mermaid has long, flowing hair and iridescent scales that shimmer in the sun. She's perched on a rock, looking out at the ocean, with a seagull perched on her shoulder. In the background, there are crashing waves and a glowing orange sun setting on the horizon.`
  - Camera: `Nikon D850 paired with a Nikon 85mm f/1.4G lens`
  - Settings: `Aperture of f/2.8, ISO 400, shutter speed of 1/125 sec`
  - Aspect Ratio: `16:9`
  Quality and Visual Settings: `--q 3.5 --v 5`

**Example 2:**

  - Subject: Albert Einstein
  - Scene: A laboratory filled with scientific equipment
  - Details: Einstein is wearing a lab coat and holding a test tube, peering intently at the liquid inside. There are beakers, flasks, and other scientific equipment scattered around the room, along with books and papers. A   - chalkboard in the background is covered in equations and diagrams.
  - Camera: Canon EOS R6 paired with a Canon EF 85mm f/1.2L II USM lens
  - Settings: Aperture of f/2.8, ISO 800, shutter speed of 1/250 sec
  - Aspect Ratio: 4:3
  - Quality and Visual Settings: --q 3.0 --v 4

These examples demonstrate how the midjourney AI image generator can be used to bring to life unique and imaginative visions. By following the instructions and carefully specifying the details, you can create stunning and personalized images that capture your subject's spirit and energy.



## Examples:

Imagine a world where humans can communicate with animals. Create a stunning photograph that captures the wonder and magic of this world. In the photograph, a young girl stands in a lush forest, surrounded by a group of animals. The girl has an ethereal quality, with a flowing white dress and a crown of flowers on her head. She is smiling warmly, and her eyes sparkle with a sense of joy and wonder. The animals are all different species, ranging from a majestic eagle to a tiny squirrel. They all gaze at the girl with a sense of reverence and affection. The photograph is taken with a Canon EOS R camera, paired with a Canon RF 50mm f/1.2L USM lens, renowned for its exceptional sharpness and beautiful bokeh. The camera settings are carefully chosen to capture every detail of the scene, with an aperture of f/2.8, ISO 400, and a shutter speed of 1/125 sec. The background is a soft, dreamy forest environment, with dappled sunlight filtering through the trees. The lighting is expertly crafted to accentuate the magical quality of the scene, with soft, diffused light adding to the overall atmosphere. This stunning and imaginative photograph captures the spirit and energy of a world where humans and animals can connect and communicate, while celebrating the beauty and wonder of nature. --ar 4:3 --q 2.5 --v 5 

![abracadabra_Imagine_a_world_where_humans_can_communicate_with_a_745e5e45-fa77-448d-b725-5c07db70290d](https://user-images.githubusercontent.com/34073221/231800498-bf1a578f-dda6-40cc-8697-6eaab1b506a3.png)


Imagine a future where robots have taken over all manual labor. Create a stunning photograph that captures the power and majesty of these machines. In the photograph, a group of robots stand on a barren landscape, their metal bodies gleaming in the harsh sunlight. They are all different sizes and shapes, but they all exude a sense of strength and power. Some are carrying heavy loads, while others are using their powerful arms to move boulders or clear debris. The photograph is taken with a Nikon D850 camera, paired with a Nikon AF-S NIKKOR 70-200mm f/2.8E FL ED VR lens, renowned for its exceptional sharpness and beautiful bokeh. The camera settings are carefully chosen to capture every detail of the scene, with an aperture of f/4, ISO 800, and a shutter speed of 1/250 sec. The background is a desolate, rocky environment, with no signs of life except for the robots. The lighting is expertly crafted to accentuate the strength and power of the machines, with strong shadows and bold highlights enhancing the overall atmosphere. This stunning and imaginative photograph captures the spirit and energy of a world where robots have taken over all manual labor, while celebrating the incredible capabilities of these machines. --ar 3:2 --q 2.5 --v 5 

![abracadabra_Imagine_a_future_where_robots_have_taken_over_all_m_b38bd0e5-e888-4722-880a-ac5cb34ae9e3](https://user-images.githubusercontent.com/34073221/231809911-d678fd46-8553-4cde-b1ac-d470b459d010.png)


A mesmerizing portrait of Dwayne "The Rock" Johnson reimagined as a god-like figure from ancient mythology, with rippling muscles and an imposing presence that exudes power and strength. He is depicted wearing a regal, golden armor adorned with intricate designs and symbols, with a majestic cape flowing behind him. His face is adorned with markings and tattoos that signify his divine status, and his eyes glow with an otherworldly intensity. The photograph is taken with a Nikon D850 camera, paired with a Nikkor 24-70mm f/2.8 lens, renowned for its exceptional sharpness and versatility. The camera settings are carefully chosen to capture every detail of the scene, with an aperture of f/5.6, ISO 400, and a shutter speed of 1/250 sec. The background is a mystical and ethereal landscape, with celestial bodies and swirling clouds adding to the sense of awe and wonder. The lighting is expertly crafted to accentuate the god-like qualities of The Rock, with dramatic shadows and highlights enhancing the overall atmosphere. This stunning and imaginative photograph captures the spirit and energy of ancient mythology, while celebrating the charisma and magnetism of Dwayne Johnson as a modern-day icon. --v 5

![abracadabra_A_mesmerizing_portrait_of_Dwayne_The_Rock_Johnson_r_de3616e2-60ab-4b0d-b02a-d1fc70d22c90](https://user-images.githubusercontent.com/34073221/231809991-e1842dab-139e-4cc2-aaca-429a17a6525e.png)

A spellbinding portrait of Beyoncé reimagined as a fierce warrior queen, with a regal bearing and a commanding presence that exudes strength and confidence. She is depicted wearing a custom-designed armor that blends elements of traditional African and modern styles, with a bold color scheme and intricate details that reflect her unique style and identity. Her face is adorned with tribal markings and golden accents that emphasize her regal status, and her eyes blaze with a fiery intensity that speaks to her fierce determination and resilience. The photograph is taken with a Canon EOS R5 camera, paired with a Canon RF 85mm f/1.2 lens, renowned for its exceptional sharpness and beautiful bokeh. The camera settings are carefully chosen to capture every detail of the scene, with an aperture of f/2, ISO 800, and a shutter speed of 1/200 sec. The background is a dynamic and vibrant landscape, with elements of both natural and urban environments blending together in a seamless and harmonious way. The lighting is expertly crafted to accentuate the power and grace of Beyoncé, with soft, diffused light enhancing the overall atmosphere. This stunning and imaginative photograph captures the spirit and energy of modern-day royalty, while celebrating the talent and charisma of Beyoncé as a true icon of our time. --ar 3:2 --q 2.5 --v 5

![abracadabra_A_spellbinding_portrait_of_Beyonce_reimagined_as_a__e4fae5d0-9ce8-4a9b-ac1b-c371743ff468](https://user-images.githubusercontent.com/34073221/231810354-01642e56-1594-4c2e-b0c0-5ecebb7fe4cf.png)


A striking portrait of the President of South Korea, reimagined as a heroic figure from ancient Korean mythology. The President is depicted in a regal pose, dressed in traditional Korean robes and wielding a powerful sword with intricate designs. His face is painted with striking patterns, representing the ancient symbols of power and wisdom. The photograph is taken with a Canon EOS R5 camera, paired with a Canon RF 85mm f/1.2L USM lens, renowned for its exceptional image quality and bokeh. The camera settings are carefully chosen to capture every detail of the scene, with an aperture of f/2.8, ISO 400, and a shutter speed of 1/125 sec. The background is a majestic mountain landscape, with misty clouds and dramatic lighting adding to the overall atmosphere. This stunning and imaginative photograph captures the spirit and heritage of Korean mythology, while celebrating the leadership and strength of the President of South Korea. --ar 4:3 --q 2.5 --v 5

![abracadabra_A_striking_portrait_of_the_President_of_South_Korea_0539e2b0-f421-4d44-a178-ac9f048f2c1e](https://user-images.githubusercontent.com/34073221/231810486-ca33ccdd-1795-4fe7-8f2e-21b77da59d29.png)

A dramatic portrait of the President of Mexico, reimagined as a fearless outlaw riding into the sunset on a majestic stallion. The President is depicted in a rugged and adventurous pose, dressed in cowboy attire and armed with a revolver and a shotgun. His face is rugged and determined, reflecting the bravery and courage of a true Western hero. The photograph is taken with a Nikon Z7 II camera, paired with a Nikkor Z 85mm f/1.8 S lens, renowned for its sharpness and bokeh. The camera settings are carefully chosen to capture every detail of the scene, with an aperture of f/4, ISO 800, and a shutter speed of 1/250 sec. The background is a sweeping desert landscape, with the warm colors of the sunset casting a golden glow over the scene. This stunning and imaginative photograph captures the spirit and romance of the Old West, while celebrating the charisma and leadership of the President of Mexico. --ar 3:2 --q 2.5 --v 5

![abracadabra_A_dramatic_portrait_of_the_President_of_Mexico_reim_4b1d04e2-1f01-433a-9344-3edbefbbdae7](https://user-images.githubusercontent.com/34073221/231811477-0d6d7a9f-dd04-4bc6-a832-d03deb913fcb.png)


A breathtaking portrait of Elon Musk reimagined as a visionary explorer, pushing the boundaries of space and technology. Musk stands at the helm of a sleek and futuristic spaceship, his hand on the controls, gazing out into the vast expanse of the cosmos with a sense of awe and wonder. He wears a custom-designed spacesuit, featuring a black and white color scheme with red accents, reflecting his bold and daring spirit. The background is a stunning vista of stars and galaxies, with shimmering nebulas and cosmic dust clouds adding to the sense of mystery and adventure. The photograph is taken with a Nikon Z7 II camera, paired with a Nikkor Z 50mm f/1.2 S lens, renowned for its sharpness and beautiful bokeh. The camera settings are carefully chosen to capture every detail of the scene, with an aperture of f/2.8, ISO 800, and a shutter speed of 1/200 sec. The lighting is expertly crafted to accentuate the futuristic and otherworldly quality of the scene, with a cool, blue light adding to the overall atmosphere. This stunning and imaginative photograph captures the spirit of Elon Musk's relentless pursuit of innovation and exploration. --ar 16:9 --q 2.5 

![abracadabra_A_breathtaking_portrait_of_Elon_Musk_reimagined_as__19e29a8e-e9db-4a43-978b-f0e6572dc41b](https://user-images.githubusercontent.com/34073221/231811811-d1840f8a-8357-4a9d-b09a-40ab732a1c81.png)

