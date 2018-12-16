# **US Bikeshare Data Analysis Project**

## 12th Dec'18

## **Overview:**
In this project, _Python_ is used to explore data related to bike share systems for three major cities in the United States — _Chicago, New York City,_ and _Washington_. 
- The source code takes in raw input from the user to create an interactive experience. 
- According to the input the code will import the data and will provide information by computing descriptive statistics.

## **Files used:**
* bikeshare_2.py

## **Credits:**
* Richard Kalehoff (Udacity mentor)
    - [https://github.com/richardkalehoff](https://github.com/richardkalehoff)
    - [https://twitter.com/richardkalehoff](https://twitter.com/richardkalehoff)

* Juno Lee (Udacity Mentor)
    - [https://github.com/junolee](https://github.com/junolee)
    - [https://www.linkedin.com/in/junoleelj](https://www.linkedin.com/in/junoleelj)

* The data for all 3 cities that is used in this project can be accessed through the link mentioned below :
    - [City Data](https://drive.google.com/file/d/1km4EggJaSvHos_7KKFuHoJxbh-StyM4G/view?usp=sharing)

* The link for commit message style reference for this project is given below :
    - [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/)

## **Softwares needed:**
* _Python 3, NumPy,_ and _Pandas_ installed using _Anaconda_
* A text editor, like _VS Code_ or _Atom_.
* A terminal application (_Terminal_ on _Mac_ and _Linux_ or _Cygwin_ on _Windows_).

## **Installation links for softwares:**
* [Git for windows - for terminal application using Git Bash](https://gitforwindows.org/)
* [Python using Anaconda (latest version for windows)](https://www.anaconda.com/distribution/)
* [Visual Studio Code Editor (for windows)](https://code.visualstudio.com/docs/setup/windows)

## **Links for software tutorials:**
* [Git - Reference](https://git-scm.com/docs)
* [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
* [VS Code Documentation](https://code.visualstudio.com/docs)

## **Code explained in Detail:**
### **How the program works:**
The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:

* Would you like to see data for _Chicago_, _New York_, or _Washington_?
* Would you like to filter the data by month, day, or not at all?
* (If they chose month) Which month - _January_, _February_, _March_, _April_, _May_, or _June_?
* (If they chose day) Which day - _Monday_, _Tuesday_, _Wednesday_, _Thursday_, _Friday_, _Saturday_, or _Sunday_?

The answers to the questions above will determine the city and timeframe on which you'll do data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.

### **The Datasets:**
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

* Start Time (e.g., 2017-01-01 00:07:57)
* End Time (e.g., 2017-01-01 00:20:53)
* Trip Duration (in seconds - e.g., 776)
* Start Station (e.g., Broadway & Barry Ave)
* End Station (e.g., Sedgwick St & North Ave)
* User Type (Subscriber or Customer)

The _Chicago_ and _New York City_ files also have the following two columns:

* Gender
* Birth Year

### **Statistics Computed:**
The code helps user to tell about bike share use in _Chicago_, _New York City_ and _Washington_ by computing a variety of descriptive statistics. In this project, the code output will provide the following information:

* Popular times of travel (i.e., occurs most often in the start time):

  - most common month
  - most common day of week
  - most common hour of day

* Popular stations and trip:

  - most common start station
  - most common end station
  - most common trip from start to end (i.e., most frequent combination of start station and end station)

* Trip duration:

  - total travel time
  - average travel time

* User info:

  - counts of each user type
  - counts of each gender (only available for _NYC_ and _Chicago_)
  - earliest, most recent, most common year of birth (only available for _NYC_ and _Chicago_)



