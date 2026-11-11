# get-fed-map
Interactive map of Get Fed food spots. Open https://bw-95.github.io/get-fed-map/ and tap **Find me** to see what's near you.

## Customising

- **Logo**: upload your logo as `logo.png` in the top folder of this repo (square works best). It shows in the header and as the pin for spots whose dish type isn't recognised. Until then a 🍽️ plate is used.
- **Colours**: change the `--brand` colours near the top of the `<style>` block in `index.html`.
- **Food icons**: the `DISHES` list in `index.html` matches words in each spot's name to an icon (e.g. "laksa" → 🍜, "burger" → 🍔). Add a line there to teach it a new dish.
- **Photos**: tapping a spot shows the episode thumbnail from YouTube and a photo of that kind of dish from Wikipedia. Neither needs an API key. The "Food photos (Google)" button opens Google Images for that stall.
