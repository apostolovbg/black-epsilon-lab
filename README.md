# Black Epsilon Lab

**Black Epsilon Lab** is my private precision engineering & AI lab in Sofia, Bulgaria — a ~50 m² space that combines a small machine shop, metrology and microscopy, custom power & network infrastructure, and a dev corner for software and AI-assisted work.

> Built end-to-end by one person: electricals, drywall, plumbing, finishing, lighting design, machine layout, and tooling.

<p align="center">
  <!-- Replace these filenames with the actual ones from docs/images -->
  <img src="docs/images/shop-overview-1.jpg" width="45%" alt="Shop Overview 1"/>
  <img src="docs/images/shop-overview-2.jpg" width="45%" alt="Shop Overview 2"/>
</p>

---

## 🏠 Layout

- **Location:** Sofia, Bulgaria  
- **Owner:** Apostol Valentinov Apostolov (**Black Epsilon Ltd.**)  
- **Area:** ~50 m² total:
  - Front **office** (street-level, light blue walls) with desk and visitor chair
  - Main **shop / lab** (white walls, tiled floor, machines and benches)
  - Small **storage/service** area
  - **Bathroom**

The shop is intentionally finished as a **white-walled lab**, not a greasy garage: clean surfaces, tiled floor, bright ceiling panels, proper lighting, and everything on solid benches.

---

## 🧰 Capabilities

### 1. Machining & Fabrication

The lab is set up for small, precise, one-off or short-run work rather than heavy production.

- **Manual machining**
  - Bench **lathe** – turning, facing, boring, simple threading
  - Bench **mill** – slotting, drilling, light milling operations
  - **Drill press** / column drill

- **Small CNC**
  - Desktop **CNC router** (originally an engraver) for:
    - 2.5D machining
    - Engraving in metals and plastics
    - Light routing / pattern work

- **Sheet metal & finishing**
  - Small **press brake** / bending tools
  - Mechanical **press**
  - **Belt + disc sander** and other finishing tools

- **General tools**
  - Multiple heavy red/grey benches
  - Vises, clamps, files, saws, hand tools
  - Oxy-based gas equipment for cutting/welding

Focus: **precision parts and fixtures** — adapters, bushings, spacers, brackets, housings — where geometry and fit matter more than volume.

---

### 2. Metrology & Measurement

A dedicated metrology corner allows proper verification instead of “by eye” guessing.

- **Surface plate** on its own stand
- **Gauge blocks** and reference blocks
- Digital and dial **calipers**
- **Micrometers** (outside, depth, etc.)
- **Dial indicators** with magnetic bases (standard and articulated arms)
- Parallels, 1-2-3 blocks, angle gauges, levels and other layout tools

Typical use cases:

- Checking dimensions and runout on turned parts
- Verifying flatness/squareness on milled faces
- Aligning setups and fixtures before cutting

<p align="center">
  <!-- Replace filename -->
  <img src="docs/images/metrology-corner.jpg" width="60%" alt="Metrology Corner"/>
</p>

---

### 3. Microscopy & Inspection

A separate station is dedicated to visual inspection and materials/geometry observation:

- **Zeiss Laboval 4** microscope with:
  - 40×, 100×, 400×, 1000× objectives  
    (higher magnifications are oil-immersion)
- Camera mounted in the eyepiece
- Dedicated computer for live view and image capture
- Mounted on a **stainless steel table** in a clean corner of the lab

Typical uses:

- Inspecting **tool wear** and cutting edges
- Examining **surface finishes**, cracks, and defects
- Looking at contamination or micro-features on parts
- Capturing images for **failure analysis** and documentation

<p align="center">
  <!-- Replace filename -->
  <img src="docs/images/microscope-station.jpg" width="60%" alt="Microscope Station"/>
</p>

---

### 4. Power, Electrical & Lighting

The infrastructure was designed and installed entirely by hand:

