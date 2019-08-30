# Instance Segmentation of Geometrical Shapes in Aerial Images
This is my Master thesis project at ETH Zurich, which contains two parts:
* Buildings Segmentation (see `buildings/Train.py`),
* Roads Segmentation (see `road_polygon_new/Train.py`).

Data should be placed correctly (not in the folder `data`).
See `Config.py` file for more details.
If you want the data please send me an request email.

Arguments:
* `--city`: the city name.
* `--net`: backbone of the net.
* `--load`: resume training or not.
* `--vis`: whether visualize the prediction or not.

To train the model just simply `python3 Train.py --XXX YYY` is fine.
To run inference just `python3 Evaluate.py --XXX YYY`.
