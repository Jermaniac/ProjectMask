# MaskProject
 
In this project a object detection model will be created.
There are three classes: with_mask, without_mask and mask_weared_incorrect.
The dataset is composed by 80 images for training and 20 images for test.


python models/research/object_detection/model_main_tf2.py --model_dir=training/trained --pipeline_config_path=training/pipeline.config --num_train_steps=5000


PD: Protocol Buffers are necessary to build this project, install here: https://github.com/protocolbuffers/protobuf/releases/tag/v3.4.0