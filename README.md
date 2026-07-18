# 26-0 faces

Player photos for the **26-0** AFL draft game, served free over the [jsDelivr](https://www.jsdelivr.com/) CDN.

This repo is deliberately **public** so the photos can be hosted — it contains only images, no game code.

## Photo URL format

```
https://cdn.jsdelivr.net/gh/D-260-AFL/26-0-faces@main/faces/<Player_Name>.webp
```

Spaces in a player's name become underscores, and apostrophes/hyphens are stripped or turned into underscores. Examples:

- Jordan de Goey → `faces/Jordan_de_Goey.webp`
- Nasiah Wanganeen-Milera → `faces/Nasiah_Wanganeen_Milera.webp`
- Connor O'Sullivan → `faces/Connor_OSullivan.webp`

## Adding a new photo

1. Name the file after the player using the rules above.
2. Drop it in the `faces/` folder and commit.
3. New files can take up to 12 hours to appear on the CDN. To force one immediately, visit:
   `https://purge.jsdelivr.net/gh/D-260-AFL/26-0-faces@main/faces/<Player_Name>.webp`
