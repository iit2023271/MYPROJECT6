# Network Speed Test

Measures your internet download speed by timing how long a test image takes to download, then shows the result in bps, kbps, and Mbps.


## Features

- Downloads a ~5.6 MB test image and times it
- Calculates speed in **bps**, **kbps**, and **Mbps** (rounded to 2 decimals)
- Shows the result in an alert dialog

## Tech Stack

- HTML
- JavaScript (single self-contained file)

## How to Run

Open `index.html` in any browser **with an internet connection**. The test starts automatically and the result appears in an alert dialog.

```bash
# or serve it locally
python3 -m http.server
# then open http://localhost:8000
```

## Notes

The page itself has no visible UI — it is just the test script, so the screenshot is a blank page and the real output is the alert dialog. The test needs the external image URL to be reachable; if that image goes offline, no result appears.
