## FPS Booster for FiveM Servers

Optimize your FiveM gameplay experience with this easy-to-use FPS Booster script.
Adjust graphical settings dynamically to improve performance on lower-end machines or customize visuals to your liking.

Perfect for servers looking to boost FPS by tweaking shadow, lighting, and entity rendering settings in real-time.

## Features

* [x] Multiple FPS preset modes: Ultra Low, Low, Medium, and Reset to Normal
* [x] Dynamically adjusts shadows, lighting, and entity visibility for performance
* [x] On-demand menu accessible via `/fps` command
* [x] Seamless integration with ESX framework for notifications and menu handling
* [ ] Future updates planned for additional customization options

## How It Works

This client-side script hooks into FiveM’s native functions to alter rendering parameters such as shadows, flashlight distance, entity alpha, and more, based on your selected preset. It also periodically clears certain effects and disables unnecessary visual features to maximize FPS gain.

Using the `/fps` command opens a menu where you select your preferred performance profile. Changes are applied instantly and can be reset anytime.

## Installation

1. Download or clone the repository files.
2. Place the resource folder (e.g., `fps-booster`) inside your FiveM `resources` directory.
3. Ensure your server uses the ESX framework as this script depends on it.
4. Add `start fps-booster` to your `server.cfg`.
5. Launch your server and type `/fps` in-game to access the FPS booster menu.

## Files

* **client.lua**: Contains all logic for rendering adjustments, menu handling, and FPS mode application.
* **fxmanifest.lua**: Defines resource metadata and dependencies.

## Contributing

Contributions are welcome! When submitting a Pull Request (PR), please follow these guidelines:

* For minor fixes like typos, open an issue instead of a PR.
* Avoid irrelevant or spammy PRs.
* Keep changes focused and do not rewrite large parts at once.

## License

This project is licensed under the **MIT License**, allowing free use, modification, distribution, and more, provided that the original copyright and permission notice remain.

The software is provided "as is", without warranties of any kind.

For details, see the [MIT License](https://opensource.org/licenses/MIT).
