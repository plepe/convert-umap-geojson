# convert-umap-geojson
UMap offers a save to GeoJSON option, but it will discard the layer information. With this script, you can save a map in Umap format, and it will convert this to a GeoJSON file. Each feature gets a `_layer` property with the name of its layer.

## Usage
```sh
./convert-umap-geojson
```
It will take a file data.umap and save it as data.geojson
