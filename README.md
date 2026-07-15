# Jerilderie 3D

Interactive browser-based 3D massing model of Jerilderie, NSW 2716.

The model combines:

- Microsoft Global ML Building Footprints
- OpenStreetMap roads, waterways, parks and named places
- Procedurally inferred building heights and roof treatments
- Aerial and walkable street-level camera modes
- Screenshot and GLB export tools

## Website

After GitHub Pages finishes deploying, the model will be available at:

**https://douglasbright.github.io/jerilderie-3d/**

## Data and attribution

Building footprints are sourced from Microsoft Global ML Building Footprints under the CDLA Permissive 2.0 licence. Map context is sourced from OpenStreetMap contributors.

The GitHub Pages workflow downloads the geographic source data during deployment and packages it with the static website. This avoids browser CORS problems and means no local Python server is required when visiting the hosted site.

## Updating

Pushing to the `main` branch runs the Pages workflow again and refreshes the packaged geographic data.
