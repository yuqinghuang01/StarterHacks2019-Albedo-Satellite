# StarterHacks2019-Albedo-Satellite
# This project was accomplished in a group of five at the StarterHacks 2019 event

# INSPIRATION
# Urban heat islands are a developing problem in developing nations where urbanization is taking place. 
# To encourage better urban planning, we created a module that can be attached to a satellite to measure 
# the number of lumens being reflected off of the Earth's surface. The satellite could be positioned over 
# cities so that the data can be measured and sent back to scientists and engineers to combat heat buildup 
# via solar radiation absorption known as albedo.

# WHAT IT DOES
# The phone's luminosity sensors measure the luminosity (lux) of a surface. Which the Arduino delivers to 
# the computer. This data is written down on a text file, and a graph is made. Which is then published on to 
# our website.

# HOW WE BUILT IT
# We used an Arduino and 1sheeld to collect the data from our phone, with Pyhon and Matlab being used for 
# data analysis. Then, HTML and CSS were used to make our website.

# CHALLENGES WE RAN INTO
# We could not read the serial output for data collection. We first tried using the Arduino IDE, then Matlab, 
# finally, python was used and it successfully retrieved the serial data and outputted a txt file that could be 
# transferred to Matlab to generate a graph.

# ACCOMPLISHMENTS THAT WE ARE PROUD OF
# We were able to make the sensor work and successfully work with 5 different coding languages. We had to learn 
# the languages during the project, it was difficult but in the end we learned a lot and we're able to create the
# product that we intended to create.

# WHAT WE LEARNED
# We learned how to link multiple languages together using serial, how to read serial with Python, code a light sensor 
# with Arduino and make a webpage to print data onto.

# FUTURE IMPROVEMENTS
# The webpage output can be turned into real time graph generation so researchers can monitor the luminosity of cities 
# in real time and perhaps make more comprehensive models from the larger and more long term data set.
