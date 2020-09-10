# crop_detection_in_fields-
# machine learning/deep learning in agriculture sector

Hey! hope this finds you helpful

Well the process is very simple. Starting with
1.Labelling our data with the tool file labelImg.py

2.Then converting it in csv file with the help of xml_to_csv.py

3.This csv file is then converted into .tfrecords with the help of generate_tfrecord.py

4.Select a model for transfer learning and get its config file

5.Train your model with train.py and save the checkpoints

its done!
Test your model
