# Vocal_Replacement_of_Audio_Recordings

NOTE!: This project does not produce the expected result, which is a audio file where the user's voice is replaced with a voice used during the training of the neural network (deep learning) model.

Abstract: <br>
By taking the data extracted in an audio file, the idea of this project was to replace the voice recording of a person with the voice from a speaker used during the model training process. The goal was to achieve results similar to Auto-Tune, in which the user’s voice would be displaced or modified to resemble the voice of another speaker. However, the approach used in this project did not result in any usable audio output.<br><br>
    
If wanting to examine this project, run and read the scripts in this order:<br>
1) Initializing_Directories_SPEAKER_CHAPTERS_GITHUB<br>
2) Audio_Properties_Extract_GITHUB<br>
3) Deep_Learning_Two_To_One_Model_GITHUB<br>
4) User_Audio_Transform_FULL_ONLY_GITHUB<br><br>

When looking at the coding for these scripts, it was initially set up to train three neural network models (male, female, and all speakers). However, the resulting male and female models did not produce a significant audio file and was omitted in the provided scripts. <br><br>

Lastly, the Deep_Learning_Two_To_One_Model_GITHUB and User_Audio_Transform_FULL_ONLY_GITHUB scripts are set up to run on TensorFlow-GPU (or other environment variants with different names, such as tf-gpu). This part will require changing in the import statements to what you have installed. If using CPU TensorFlow (regular TensorFlow), change the with statement in the Deep_Learning_Two_To_One_Model_GITHUB script: <br><br>
    with tf.device('/GPU:0') ----> with tf.device('/CPU:0')<br><br><br>
    
Hardware Requirements:<br>
- 16+ GB of RAM<br>
- At least 100 GB of Hard Drive Storage (1+ TB if wanting to train all speakers available in all datasets)<br>
- GPU and TensorFlow-GPU highly recommended<br><br>
    
For more information, see Thesis.


<br><br><br> Version 1.0
