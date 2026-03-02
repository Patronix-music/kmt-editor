Live site is at https://patronix-music.github.io/kmt-editor/

# KMT Editor

Standalone HTML editor for NI Kontrol S-Series MK3 MIDI template files (`.kmt`).

This tool allows you to:

- Create and edit `.kmt` templates
- Configure knobs (absolute, relative, offset)
- Configure buttons (toggle, gate, trigger, incremental, fixed)
- Edit Pitch Wheel, Mod Wheel, Touchstrip, and Keyzones
- Add artwork banners (1280×212, distortion-free)
- Import / Export `.kmt`
- Scan PDF manuals for MIDI CC tables
- Maintain a drag-and-drop MIDI CC library

No backend. No installation. Runs fully offline in the browser.

---

## Usage

1. Download the latest HTML file.
2. Open it in a modern browser (Chrome, Edge, Safari).
3. Start editing or import an existing `.kmt`.

Everything runs locally. No data is uploaded anywhere.

---

## Features

### Pages
- Up to 16 pages
- 8 knobs + 8 buttons per page
- Drag & drop reordering

### Knobs
- Absolute (custom range)
- Relative
- Relative Offset
- Multiple display modes (Integer, %, Bipolar, dB)

### Buttons
- Toggle
- Gate
- Trigger
- Fixed value
- Incremental (step + wrap)

### Performance Controls
- Pitch Bend (full 0–16383 range)
- Mod Wheel (CC / Pitch / Program Change)
- Touchstrip (CC / Pitch / Program Change)
- Keyzone configuration

### MIDI Library
- JSON import
- PDF scan (regex-based, offline)
- Drag & drop assignment

---

## License

This project is licensed under the MIT License.

You are free to:
- Use
- Modify
- Distribute
- Use commercially

As long as the original copyright notice is included.

See the `LICENSE` file for details.

---

## Disclaimer

This tool is an independent utility and is not affiliated with or endorsed by Native Instruments.
