import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
print(" ")
print("Data Analysis and Visualization")
print(" ")
print("Project by students of ")
print(" ")
print("BK BIRLA CENTRE FOR EDUCATION")
print("Acedemic Year 2022-23")
def Fun():
    print("Topic - Data Analysis")
    print("===================")
    print(" ")
    print("#1. For checking the data.")
    print("#2. Reading complete file without index.")
    print("===================")
    print("Topic - Data Visualization")
    print(" ")
    print("#3. Bar Graph")
    print("    Press 1 to visualize Bar Graph")
    print(" ")
    print("#4. For Exit")
    print("===============")


def Read_CSV():
    print("The Data")
    df=pd.read_csv('Covid_data_kerala.csv')
    print(df)

def No_Index():
    print("Reading the file without index")
    df=pd.read_csv('Covid_data_kerala.csv', index_col=0)
    print(df)
        
#FOR BAR GRAPH:)

def bar_plot():
    df = pd.read_csv('Covid_data_kerala.csv')
    df['States'] = ['KL','AP','MH','GJ','PJ','HP','JK','KA','TN']
    District = df["States"]
    Score = df["Score"]
    plt.xlabel("States")


    YC = int(input("Enter for 1 Bar Graph:"))
    
    if YC == 1:
        plt.ylabel("Score Cases")
        plt.title("States Wise Health")
        plt.bar(District, Score, color='b', width = 0.5)
        plt.show()
    
Fun()
YC = int(input("Enter Your Choice: "))

while YC == 1 or 2 or 3 or 4 or 5 or 6:

    if YC == 1:
        Read_CSV()
        print("Thank You for using...")
        break
    elif YC == 2:
        No_Index()
        print("Thank You for using...")
        break
    elif YC == 3:
        bar_plot()
        print("Thank You for using...")
        break
    elif YC == 4:
        print("Thank You for using...")
        break
    else:
        print("Enter valid input")
        break
