RouteLab: Flashpoint V5 scan viewer (experimental)

FILES
- index.html: Web viewer with orbit and manual pinning of blue holds / grey blocks
- V5 in the bay - Flashpoint.glb: Original 3D scan

HOW TO RUN
1. Create a new GitHub repository, e.g. routelab-v5.
2. Upload index.html and the GLB file to repository root. Keep GLB filename unchanged.
3. Enable GitHub Pages (Settings > Pages > Deploy from branch > main / root).
4. Open the Pages URL on your iPhone. An internet connection is required to load the Three.js libraries from jsDelivr.
5. Orbit to inspect the wall. Tap Mark hold, choose blue or grey, then tap the surface to add a numbered pin. Switch back to Orbit mode to navigate.
6. Add movement notes. Export route JSON regularly to back up your annotations.

NOTES
- Does NOT automatically identify route holds, start/finish holds, or propose beta.
- Geometry and scale are approximate; incomplete captured areas remain in the original scan.
- Pin numbers are insertion order, not necessarily climbing sequence.
- Notes and pins are stored only in the browser's localStorage and may be cleared by Safari.
- Original scan may contain people or gym details; only host it publicly with permission.
- Static demo, not yet tested on your exact iPhone/Safari combination.
