# TRANSIT-NATAL-OVERLAP-CHART
Transit Mixer is a simple, fast, browser-based Vedic astrology tool that overlays transit planets on a natal chart.


LIVE LINK


# Transit Mixer

Transit Mixer is a simple, fast, browser-based Vedic astrology tool that overlays transit planets on a natal chart.

It allows astrologers to visually mix natal and transit positions in a clean, square North-Indian style chart layout.

No installation, no dependencies, and no internet required after download.

---

## Features

- Load natal chart from JSON
- Load transit chart from JSON
- Overlay transit planets on natal chart
- Pivot chart from:
  - ASC
  - Any major planet
- Adjustable house starting point
- Hide minor transit planets
- Hide house cusps
- Retrograde markers
- Clean dark-theme interface
- Fully offline tool

---

## How It Works

1. Load natal JSON file
2. Load transit JSON file
3. The chart displays:
   - Natal planets
   - Transit planets
   - House cusps
   - ASC

Transit planets are shown in cyan color with `T-` prefix.

---

## JSON Format Required

The tool expects JSON in this structure:



{
"ayanamshas": {
"Lahiri": {
"lagna": 123.45,
"cusps": {
"1": 123.45,
"2": 153.45
},
"planets": {
"Surya": 210.5,
"Chandra": 15.3
},
"planets_retro": {
"Saturn": true
}
}
}
}


All degrees must be in **0–360 format**.

---

## How to Use

### Step 1 — Download
Download the HTML file.

### Step 2 — Open
Open the file in any modern browser:
- Chrome
- Edge
- Firefox

### Step 3 — Load Charts
1. Click **LOAD NATAL JSON**
2. Select natal chart JSON
3. Click **LOAD TRANSIT JSON**
4. Select transit chart JSON

---

## Controls

| Control | Function |
|--------|----------|
| Hide Minor | Hides Sun, Moon, Mars, Mercury, Venus from transit |
| Hide Cusps | Hides house cusps |
| Pivot | Sets chart reference (ASC or planet) |
| House Start | Rotates house numbering |

---

## Requirements

- Any modern web browser
- No installation required
- Works fully offline

---

## Project Structure



