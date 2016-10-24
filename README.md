## Steering angle visualizations ##

![enter image description here](https://github.com/jacobgil/keras-steering-angle-visualizations/blob/master/examples/20843_cam.jpg?raw=true)
![enter image description here](https://github.com/jacobgil/keras-steering-angle-visualizations/blob/master/examples/18123_cam.jpg?raw=true)

This contains the model and code for training the NVIDIA steering model on [the dataset given here](https://github.com/SullyChen/Nvidia-Autopilot-TensorFlow), and code for creating visualizations for understanding the steering angle.

[See this blog post.](http://jacobcv.blogspot.com/2016/10/visualizations-for-regressing-wheel.html)


----------


Usage:
Training: `python train.py`
Running: `python run.py --image_path <path_to_image> --type <visualization_type>`

visualization_type can be cam/hypercolumns/occlusion.
