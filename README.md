<div align="center">

# GameGuru

Minimal in-game overlay for FPS, temperatures and your own widgets, without touching the game.

Rust · Tauri · React · TypeScript

<img src="https://img.shields.io/badge/In%20development-F59E0B?style=flat-square" alt="In development">


GameGuru shows what you would otherwise alt-tab for, on top of the game: frame rate, temperatures, ping
and a few widgets of your own. It draws in its own transparent window instead of hooking into the game,
so there is nothing for anti-cheat to flag, and it stays out of sight until you press its hotkey.

| | |
|:---|:---|
| **Performance** | FPS, 1% lows and frame times, CPU and GPU load, GPU temperature, VRAM and ping |
| **Widgets** | Clock, timers, counters, notes and what's playing, each on a hotkey |
| **Layouts** | Drag any widget anywhere; each game gets its own layout, applied when it starts |
| **Style** | One line or a small panel, with your font, size, colours and opacity |
| **Footprint** | A few megabytes, no account and no telemetry; settings live in one JSON file |

Frame times come from PresentMon's event tracing, GPU readings from the NVIDIA and AMD libraries, and CPU
temperature from HWiNFO or LibreHardwareMonitor when one is running. It works over games in borderless or
windowed mode, the default for most games. Exclusive full screen would mean injecting into the game, which
GameGuru deliberately doesn't do.

</div>
