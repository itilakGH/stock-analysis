# stock-analysis
# Challenge
The existing code was passing thru all records in the dataset for each ticker.  This redundance has been eliminated in the refactored code by looping thru only the ticker under evaluation for each ticker.  We are also using arrays that may improve performance.  I have also used the redim preserve VBA statement which dynamically changes the size of the array so that memory is utilized efficiently.
