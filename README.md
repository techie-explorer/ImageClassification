# ImageClassification using Inception V3

This is an existing project. I modified the code according to my convenience

Create folders in the 'training_dataset' folder,
each folder representing a class. 

python retrain.py --bottleneck_dir=tf_files/bottlenecks --how_many_training_steps=500 --model_dir=inception --summaries_dir=tf_files/training_summaries/basic --output_graph=tf_files/retrained_graph.pb --output_labels=tf_files/retrained_labels.txt --image_dir=training_dataset --eval_step_interval=100 & python classify.py test.jpg

original source links will be mentioned here soon