# Menu images: Best Corner Bar & Resto

Photos for the menu items in the abydash export (197 items).

- `images/`: 93 images, JPEG, max 1000px on the longest side, named by dish or product (`images/fanta.jpg`, `images/goat-brochette.jpg`, ...).
- `menu-images.json`: every menu item (`id`, `name`, `category`) with its `image` path, or `null` if no image was found yet. Some items also have `altImages`: extra photos of the same dish.
- `CREDITS.md`: the source and licence of each image.

## How the images were chosen

- **Branded drinks** (beers, sodas, spirits, wines) are product photos from Open Food Facts. Where possible they are the Rwandan (Bralirwa) bottles, e.g. Mützig, Heineken, Amstel, Agahozo, Virunga, Gilbey's, Rack Gin, K-Vant and Bazooka.
- **Dishes** are freely licensed photos from Wikimedia Commons, except matoke, boiled potato, Rolex, chicken wings, vegetable soup and spaghetti bolognese, whose photos the owner supplied. They show the same kind of dish, not plates from this restaurant. Several menu items share one image, e.g. all the ugali/kawunga plates.

## Items still without an image (29)

Amstel Bock, Primus, Legend, Gatanu, Turbo King, Virunga Mist/Silver, Panaché, EXO, Glory, Goldberg, Konyagi (all sizes), Golon B, Four Cousins, Drostdy-Hof 5L, Red Wine 5L, Domaine Bel, Tabalish, house red/white wine, Wine pichet, Intore, mayonnaise, take-away.

To add one, drop the photo in `images/` and set its `image` in `menu-images.json`.
