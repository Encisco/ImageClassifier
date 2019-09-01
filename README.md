# 3-way image-classification

This classifier is based on "transfer learning" which takes a pretrained model and extends it to the needs of the current task. In this case our app partitions items into 3 different classes.

The pretrained model is MobileNet and the extension is k-nearest neighbors.

It's all wrapped up using TensorFlow.js for a convenient web-based application.
