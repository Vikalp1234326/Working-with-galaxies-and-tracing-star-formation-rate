# Working-with-galaxies-and-tracing-star-formation-rate
Here you can find codes to work with multi wavelength datasets for M51 galaxy. For preparation and calibration of the raw data Pystructure code has been used the link to same is git clone https://github.com/jdenbrok/PyStructure.git

# Instructions for understanding the structure of the code and using the codes within it for your own analysis: 

1. As instructed in Pystrcuture repository you can start with your raw data in fits format and and run the Pystrcuture code for further detailed explanation use the PyStructure repository.
2. Following the sucessful implementaion of the PyStructure code you will get the result of the code in form of a .npy file under this you will find all the data in form of a dictionary with all the values stored as list. Detailed list of all the columns can be found using the Pystructure page or using the first command of the .ipynb file. (Note: The PyStructure repo gets regular updates you the structure might vary at the time of usage)
3. Following this all the calculations for star formation rate and sigma star formation rate can be found. All the equations are given in form of comment where the formula is being used.
4. Once the calculations are perfomed successfully all the plots made using these calculations are shown from the second .ipynb file plots.ipynb .
