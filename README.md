# Helipad Approach Clear-Angle Visualizer

A simple static HTML/CSS/JavaScript tool for visualizing a helipad-centered approach/departure surface and checking obstacle clearance.

## Run locally

1. Open `/home/runner/work/helipad-approach/helipad-approach/index.html` in a browser.
2. Adjust the inputs:
   - approach/departure horizontal distance
   - clear angle / slope angle
   - obstacle horizontal distance from helipad
   - obstacle actual height
3. The app updates immediately to show:
   - maximum permitted obstacle height at obstacle distance
   - clearance margin and clear/penetration status
   - a side-profile SVG diagram of the helipad, surface, and obstacle

## Assumption

This app uses a simplified geometric model where the approach/departure surface is a straight line rising from the helipad at the configured angle. It is a planning/visualization aid only and not an operationally certified aviation planning system.
