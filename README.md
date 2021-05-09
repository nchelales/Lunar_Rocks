# 738_LunarLandscapes
ECE 738 University of Wisconsin Madison Project, adapting U-Net for Lunar Landscape Segmentation

Project Goals:
-Apply U-Net Segmentation Algorithm to Lunar landscape dataset, and compare results with K-means clustering and K-Means shift.
-Perform error analysis exploring different types of segmentation errors and their efficacy. 

Project Implemented Using Kaggle Dataset Here by Roman Pessia: 
https://www.kaggle.com/romainpessia/artificial-lunar-rocky-landscape-dataset

For more information on the complete project and results, please consult 738_Project_Report.pdf


**Project Files and Notebooks:**

**738_Project_Report:** discussion of project goals, methods, results, and analysis

**CreateDataSets_clean:** generates data batches for training U-net using the given kaggle dataset

**GenerateStatisticsMyModels:** Used to generate quantitative metrics for the given U-Net model

**GenerateStatisticsUnsupervisedModels:** Used to generate quantitiatve metrics for the K-means and mean-shift algorithm

**Version3_RunUnet_myModel:**

U-net training model. Trains U-net using the given dataset and saves trained model into json and h5 files. 
Note the files are too big to be included in the GitHub Repo.

**Statistics_MyModels:** Statistics of the two different U-Net models
**Statistics_Unsupervised:** Statistics of the K-means and Mean Shift models. 
