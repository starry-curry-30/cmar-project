# CMAR-search project page

Project page for **CMAR-search: Commonsense and Memory Augmented Reasoning for Object Search in Dynamic Interactive Environments**, ICRA 2026, pp. 18586–18593.

- Website: https://starry-curry-30.github.io/cmar-project/
- Paper: https://ieeexplore.ieee.org/document/11697035/
- DOI: https://doi.org/10.1109/ICRA57385.2026.11697035
- Video: https://youtu.be/1Qv1jwpRiYA
- Code: https://github.com/starry-curry-30/CMAR-search

Static HTML, CSS, JavaScript, and paper figures are in `dist/`. The research images are the five figures included in the authors' manuscript. The SVG logo links a light bulb (commonsense) with stacked cards and a recall arrow (memory). The page uses a blue-violet palette with amber commonsense accents. Figure viewports trim empty outer margins without modifying the paper images. The layout follows the companion OASIS project page.

Edit `dist/site-config.js` to update resource links. `dist/index.html` contains the publication metadata and BibTeX. The Paper button and citation link to IEEE Xplore.

## Preview

```bash
python3 -m http.server 8767 --directory dist
```

## Publication

GitHub Actions deploys `dist/` to GitHub Pages on pushes to `main`. Set the Pages build source to GitHub Actions. The website repository is separate from the research implementation.
