# awesome-nano-banana

A curated list of **Nano Banana** (officially *Gemini 2.5 Flash Image Preview*) use-cases, prompts, and sources.  
This model excels at **natural-language image editing**, **identity/likeness consistency**, **multi-step edits**, and **multi-image blending**.

- **Official updates:** Google Product Blog — “Nano Banana! Image editing in Gemini just got a major upgrade” (Aug 26, 2025).  
  https://blog.google/products/gemini/updated-image-editing-model/  
  https://blog.google/intl/en-mena/product-updates/explore-get-answers/nano-banana-image-editing-in-gemini-just-got-a-major-upgrade/
- **Developers:** “Introducing Gemini 2.5 Flash Image (aka nano-banana)” — Google Developers Blog.  
  https://developers.googleblog.com/en/introducing-gemini-2-5-flash-image/

> **Try it**: Gemini App / Google AI Studio / Vertex AI (when available in your region); or community blind tests such as LMArena.

## Overview

Nano Banana is a powerful image-editing model known for consistent identity preservation across edits, object insertion, pose and gaze adjustments, multi-image blending, and multi-turn edits. This README provides reproducible prompts used in community examples and articles.

## Table of Use-Cases (Full prompts included)

| # | Use-case summary (short) | Full prompt | Source |
|---|---|---|---|
| 1 | Add a third dog-food bag matching the other two | "Add a third bag of dog food in the cart the same as the other two." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 2 | Make the subject look straight ahead | "Create a photo of someone looking straight ahead." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 3 | Create a four-panel sports montage matching a reference style | "Create a 4-panel montage showing sporting moments. Use the style of the reference image." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 4 | Merge two photos into a selfie in a park | "Take those two photos and make it look like they’re taking a selfie in a park." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 5 | Turn the subject’s face toward the camera | "Turn a person’s face toward the camera." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 6 | Insert or replace a product while matching its texture | "Replace a product in the photo (e.g., add another bag with matching pattern)." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 7 | Swap objects in a scene without breaking realism | "Perform object replacements (before/after). Keep realism." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 8 | Change a person’s outfit (e.g., new clothes or profession) | "Replace the subject’s clothes — put them in a new outfit or profession." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 9 | Generate a 4-panel b-roll montage of actions | "Provide a 4-panel montage of b-roll footage of this subject, 16:9: 1) standing outside (back to camera) 2) getting into the driver seat 3) driving the car 4) walking away after the drive." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 10 | Replace brand logos in a product photo | "Replace the brands in the photo." | https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/ |
| 11 | Add a logo and a prop to a folder | "Put a Google logo and a banana on her folder." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 12 | Remove an unwanted person from a group photo | "Remove the unwanted person from the team photo." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 13 | Swap attributes between people (race swap example) | "Swap the races of the couple." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 14 | Convert a photo into Studio Ghibli-style animation | "Make it Ghibli styled." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 15 | Dress subjects in formal James Bond-style outfits | "Dress them up for James Bond." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 16 | Enhance a subject's musculature | "Make this person more muscular." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 17 | Generate a full head of hair | "Give me a head of beautiful hair." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 18 | Add formal hair and facial hair | "Give me formal hair with a full mustache." | https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/ |
| 19 | Role-reversal: dog walking a human | "A dog walking a man on a leash." | https://jzcreates.com/blog/how-to-use-googles-nano-banana-easy-tutorial/ |
| 20 | Bikini model with headphones and soda | "A bikini model drinking a soda with headphones on." | https://jzcreates.com/blog/how-to-use-googles-nano-banana-easy-tutorial/ |
| 21 | Add a surfer riding on a river | "Add a surfer riding on the river." | https://jzcreates.com/blog/how-to-use-googles-nano-banana-easy-tutorial/ |
| 22 | Costume or location change for a subject | "Put yourself in a new outfit or profession (costume or location change)." | https://blog.google/products/gemini/updated-image-editing-model/ |
| 23 | Blend photos (person + pet) into new composition | "Blend your photo with your dog’s photo to create a portrait on a basketball court." | https://blog.google/products/gemini/updated-image-editing-model/ |
| 24 | Multi-turn room edits (paint, furnish) | "Paint the walls, then add a bookshelf and furniture." | https://blog.google/products/gemini/updated-image-editing-model/ |
| 25 | Design mixing: transfer color/pattern between objects | "Apply flower-petal colors to rainboots or create a dress using butterfly-wing patterns." | https://blog.google/products/gemini/updated-image-editing-model/ |
| 26 | Turn a game screenshot into a character figure on a tiger | "Please turn this screenshot of the game character into a character figure riding on an Asian tiger. Behind it, place a PlayStation game box printed with the character’s image and the game title 'Black Myth: Zhong Kui.' Next to it, add a computer with its screen displaying the in-game scene, complete with the game's UI and the character. In front of the game box, add a round plastic base for the figure and have it stand on it. The PVC material of the base should have a crystal-clear, translucent texture, and set the entire scene indoors." | https://news.qq.com/rain/a/20250823A064HW00 , https://x.com/ZHO_ZHO_ZHO/status/1958896319524663781 |
| 27 | Generate a realistic 1/7-scale commercial figure inside a display cabinet | "Create a highly realistic 1/7 scale commercialized figure based on the illustration’s adult character, ensuring the appearance and content are safe and appropriate. Render the figure in a detailed, lifelike style and environment, placed on a shelf inside an ultra-realistic figure display cabinet, mounted on a circular transparent acrylic base without any text. Maintain precise texture, material, and paint detail. Use natural, adaptive lighting and a shallow depth of field with slightly blurred figures on neighboring shelves to enhance depth." | https://linux.do/t/topic/901564 |
| 28 | Remodel into a high-end collectible resin figure | "Remodel the character into a top-tier collectible resin figure in a dynamic full-body pose, placed on a character-themed base; high-precision materials with hand-painted finish, realistic skin textures and clothing fabrics. Use dramatic hard lighting as the primary source, with strong fill light to preserve detail. Background should include a shallow-depth-of-field window and faint product packaging box. Aim for museum-grade photographic quality with precise facial structure." | https://linux.do/t/topic/901564 |
| 29 | Create a realistic East-Asian cosplay photo on a Tokyo street | "Generate a realistic East-Asian female cosplayer, age-appropriate, maintaining the subject’s clothing and pose. Place an easel behind her displaying the original image. Set the scene on an empty street in Tokyo, preserving lifelike skin and fabric textures; the composition should be people-centered with the subject occupying most of the frame." | https://linux.do/t/topic/901564 |
| 30 | Embed subject into first-person fast-food POV scene | "Take an immersive first-person snapshot as if taken with an iPhone 15 Pro. I am sitting in a fast-food restaurant facing the subject across the table eating French fries. Keep the subject’s pose; show restaurant lighting, blurred background patrons, food wrappers, and a condensation-covered drink. Ensure the subject receives consistent lighting and interacts physically with the table and food." | https://linux.do/t/topic/901564 |
| 31 | Banana cosplay costume editing | "Let this person wear a Nano Banana cosplay costume." | https://linux.do/t/topic/901564 |
| 32 | Minecraft-style cozy interior | "Minecraft style, high resolution, clear pixel details; a warm and cozy wooden cabin interior with rain-blurred windows, bookshelves, potted plants, and warm lights. A blocky character sits at a wooden desk playing on a computer. Use another image as the monitor content." | https://linux.do/t/topic/901564 |
| 33 | Minecraft post-rain morning with reflections | "Minecraft style, ultra-high resolution. Third-person close-up: after morning rain, the character stands on a grassy plain looking upward; distant pixel forest and misty mountains are clear. Foreground puddles reflect sky colors and morning glow with realistic reflections. Overall soft, transparent lighting." | https://linux.do/t/topic/901564 |

## Reproduction Notes

- Use concise, structured prompts. Break scene, lighting, material, pose, and camera into short sentences.
- For multi-step edits, apply changes iteratively preserving identity consistency.
- When using brands, public figures, or copyrighted works, obtain necessary rights for reuse or commercial use.

## Contribution

Pull requests are welcome. Add new items to the table with a reproducible full prompt and a public source link.

## Further Reading

- https://blog.google/products/gemini/updated-image-editing-model/
- https://developers.googleblog.com/en/introducing-gemini-2-5-flash-image/
- https://www.bgr.com/1947324/nano-banana-ai-image-generator-10-examples/
- https://felloai.com/2025/08/what-is-google-nano-banana-heres-how-you-can-test-it/
- https://jzcreates.com/blog/how-to-use-googles-nano-banana-easy-tutorial/

## License

This document is licensed under CC-BY-SA 4.0.
