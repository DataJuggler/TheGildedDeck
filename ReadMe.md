# The Gilded Deck

![The Gilded Deck](preview-placeholder.png)  
*(Preview gallery coming soon after the initial push)*

**Please enjoy these cards** — I worked really hard to create them.

This is a complete 52-card deck plus 4 back color images with a luxurious gilded aesthetic. 

### Preview
*(Image grid or embedded gallery will go here)*

**All 56 cards** will be displayed in a clean grid below once the repo is public.

---

## How They Were Made

Most of the images were generated with **ChatGPT Images 2** in Comfy UI. While the AI produced beautiful base
artwork, it created inconsistencies across the deck — varying fonts, symbol sizes, and positions.

To bring everything together into a cohesive style, I used my own tools:

- **[DataJuggler.PixelDatabase](https://github.com/DataJuggler/PixelDatabase)** — my NuGet package for pixel-level image manipulation. For this project I added new features including drawing text upside down and rotating images. I also wrote `FindFirstVisiblePixel()` and `FindFirstNonWhitePixel()` specifically to handle the deck's needs.

- **[Isolator](https://github.com/DataJuggler/Isolator)** — another new open-source project of mine that makes it easy to isolate objects from transparent backgrounds.

**Grok** (from xAI) helped me build a **Marching Ants selector** tool that simplified isolating and refining the images.
** Claude ** also helped with some graphics programming help. Most of the credit goes to
** CHatGPT Images 2 ** in ** Comfy UI **

I spent about **$10 on Comfy UI credits** to generate high-quality face cards and card backs.

---

These images are **completely free to use** in any project — commercial or personal. No attribution required, though it's always appreciated.

If you like the deck, please leave a star on this repo and drop a link if you use the cards in your own work. 
It helps more people discover the project!

Thanks for stopping by — I hope The Gilded Deck brings some elegance to your games, projects, or collections.

Corby / Data Juggler