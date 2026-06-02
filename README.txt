This folder contains a static website reconstructed from the uploaded MATLAB figure `bias_valida_barotro_filter.fig`.

Files:
- index.html : public webpage
- grid_data.csv : reconstructed gridded field (x, y, value)
- scatter_points.csv : scatter points extracted from the figure

How to publish publicly:
1. Upload this folder to Netlify Drop or GitHub Pages.
2. Share the resulting public URL.

Notes:
- The scatter-point values come directly from the .fig file.
- The colored background field is reconstructed from the truecolor surface saved inside the figure using the stored colormap and color limits, so it is an approximation of the original gridded values.
