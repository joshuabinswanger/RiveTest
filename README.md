# RiveTest

Test for hosting a Rive file and embedding it in a Magnolia site.

**Live page:** https://joshuabinswanger.github.io/RiveTest/

The page shows the RSWS landscape with six hotspots. Clicking a hotspot draws a line to its
illustration and opens it; the small X next to the illustration closes it again.

## Files

- `index.html` loads the Rive file full-screen with the Rive web (canvas) runtime and plays
  `State Machine 1`.
- `assets/RSWS_RiveTest3.riv` is the current export from the Rive editor, with the Final 1
  illustrations embedded.

## Run locally

The `.riv` has to be served over HTTP, not opened as a file:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.
