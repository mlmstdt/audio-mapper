# Audio Cartographer

Client-side tool for visualizing audio as a 2D map. Upload audio, segment it by onsets, extract features, reduce to 2D, click dots to listen. Runs entirely in the browser.

## Usage

- Upload one or more audio files, or a whole folder
- Adjust onset detection sensitivity and segment length
- Pick which features to extract (RMS, ZCR, spectral centroid, MFCCs, chroma, etc.)
- Pick a dimensionality reduction method (t-SNE, PCA, or UMAP)
- Hit Analyze & Map
- Click any dot on the map to hear that segment
