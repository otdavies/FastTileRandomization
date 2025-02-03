# Dual-Point Texture Tiling Demo

Interactive demonstration of a texture tiling technique that uses dual-point rotation blending to create seamless textures with reduced repetition artifacts.

[Try Demo](https://otdavies.github.io/DualPointTiling/)

![chrome_Th3zh0hmF5](https://github.com/user-attachments/assets/03bda29e-e974-4295-a8ba-60bae50437ba)


## How it works
The algorithm uses two reference points (corners and centers) to create random rotations of the texture, then blends between them based on distance. This creates a more natural-looking tiling pattern that reduces the obvious repetition typically seen in tiled textures.

![example](https://github.com/user-attachments/assets/d463cfaa-2bfc-43c7-937d-1fe3a5e87bd0)

## Controls
- Rotation: Controls the maximum rotation amount
- Blend Falloff: Adjusts how sharply the algorithm transitions between rotated sections
- Blend Offset: Modifies the center point influence
- Scale: Adjusts the tiling scale
