# Florida Book Bans Map

This project provides an interactive map visualizing book bans in Florida school districts for the year 2022-2023. The map allows users to explore the distribution of banned books across different districts. This map would be a good addition to this news article(https://www.npr.org/2024/04/16/1245037718/book-bans-2023-pen-america).

## Interactions

The map provides the following interactions:

- **Hover:** Hover over a school district to view the number of banned books in that district.
- **Click:** Click on a school district to zoom in and view it in more detail.

## Libraries Used

The following libraries are used to build the map:

- **Leaflet:** Leaflet is an open-source JavaScript library for interactive maps. It provides a simple and lightweight solution for creating web maps.
- **jQuery:** jQuery is a fast, small, and feature-rich JavaScript library. It simplifies HTML document traversing, event handling, animating, and Ajax interactions for rapid web development.
- **Leaflet.ajax:** Leaflet.ajax is a plugin that extends Leaflet to support loading GeoJSON data via Ajax.
- **Chroma.js:** Chroma.js is a small library for color conversions and color scale manipulations. It's used here for generating color scales to represent the number of book bans.

## Usage

1. Clone the repository to your local machine:
    ```
    git clone https://github.com/your-username/your-repository.git
    ```
2. Open the `index.html` file in a web browser to view the map.

## Data Sources

- **Florida GeoJSON:** The shapefile data for Florida school districts is obtained from [Data.gov](https://catalog.data.gov/dataset/2019-cartographic-boundary-shapefile-current-unified-school-district-for-florida-1-5000001).
- **Book Bans Data:** Information about banned books comes from [Pen America](https://pen.org/2023-banned-book-list/).

## Credits

This map is created by Angela Andrade.