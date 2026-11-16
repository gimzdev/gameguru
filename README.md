<h1 align="center">GameGuru</h1>

<p align="center">In-game overlay · in development</p>


GameGuru will show what you would otherwise alt-tab for, on top of the game: frame rate, temperatures, ping and a
few widgets of your own. It will draw in its own transparent window instead of hooking into the game, and it will
stay out of sight until you press its hotkey.

In development: there is no release yet, and this repository holds no code yet.

## Planned features

- **Performance.** FPS, 1% lows and frame times, CPU and GPU load, GPU temperature, VRAM and ping.
- **Widgets.** Clock, timers, counters, notes and what's playing, each on a hotkey.
- **Layouts.** Drag any widget anywhere. Each game gets its own layout, applied when it starts.
- **Style.** One line or a small panel, with your font, size, colours and opacity.
- **Footprint.** A few megabytes, no account and no telemetry. Settings live in one JSON file.

## Planned stack

Rust and Tauri for the app, React and TypeScript for its interface.

- **Overlay.** Its own window over games in borderless or windowed mode, the default for most games. Exclusive full screen would mean injecting into the game, which GameGuru won't do.
- **Readings.** Frame times from PresentMon's event tracing, GPU readings from the NVIDIA and AMD libraries, and CPU temperature from HWiNFO or LibreHardwareMonitor when one is running.

## Licence

Public domain under [CC0 1.0](LICENSE).

<p align="center"><sub><a href="https://www.gimzdev.com/?utm_source=github">Gimz</a> · <a href="https://github.com/gimzdev/grimoire">Grimoire</a> · <a href="https://github.com/gimzdev/metaforge">MetaForge</a> · <a href="https://github.com/gimzdev/patchlab">Patchlab</a> · <a href="https://github.com/gimzdev/mosaik">Mosaïk</a> · <a href="https://github.com/gimzdev/dropdate">Dropdate</a></sub></p>
