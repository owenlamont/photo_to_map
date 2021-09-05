# photo_to_map

Example Jupyter Notebook to read a directory of photos (jpgs) with location meta data and add popups for each photo to a leaflet map.

https://user-images.githubusercontent.com/12672027/132132625-1e3c0939-6a6b-48b1-8244-1194792bca29.mp4

## Acknowledgements / Attribution

I got the idea for this notebook after listening to [Christopher Bailey](https://twitter.com/digiglean) on the [Real Python Podcast episode 45](https://realpython.com/podcasts/rpp/45/) where I learnt that not only can [Pillow](https://github.com/python-pillow/Pillow) edit and convert images but read the EXIF meta data too.

I copied the functions for extracting the latitude and longitude from this [gist](https://gist.github.com/erans/983821/e30bd051e1b1ae3cb07650f24184aa15c0037ce8) and one of its [forks](https://gist.github.com/moshekaplan/5330395). I used some example code from this [ipyleaflet issue comment](https://github.com/jupyter-widgets/ipyleaflet/issues/550) for how to convert the image to binary format to embed in the popup html.