- **Power**
  - 50 A / 240 V supply
  - Distribution panel on the shop wall
  - New circuits and outlets routed around the room (channels cut in the drywall, then closed, replastered and painted)

- **Lighting**

  Carefully zoned lighting to avoid the classic “single blinding lamp” workshop:

  - Bright overhead LED panels:
    - Zone for the **lathe & mill** bench
    - Zone for the **window-side** wall and general-purpose bench
  - Low-intensity 5 W lights for:
    - Comfortable evening presence
    - Screen work without glare
  - Directed task lighting:
    - Spot for the **surface plate**
    - Spot for the **main GP bench**
  - **Hidden LED strips** along tool walls above benches for extra local light

In the **front office**:

- One warm (3000 K) and one neutral (4000 K) light on the ceiling, for both relaxed and focused work.

Result: you can light just the area you’re working in — from “surgical bright over the machine” to “soft ambient while watching something”.

---

### 5. Water & Cleanup

- Large **ceramic sink** with proper drainage
- Storage around the sink for cleaning agents and consumables
- Tools and brushes for parts and machine cleanup

This keeps the space closer to “lab clean” than “oil pit” and makes it realistic to do fine work and inspection.

---

### 6. Network & Computing

There is a small but capable network and computing setup:

- **Rack**
  - 16U rack
  - Rack switch
  - PDU
  - Legacy rack server (currently unused due to length, kept as spare/experimental hardware)

- **Workstations**
  - PC for the microscope station
  - Dev/office PC in the front room
  - PC / screen in the shop
  - TV on the shop wall for diagrams, docs, visualisations

- **Network design**
  - Segmented lab network, **inspired by zero-trust**
  - Separation between machine/control traffic, office/dev traffic, and external connectivity

This ties into my software work (e.g. the Copernican Suite) and lets me run simulations, data analysis, and instrumentation control from the same physical environment.

---

## 🧪 What This Lab Is For

Black Epsilon Lab is not a production factory. It’s a **precision workshop and experimentation space**.

Typical things it’s good at:

- One-off **precision parts** and small batch runs
- **Fixtures and jigs** for experiments or repairs
- **Measurement and inspection** of parts where tolerances actually matter
- Experiments that combine **hardware** and **software/simulation**
- Using AI tools to help design, diagnose and document real-world setups

---

## 🧱 How It Was Built

This is not just “I put some machines in a room” — the room itself is a project.

- Found and fixed the **external cause** of a water-damaged wall
- Cut out and replaced **soaked drywall** with water-resistant board
- Routed new **electrical channels** around the perimeter and installed outlets
- Closed everything with filler, replastered, primed and painted in white alkyd
- Replaced the **ceiling grid panels**, repainted the grid, installed new LED lighting
- Built a **separating wall** and installed a reclaimed door between office and shop
- Installed plumbing and the large **ceramic sink**
- Designed bench and machine layout for realistic workflows

All done solo, learning multiple trades (electrical, drywall, masonry, finishing) along the way.

---

## 🧠 Philosophy

Black Epsilon Lab exists to bridge:

- **Physical reality** – metal, glass, tools, fixtures, chips, coolant, measurements  
- **Abstract structure** – equations, simulations, software like the Copernican Suite  
- **Human cognition** – languages, AI, and the urge to understand and build

Most of the “architecture” for the room lived in a **whiteboard and in my head** — informal CAD with real-world feedback. Formal CAD is for parts and fixtures; the space itself was iterated in full scale.

> TL;DR: I use my head as my favourite CAD software.

---

## 🔗 Related Projects

- **Copernican Suite** – cosmological inference and model-comparison framework  
  <https://github.com/apostolovbg/copernican>

- **Profile & other work**  
  <https://github.com/apostolovbg>

---

## 📸 More Photos

To keep the main README readable, additional images can live in `docs/images/` and be referenced from here or from a dedicated `docs/` page.

