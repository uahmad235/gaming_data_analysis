# ML Assignment

### Project setup

Clone the repo using command:

`git clone https://github.com/uahmad235/ml_assg_1.git`

Install all the project dependencies using command:

`cd ml_assg_1 && pip install -r requirements.txt`

### Download and prepare dataset

In order to run the classification notebook you need classification dataset. The dataset can be obtained by running following command:

`wget https://www.dropbox.com/s/rzbd2vfgmvd9opw/stream_quality_data.zip?dl=1`

You can unzip the dataset using command:

`unzip stream_quality_data.zip -d src/stream_quality_data_class`


In order to run the regression notebook you need regression dataset. The dataset can be obtained by running following command:

`wget https://www.dropbox.com/s/ggim3akt5yjoexb/bitrate_prediction.zip?dl=1`

You can unzip the dataset using command:

`unzip bitrate_prediction.zip -d src/bitrate_prediction`

### Run Notebooks

Now you can run jupyter notebook in the current project using:

`jupyter notebook .`

Once notebook is opened, you can navigate to `src` directory and find two notebooks `classification.ipynb` and `regression.ipynb`. Just click on desired notebook and run. Enjoy! 


**P.S:** This code has been tested with `python 3.8`
