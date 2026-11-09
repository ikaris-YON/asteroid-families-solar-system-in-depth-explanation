# Asteroid Families of the Solar System

An interactive, single-page explainer about asteroid families and every place small bodies live in the Solar System. It covers near-Earth asteroids, the main belt, Hildas and Trojans, the Kuiper belt and the Oort cloud.

## Features

- **Population map**: animated map at three scales (inner system, Kuiper belt, log-scale Oort cloud). You can switch to a frame that rotates with Jupiter or Neptune to see Trojans and resonant objects.
- **Resonances**: Kirkwood-gap histogram, plus a view of an asteroid's path as Jupiter sees it.
- **Proper vs osculating elements**: an animated toggle that shows families appearing.
- **Family explorer**: a–e, a–sin i and e–sin i plots for 26 main-belt families, coloured by family or taxonomy, with a sortable table.
- **Hierarchical Clustering Method demo**: a cut-off velocity slider with recovery statistics.
- **Yarkovsky V-shape**: a family-age slider showing fragments drifting into resonances.
- **Near-Earth asteroids**: an orbit classifier (Atira/Aten/Apollo/Amor and more, with the Tisserand parameter), an a–e plot coloured by source region, a "journey of a fragment" animation, and source fractions from Granvik et al. (2018).
- **Beyond the belt**: Hungarias, Cybeles, Hildas, Trojans, Centaurs, the Kuiper belt, the Haumea family and the Oort cloud.

## Usage

There's no build step or install. Open `index.html` in any modern browser.

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
open index.html   # or double-click the file
```

## GitHub Pages

Or you can just directly access with this GitHub Pages:
https://ikaris-yon.github.io/asteroid-families-solar-system-in-depth-explanation/



## Built with

- Plain HTML, CSS and JavaScript (Canvas 2D), in a single file
- Google Fonts: Newsreader, IBM Plex Sans, IBM Plex Mono

## Data note

The plotted points are **synthetic**: they're generated around published proper-element centres, resonance locations and source fractions. They reproduce the real structure without loading a catalogue. Member counts and ages are approximate. For real data, use the AstDyS proper-element catalogue, the PDS asteroid family catalogue or the JPL Small-Body Database.

## References

- Granvik, M. et al. (2018). Debiased orbit and absolute-magnitude distributions for near-Earth objects. *Icarus* 312, 181–207.
- Nesvorný, D., Brož, M. & Carruba, V. (2015). Identification and dynamical properties of asteroid families. *Asteroids IV*.
- Zappalà, V. et al. (1990). Asteroid families I: identification by hierarchical clustering. *Astron. J.* 100.
- Nesvorný, D. et al. (2002). The recent breakup of an asteroid in the main-belt region. *Nature* 417.

## License

MIT
