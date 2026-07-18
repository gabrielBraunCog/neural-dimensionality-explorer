# Neural Dimensionality Explorer

An interactive, browser-based tool for exploring neural dimensionality with PCA.

## Features

- Within-participant PCA: neural-state dimensionality across time
- Full-feature dual PCA: all parcels contribute without constructing a parcel-by-parcel covariance matrix
- Between-participant PCA: dimensions separating participants
- Participation ratio and variance-threshold measures
- Sliding-window analysis
- Multiple-participant data
- CSV, TSV, JSON, MATLAB `.mat`, NumPy `.npy`, and `.npz` input
- Local browser processing: uploaded neural data are not sent to a server
- Visible calculation progress for group and sliding-window analyses
- Responsive, cancelable recalculation when arrays, participants, modes, windows, or thresholds change

## Publish with GitHub Pages

1. Create a new public repository named `neural-dimensionality-explorer`.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.

The public site will appear at:

https://gabrielbrauncog.github.io/neural-dimensionality-explorer/

## Data organization

Assign the three input dimensions to time, neural features, and participants inside the explorer. For multiple 2D table files, rows are Dimension 1, columns are Dimension 2, and the sequence of files is Dimension 3.
