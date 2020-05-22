# m5

I recommend creating the following directories for data

../input/m5-forecasting-accuracy/ -- for original data
../input/m5-forecasting-uncertainty/ -- only sample_submission.csv differs from m5-forecasting-accuracy
../data/m5-forecasting/ -- for intermediate (derived) data
../output/ -- for final forecasts

Keep these directories outside of git or we're going to run out of space

data_preparation notebook transforms the data to the format that I think is most suitable for ML and saves them to feather 
files that are smaller in size, still have all the information and compatible with both pandas and R
