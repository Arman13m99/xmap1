# xmap1

## Heatmap Processing

This project now generates heatmap visualizations on the backend using a
Gaussian-smoothed grid. The frontend sliders control the smoothing radius and
grid resolution, which are sent to the server for processing. This provides a
more consistent heatmap with less drastic changes between slider values and
shifts most of the computation to the backend for improved performance.

