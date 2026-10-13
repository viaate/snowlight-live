# snowlight-live

This repository will host the live school-closings file for Snowlight Map
(snowlightmap.com). The file is published to GitHub Pages by a GitHub Actions
workflow and the map reads it from there.

Right now it only holds a timing test: a workflow that publishes `probe.json`
(a counter and a timestamp, nothing else) so we can measure how quickly a new
file becomes visible on GitHub Pages. There is no school data here yet.
