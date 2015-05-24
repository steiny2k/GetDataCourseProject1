# GetDataCourseProject1

In order to run the analysis you can just execute the `run_analysis.R` file. 
It will automatically create the rawdata directory (if it doesn't exist yet), 
download the source-file for the assignment and unzip it.

Subsequently it will execute all necessary steps to produce the output folder,
and write two files there. The `5.txt` is the output as required by the 
assignment. The `5.slim.txt` is a reshaped version of the dataset saved in 
`5.txt`.

## Code Book of 5.txt
The file 5.txt consits of 68 variables:

* **1. Activity:** The main activity that had been manually labelled
* **2. Subject:** The subject (1 to 30) that participated in the study.
* **3 - 68 Variables:** The mean of the original variable from the samsung 
dataset. As the assinment required to focus the analysis only on the mean and 
standard deviation of the features captured, there are only 66 variables 
remaining from the original dataset.

## Code Book of 5.slim.txt

Reshaped means, that it contains only 4 variables:

1. **Subject:** The subject (1 to 30) that participated in the study.
2. **Activity:** The main activity that had been manually labelled
3. **Variable:** The mean of the original variable from the samsung dataset. 
As the assinment required to focus the analysis only on the mean and standard 
deviation of the features captured, there are only 66 variable values.
4. **Value:** The variable is summarized by applying the mean by activity and 
subject. Due to that, for every combination of subject, activity and variable,
there exists only one value.
