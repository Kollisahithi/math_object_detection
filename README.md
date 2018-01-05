# Math Operators Object Detection (Video Demo):
[![Custom Math Operators TensorFlow Object Detection - Test 1](https://github.com/stevenobadja/math_object_detection/blob/master/s_img/Screen%20Shot%202018-01-04%20at%205.58.45%20PM.png?raw=true)](https://youtu.be/iss52uQS6jo)

Utilizing TensorFlow Object Detection API open source framework, it makes it feasible to construct, train and deploy my own custom object detection model. In this instance, I have created my own image library (of math numbers & operators) for training and testing. This can be found under the [images](https://github.com/stevenobadja/math_object_detection/tree/master/images) folder.

### Powered by: Tensorflow
**Model:** ssd_mobilenet_v1_coco_2017_11_17<br/>
**Config:** ssd_mobilenet_v1_coco<br/>

# Source:

### Google's object detection
[https://github.com/tensorflow/models/tree/master/research/object_detection](https://github.com/tensorflow/models/tree/master/research/object_detection)

Will contain:
- xml_to_csv.py
- generate_tfrecord.py
- train.py
- export_inference_graph.py
- All other support docs...

### Tensorflow detection model zoo
[https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)

Will contain:
- ssd_mobilenet_v1_coco_2017_11_17 (model used for this demo)
- All other models released by Tensorflow...

### Tensorflow config files
[https://github.com/tensorflow/models/tree/master/research/object_detection/samples/configs](https://github.com/tensorflow/models/tree/master/research/object_detection/samples/configs)

Will contain:
- ssd_mobilenet_v1_coco (config used for this demo)
- All other configs released by Tensorflow...

### Label images with labelImg
[https://github.com/tzutalin/labelImg](https://github.com/tzutalin/labelImg)

Will contain:
- labelImg.py
