# jpg_to_tiles

gdal2tiles.py -s EPSG:3857 -v source/chura1.jpg tiles/

git checkout -b gh-pages
git add tiles
git commit -am "add tiles"
git push origin gh-pages
in OSM background -> Custom -> https://niryariv.github.io/jpg_to_tiles/tiles/{z}/{x}/{-y}.png
