# Active-Learning-Playground
#This program compares the performance of active learning and no active 
#learning with Gaussian Process Regressor. The data it takes are kmer protein 
#sequences(in protein alphabet) and their corresponding protein affinity 
#values(continuous value) in a csv file.
#The protein alphabet is first tranformed to binary vectors using one hot encoding so 
#that each letter becomes a feature. It then trains Gaussian Process Regressor using 
#active learning with query strategy picking samples with highest standard deviation 
#according to the regressor prediction. Note: currently, the active learning performs 
#worse than no active learning. ;(
