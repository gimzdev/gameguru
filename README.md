<div align="center">

<h1>GameGuru</h1>

<h3>In-game overlay for performance and HUD</h3>

[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org)
[![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)](https://electronjs.org)
[![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white)](https://opengl.org)

<hr>

<h2>About</h2>

<p>GameGuru is an overlay that sits on top of whatever you're playing.<br>
It shows the kind of information you'd normally have to alt-tab for:<br>
frame rate, CPU and GPU load, temperatures, network latency.<br>
Alongside the perf readouts you can put simple custom widgets on screen,<br>
like timers, counters, and short notes.</p>

<p>It stays out of the way by default and lets you turn on only what's useful<br>
for the game you're playing.</p>

<hr>

<h2>Modules</h2>

<table align="center">
<tr>
<td align="center" width="33%">

<h3>Performance</h3>

FPS<br>
CPU/GPU usage<br>
Temps<br>
Latency

</td>
<td align="center" width="33%">

<h3>HUD</h3>

Timers<br>
Counters<br>
Notes<br>
Hotkeys

</td>
<td align="center" width="33%">

<h3>Streaming</h3>

Chat<br>
Alerts<br>
Now playing<br>
OBS

</td>
</tr>
</table>

<hr>

<h2>Config</h2>

```yaml
overlays:
  fps:
    position: top-right
    color: green
    show_graph: true

  timer:
    name: "Ultimate"
    duration: 120
    hotkey: F1
```

<hr>

<h2>Compatibility</h2>

<p>DirectX, OpenGL, Vulkan.<br>
Fullscreen and windowed.<br>
Auto game detection.<br>
One-click install with sensible defaults.</p>

<hr>

<h2>Install</h2>

```bash
curl -L github.com/gimzdev/gameguru/releases/latest/download/gameguru.exe -o gameguru.exe
./gameguru.exe
```

<hr>

[![Download](https://img.shields.io/badge/Download-47848F?style=for-the-badge&logo=download&logoColor=white)](https://github.com/gimzdev/gameguru/releases)

</div>
