# Workfront-API-sample
An example Python API call to a Workfront object (assignment object) that exports it to a .CSV file.

This code allows you to choose your Workfront object and determines how many records to pull and how to loop through them without missing data. It oragnizes the response data and formats desired fields into a Pandas dataframe before exporting it as a .CSV to your location of choice.

The code uses try-and-except statements because it was developed under a very short timeframe and the semi-structured data did not always contain the desired field(s), causing errors in the loop. Streamlining the pulling of the information from the semi-structured response with error handling exceptions would be a great improvement to this code in terms of readability and efficiency.
