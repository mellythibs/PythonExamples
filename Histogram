import os
import shutil
import matplotlib.pyplot as plt #Added just to print histo graph
import numpy as np #added for histo graph

ARR = np.array([])

#just starts the process so it doesn't skip over the while loop
number = input("ENTER A NUM ")
number = int(number)

#Takes input from keyboard as the prompting says
while(number >= 0):
   print('Input a number that is equal to or greater than 0')
   print('Enter a number less than 0 to stop entering numbers')     
   number = input("ENTER A NUM ")
   number = int(number)
   ARR = np.append(ARR, number)
   
# creates the histogram graph using the input from the user   
figLook = plt.hist(ARR, 100,density =1, facecolor = 'g', alpha=1)
figLook = plt.xlabel('Values')
figLook = plt.ylabel('Frequency')
figLook = plt.title('Keyboard Inputs')
plt.plot() #prints to console
plt.savefig('exampleHISTO.png') #saves the picture as a .png file
