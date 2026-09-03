# DARWIN Genetic Algorithm Explorer

An interactive, animated companion to “Application of Genetic Algorithm to DARWIN Core Design Optimisation” by Anže Mihelčič and Luka Snoj (NENE 2026).

The single-page visualization explains:

- the four-region, 12-gene candidate representation;
- coolant-temperature-feedback screening;
- single-objective fitness evaluation;
- elitism and tournament selection;
- one-point crossover and bounded mutation; and
- the paper's two reported best configurations.

## Run locally

Open `dist/index.html` in a modern browser. No build step or dependencies are required.

## Scientific scope

The animated numbers are an educational surrogate designed to make the algorithm legible. They are not Serpent outputs and must not be used for reactor design or safety analysis. Reported final optima and method parameters are taken from the paper.

## GitHub Pages

The included workflow publishes the `dist` directory. In the repository settings, choose **GitHub Actions** as the Pages source.
