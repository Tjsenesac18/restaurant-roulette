# Restaurant Roulette

Pick your places. Spin your dinner.

An installable mobile web app with 200 starter restaurants in 20 categories, search, custom restaurant names and photos, and a colorful wheel. Choices stay selected for repeat spins. Reset Wheel clears the selection without deleting restaurants.

## Run locally on Windows

No build or dependencies are required. With Python installed, run `python -m http.server 8000` in this folder and open http://localhost:8000 on the laptop. iPhone installation requires an HTTPS hosted address.

## Publish on GitHub Pages

These files belong in the repository root. In Settings → Pages, select Deploy from a branch, main, and / (root), then Save. GitHub provides the live address after deployment. Free Pages hosting normally requires a public repository.

## Add to iPhone

Open the live address in Safari. Tap Share → Add to Home Screen, enable Open as Web App if offered, and tap Add. Open once online to prepare offline mode. Maps and new brand icons require internet.

## Data and backup

Selections and custom restaurants are saved on the device in IndexedDB. Photos are compressed. Use the information button to export or import a JSON backup. When moving to a different website address, export from the old app and import into the new one; data does not transfer automatically.

## Wheel behavior

Uniform cryptographic random selection with rejection sampling chooses a winner. The rotation places that segment under the fixed arrow. Selections are preserved after each spin.

## Brand artwork

Restaurant icons load online and fall back to initials. They are not a verified set of official logos. Trademarks belong to their owners. This independent picker does not check hours or nearby availability.
