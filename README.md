# react-3d-fluid — Coming Soon

react-3d-fluid will be a React-friendly WebGL library implementing 3D Navier–Stokes based fluid simulations and shaders for interactive UIs, art, and scientific visualization.

Status
- Project status: Coming soon — repository created and ready for initial development and publish.
- NPM package name reserved: react-3d-fluid

Goals / What to expect
- A lightweight, tree-shakeable set of React components and hooks to run 3D Navier–Stokes fluid simulations on the GPU via WebGL.
- Utilities for simulation setup (domain, boundary conditions), rendering helpers, and shader examples.
- Example apps and benchmarks demonstrating performance and integration with React.

Planned API surface (early)
- <FluidCanvas /> — React component that hosts the WebGL simulation and renderer.
- useFluidSimulation(options) — hook to control simulation parameters and step the solver.
- shader presets and helpers for common visual styles.

Publishing / Claiming the package name
- Repository prepared for publishing. Ensure package.json has "private": false and "publishConfig": { "access": "public" }.
- To publish:
  1. Build the distribution into `dist/`.
  2. Update version in package.json (for first public release use e.g. `0.1.0`).
  3. Run `npm publish`.

Repository
- Repository URL: https://github.com/hieroglyphica/react-3d-fluid
  (Replace with a different URL only if you want a different owner.)

License
- This project will be published under the MIT license (see package.json license field). Add a LICENSE file before publishing if you want the full text in repo.

Contributing
- Contributions, issues and PRs are welcome once the repository is public. Please include reproducible examples for any bug reports.

Contact / Notes
- Replace the repository and author fields in package.json with your own information before publishing.
- Add examples and a demo page (gh-pages or Vercel) for a public showcase when ready.
