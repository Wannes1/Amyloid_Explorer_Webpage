# Amyloid Landscape Explorer

React + TypeScript web app for exploring amyloid graph data with Cosmograph.

## Prerequisites

- Node.js
- npm

## Run Locally

1. Install dependencies:

   npm install

2. Start the local dev server:

   npm run dev

3. Open the app:

   http://localhost:8000

The dev command bundles with esbuild, serves the project from the repository root, and writes build artifacts to `dist`.

## Production Build

Run:

npm run build

This creates the production bundle in dist.

## Available Scripts

- npm run dev: Start local server with sourcemaps.
- npm run build: Create production bundle in dist.

## Data Files

- data/thermodynamics_nodes_merged_with_description.csv
- data/thermodynamics_edges.csv
- data/multiple_alignments/
- data/stamp_b_factor_residue_pdbs_corrected/

The app loads the two thermodynamics CSV files at startup and uses the other data folders for linked images and structure files when you select nodes.
