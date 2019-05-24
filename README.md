UET-AI-Robot INT3409-21
## Chalenge 1

Group members:	Nguyễn Như Duy Phương-16020267, Phan Tuấn Thành 

## Requirements
* OS: Mac OS X 10.9+, Ubuntu 14.04+
* Graphics Card: DX9 (shader model 3.0) or DX11 with feature 	level 9.3 capabilities.
* CPU: SSE2 instruction set support.
* Python 2.7 or Python 3.5+
* Linux users: X server with GLX module enabled
* CUDA

## Installation and Getting Started
* Installing AI2-THOR using pip:

`$ pip install ai2thor`

* Git clone the repository:

`$ git clone https://github.com/TowTow0059/robot.git`

`$ cd yolo-coco`

`$ wget https://pjreddie.com/media/files/yolov3.weights`

* Run:

`$ sudo python assignment.py`

## Actions
* “w” - Move forward.
* “s” - Move backward(without changing view direction).
* “a” - Move left(without changing view direction).
* “d” - Move right by gridSize (without changing view direction).
* “left arrow” - Turn 90 degrees to left.
* “right arrow” - Turn 90 degrees to right.
* “up arrow” - Turn 30 degrees up.
* “down arrow” - Turn 30 degrees down.
## Example
Input:

![input](/img/image.jpg)

Output:

![output](/img/detected_image.jpg)
