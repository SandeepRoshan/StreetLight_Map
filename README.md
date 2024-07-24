# Leaflet Map with Custom Icons and Circles

This project demonstrates how to create an interactive Leaflet map with custom icons and circles to represent various areas. The map allows users to view different areas based on their selection and includes a modal for authentication.

## Features

- **Interactive Map**: Display areas with custom circles and icons using Leaflet.
- **Custom Icons**: Use custom icons for streetlight markers.
- **Area Selection**: Buttons to show different groups of areas on the map.
- **Popup Links**: Popups with hyperlinks to additional information and authentication.
- **Authentication Modal**: A modal for user authentication.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd your-repository
   ```

3. **Open the `index.html` File**

   You can open the `index.html` file directly in a web browser.

## Project Structure

- `index.html`: The main HTML file containing the map and controls.
- `style.css`: Custom styles for the map and UI components.
- `script.js`: JavaScript code for map initialization, area plotting, and event handling.

## Configuration

- **Map Tile Layer**: Configured using MapTiler. Replace the URL in `L.tileLayer` with your own if necessary.
- **Streetlight Icon**: Replace the `iconUrl` with the URL to your own streetlight icon image.
- **Areas**: Customize the `areas` object in `script.js` to adjust the center and radius of each area.

## Usage

- **Show Area**: Click the buttons in the control box to view different groups of areas on the map.
- **Streetlight Popups**: Hover over streetlight markers to view detailed information and click the links for queries and status.

## License

- **MIT License**: This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
- **OpenStreetMap**: This project uses map data from OpenStreetMap. The data is licensed under the [Open Database License (ODbL)](https://www.openstreetmap.org/copyright). For more information, see [OpenStreetMap's usage policy](https://operations.osmfoundation.org/policies/usage/).

## Contributing

Contributions are welcome! Please submit a pull request or open an issue if you have suggestions or find bugs.

## Acknowledgments

- [Leaflet](https://leafletjs.com/) for the mapping library.
- [MapTiler](https://www.maptiler.com/) for the tile layer.
- [OpenStreetMap](https://www.openstreetmap.org/) for the map data.
