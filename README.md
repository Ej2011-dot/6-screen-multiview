Multiview

A video wall for YouTube. Paste up to 6 links and watch them all at once instead of switching between tabs.

Why

Comparing or following multiple videos normally means flipping between browser tabs one at a time. Multiview collapses that into a single screen  everything plays side by side.

How to use
Open index.html (or the live GitHub Pages link) in your browser.
Paste up to 6 YouTube links or video IDs into the box, one per line.
Click Load wall.
Each tile autoplays muted (browser rule)  click sound on on any tile to hear it.
Click remove on a tile to clear that screen, or Clear all to reset everything.
How it works
Extracts the video ID from whatever YouTube link format you paste (youtube.com/watch?v=, youtu.be/, youtube.com/shorts/, or a bare ID).
Builds an embedded YouTube player (<iframe>) for each ID.
Lays the players out in a responsive grid (3 columns on desktop, fewer on mobile).
Autoplay starts muted per browser policy; each tile can be unmuted independently.
Notes
Some videos have embedding disabled by their uploader those won't load no matter what.
Runs entirely in the browser, no build step or dependencies. Just open the HTML file.
