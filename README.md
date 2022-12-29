# ICDAR2023 Competition on Detection & Classification of Writing in Air

DataSet folder contains two subfolders DataSet_1 and DataSet_2 each for the specific task mentioned in the dataset.

TASK-1:
CASSIFICATION OF WRITING ACTVITIY IN AIR
Aim of this task is to map airiwritten trajectories onto respective digits(0-9) and characters (A-Z and a-z).

Data provided for this task is presented in Dataset_1 folders and details of data are given below:
 
           1) It contains the data for training as Train_Set divided into Two sub folders (X,Y)_Co-ordinates and Sensor data.
	             1a). (X,Y)_Co-ordinates : contains the x,y co-ordinates of reconstructed trajectories. 70 participants data is stored in separated folder with its ID and labels for it trajectory is mentioned in file name as well.
				  
		     1b). Sensor : 
		                  Contains the data from same number of participants. The data is directly collected from IMU sensor and is each sensor data file is presented with its trajectory recontruction.
				  
TASK-2
Aim of this task is to segment the writing activity from other gestures performed in air as binary classification task.
  
Data provided for this task is presented in Dataset_2 folders and details of data are given below:

           1) It contains the data for training as Train_Set divided into Two sub folders (X,Y)_Co-ordinates and Sensor data.
	             1a). (X,Y)_Co-ordinates : 
		                  Contains 38 participants and each participants data is stored in separated folder id and that folder contains the (X,Y)Co-Ordinates calculated or extracted using raw sensor data in Not_writing_sequence_start - writing_sequence - Not_writing_sequence_end 
				  
		     1b). Sensor : 
		                  Contains 38 participants and each participants data is stored in separated folder id and that folder contains the  slected raw feature data taken from raw sensor data in Not_writing_sequence_start - writing_sequence - Not_writing_sequence_end along with respective image as well.
				  
	   
