# geoguess-silhouette
guess region by picture

2610
geoguess by silhouette
iu-village, city
(county - old known
regions - saw at mono unf chat)

>gen imgs

2710
with ds 
on python 
in google colab format
- fetch & parse geojson
source: geoBoundaries-UKR-ADM1.geojson (ODbL)
- generate svg (with aspect ratio fix), handle multi-polygons
- generate png
- iso_to_name mapping
- show_all (result pic)
- <img width="1178" height="1390" alt="image" src="https://github.com/user-attachments/assets/e69bbae4-ad97-4de8-9c71-c479532d8ca8" />


TODO 
- integrate real shapes instead mocks
- round’s logic
- upload ipynb here
- fix drawing for dome regions
- make universal tool gejson-to-silhouette-pics
