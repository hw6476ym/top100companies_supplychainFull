# Mag 7 Supply Chain Explorer

Interactive 8-tier supply-chain map of the Magnificent 7
(Apple, Microsoft, Alphabet, Amazon, Meta, Nvidia, Tesla):

**Companies → Products → Assembly Plants → Components → Specialty Fabs → Refined Materials → Refineries → Mines**

Every node is a real, named entity (e.g. *Foxconn Zhengzhou*, *TSMC Fab 18*, *SK Hynix M16*,
*CATL Ningde*, *Salar de Atacama*, *Bayan Obo*, *Spruce Pine quartz*) with location, owner,
capacity, and chokepoint flags.

Click any node to trace its full chain in either direction. Search by name, location, or owner.

## Live demo

Open `index.html` directly, or visit the GitHub Pages URL once published.

## Data sources

Public-domain figures from USGS, IEA, BloombergNEF, S&amp;P Commodity Insights,
company filings, and trade press through 2025. Treat as a teaching map — supplier
networks shift quarterly.

## Built with

Single-file HTML + [D3.js](https://d3js.org/) (loaded from CDN). No build step.
