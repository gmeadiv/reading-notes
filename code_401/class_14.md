# Cascadia JS: Thursday

## Dolby dot io Workshop

### [Here's my video app](https://flamboyant-bohr-9edbd9.netlify.app)

### [GitHub Repo](https://github.com/gmeadiv/dolby-io-workshop)

## Derek Hurley: Cartography on the Web

- lessons learned building interactive maps

- common core:
  - data sources --> style layers
- similar to
  - HTML --> CSS

- preparing data for the map
  - GeoJSON
    - easy to build and change a truntime
    - needs all data in the browser at once
    - better for smaller or real-time datasets
  - Vector Tiles
    - compressed at build time
    - won't always have all the data at once
    - better for larger or stable datasets

- interacting with the map
  - design decisions
    - which layers can be clicked/hovered
    - which features can be clicked/hovered
    - does zoom matter
  - play to layer strengths
    - data layers
      - all trees
      - source of truth
      - often vector tiles
    - UI layers
      - Hovered tree
      - data comes from other layers
      - often GeoJSON

- connecting to the larger app

![SCREENSHOT]('./images/connecting-to-larger-app.png')

- initialization sequence
  - app renders
  - app sends config to map
  - map loads, starts fetching data
  - map broadcasts it has been loaded
  - map continues fetching data
  - app runs map-dependent logic

  - connecting and waiting

## key takeaways

- consider which layers are best paired with which sources
- create intentional boundaries between the map and the larger app
- understand the nature of the data you want to contextualize that data in maps
