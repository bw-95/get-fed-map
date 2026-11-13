# get-fed-map
Interactive map of Get Fed food spots. Open https://bw-95.github.io/get-fed-map/ and tap **Find me** to see what's near you.

## Using the map

- **Your spot**: tap **Find me**, pick an MRT station, or **press and hold** anywhere on the map (right-click on a computer). A normal tap just pans, so your spot won't move by accident.
- **Places with several spots**: spots in the same hawker centre, mall or block share one pin with a number on it. Tap it to pick a spot; each spot's details have a "← N spots here" button to go back.
- **Map style**: the layers button under the zoom buttons switches between Streets, Colourful, OneMap (Singapore only), Satellite and Plain. Your choice is remembered.

## Customising

- **Logo**: `logo.png` (the Get Fed mascot) shows in the header, as the browser-tab icon, and as the pin for spots whose dish type isn't recognised. Replace the file to change it.
- **Colours & font**: Get Fed yellow `#f2c744`, orange `#eaa94a` and near-black `#1c1b17`, with Oswald for headlines. Change the `--brand` colours near the top of the `<style>` block in `index.html`.
- **Food icons**: the `DISHES` list in `index.html` matches words in each spot's name to an icon (e.g. "laksa" → 🍜, "burger" → 🍔). Add a line there to teach it a new dish.
- **Photos**: tapping a spot shows the episode thumbnail from YouTube and a photo of that kind of dish from Wikipedia. Neither needs an API key. The "Food photos (Google)" button opens Google Images for that stall.
