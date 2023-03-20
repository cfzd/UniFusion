# UniFusion: Unified Multi-view Fusion Transformer for Spatial-Temporal Representation in Bird’s-Eye-View

## City-based split
This repo contains the "city-based" split proposed in the [paper](https://arxiv.org/abs/2207.08536). 
* Trianing set: the samples collected in `singapore-queenstown` and `singapore-hollandvillage`.
* Validation set: the samples collected in `singapore-onenorth` and `boston-seaport`.

The sizes of training and validation sets of "city-based" split are 26,093 and 8,056. For comparision, the sizes of the vanilla training and validation sets are 28,130 and 6,019.

We also provide a `nuscenes_city_based_split.py` to generate the city-based split.

## Demo

We also provide a demo of our method.

<a href="https://youtu.be/zUpJIj7HHU8
" target="_blank"><img src="http://img.youtube.com/vi/zUpJIj7HHU8/0.jpg" 
alt="Demo" width="1280" height="400" border="10" /></a>
