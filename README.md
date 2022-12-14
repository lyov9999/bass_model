"# boass_model_package" 

To run the following package you should:

1. Need to be created a folder data and python file .
2. In the folder, have the data in the 'CSV' format, where the first column will represent year and the second column sales. WARNING!!! (data should be without headings)
3. Create a .py and run the commands below
- !pip install bass-model
- from bass_model.bass_model import Bass_model
- model = Bass_model("avocados.csv")

Available methods:

- model.fit_model()  # fitting the data
- model.predict_result() # getting the prediction
- model.visualize_pdf() #  ploting predicted pdf against the actual sales data
- model.visualize_cdf() # ploting predicted cdf 
- model.summary() # getting the summary

Warning!!! (to visit the code, please refer to master branch!!!)
