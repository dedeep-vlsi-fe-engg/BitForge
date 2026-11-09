# BitForge

**Electronics tools that run in a browser tab.**

BitForge builds browser-based simulators for electronics engineers and students. This repository contains the BitForge website: the home of the BitForge product family, with an introduction to each product and a small set of interactive ECE tools.

**Live site:** https://dedeep-vlsi-fe-engg.github.io/BitForge/

---

## Products

| Product | What it does | Link |
|---|---|---|
| **FPGAForge** | Write Verilog, assign pins with an XDC file, and run designs on pin-accurate models of the Digilent Nexys A7 and AMD Xilinx ZCU102 boards — with waveforms, an oscilloscope, a spectrum analyser, block design and real-time speed control. | https://dedeep-vlsi-fe-engg.github.io/FPGAForge/ |
| **VLSIForge** | Analog IC design in the browser, following the custom-design flow: schematic capture, circuit simulation, layout, DRC, LVS and parasitic extraction (RCX). | https://dedeep-vlsi-fe-engg.github.io/VLSIForge/ |

Both tools are free to use, need no installation, and keep users' designs on their own computers.

## Website contents

- **Chip-floorplan hero** — BitForge drawn as a die with a pad ring; the FPGAForge and VLSIForge blocks are wired to a BitForge core with animated routing, and each block opens its product.
- **Products** — an introduction to FPGAForge and VLSIForge with their key features.
- **ECE bench** — four interactive tools:
  - **Logic gates:** toggle inputs A and B and see AND, OR, XOR, NAND, NOR and XNOR outputs, with the current truth-table row highlighted.
  - **Number bases:** click the bits of a byte to see its decimal, hexadecimal, signed (two's complement), octal and ASCII values.
  - **Ohm's law:** enter any two of voltage, current and resistance to calculate the third, plus power.
  - **Resistor colour code:** choose four bands to read the resistance and tolerance.
- **Milestones** — a timeline of the inventions behind modern electronics, from the transistor (1947) to the first FPGA (1985).
- **About** — the BitForge mission and credits.

## Technology

- A single, self-contained `index.html` file: HTML, CSS and vanilla JavaScript with no frameworks and no build step.
- Logos are embedded in the page as WebP images.
- Fonts: Chakra Petch (headings), IBM Plex Sans (body) and IBM Plex Mono (numbers), loaded from Google Fonts.
- Responsive from mobile to desktop, keyboard accessible, and respects the system's reduced-motion setting.
- No cookies, no tracking and no accounts.

## Repository structure

```
BitForge/
├── index.html   # the complete website
└── README.md    # this file
```

## Deployment

The site is hosted on **GitHub Pages**:

1. Upload `index.html` to the root of the repository.
2. In **Settings → Pages**, choose **Deploy from a branch → `main` → `/ (root)`** and save.
3. GitHub publishes the site at `https://<account>.github.io/BitForge/` within a minute or two.

To update the site, upload a new `index.html` and commit; GitHub Pages republishes automatically. If an old version still appears, refresh with **Ctrl + Shift + R**.

## Browser support

All current versions of Chrome, Edge, Firefox and Safari on desktop and mobile.

## Credits

**BitForge** — designed and developed by **DSS**, engineered with **Claude** by Anthropic.

## License

© 2026 BitForge. All rights reserved.
No part of this website, its code or its logos may be copied, modified or redistributed without permission from BitForge.

FPGAForge and VLSIForge are products of BitForge. Other product and company names mentioned are trademarks of their respective owners.
