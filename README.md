# GeoScaler v1.0

A web-based spatial expansion utility for scaling and editing geospatial data.

## Description

GeoScaler is an open-source web application that allows users to upload geospatial data (Shapefiles or GeoJSON), scale geometries relative to their centroids, perform manual edits, and download the processed data as a ZIP file. It's built with Leaflet for mapping, Turf.js for spatial operations, and Leaflet-Geoman for editing capabilities.

## Features

- **File Upload**: Supports ZIP archives containing Shapefiles or standalone GeoJSON files
- **Geometry Scaling**: Adjust the size of geometries with a slider (from -50% to +100%)
- **Manual Editing**: Enter edit mode to manually reshape polygons using drag-and-drop markers
- **Real-time Preview**: See changes instantly on the map
- **Download Processed Data**: Export modified data as a ZIP file with the scaled GeoJSON included

## Usage

1. Open `index.html` in a modern web browser
2. Click or drag a file into the upload zone (supports .zip or .geojson)
3. Adjust the expansion scale using the slider
4. Optionally, enter manual edit mode to fine-tune geometries
5. Click "Process & Download Zip" to save the modified data

## Requirements

- Modern web browser with JavaScript enabled
- No server-side components required (runs entirely in the browser)

## Dependencies

- [Leaflet](https://leafletjs.com/) - Interactive maps
- [Turf.js](https://turfjs.org/) - Advanced geospatial analysis
- [Leaflet-Geoman](https://geoman.io/) - Geometry editing
- [JSZip](https://stuk.github.io/jszip/) - ZIP file handling
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) - File downloads

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Contributing

Contributions are welcome! Please see the [project repository](https://github.com/KeaganGilmore/geo-scaler/) for more information.

## Donations

If you find this tool useful, consider supporting the developer via [DONATIONS.md](DONATIONS.md).

## Author

Keagan Gilmore - [GitHub](https://github.com/KeaganGilmore/) | [Email](mailto:keagangilmore@gmail.com) | Discord: keagan2980
