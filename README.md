# The Tkinter library for Python was used to create this straightforward, stand-alone desktop application.  Its main goal is to assist users in rapidly performing basic statistical analysis (Mean, Variance, Standard Deviation) on a collection of measured data points and, in the event that a known true value is supplied, calculating measurement errors (Absolute, Relative, Percentage).

 #Flexible Data Input: Any character (spaces, commas, newlines, etc.) can be used to separate measured values.


 For the measured data, statistical analysis computes the following:

 Average (mean)

 Variance of the Sample

 Standard Deviation of the Sample

 When a True Value is provided, Error Analysis (Optional) computes measurement errors.

 Total Inaccuracy

 Error Relative

 Error Percentage

 User-Friendly GUI: Tkinter was used to create a straightforward, responsive interface.
 Error messages for non-numeric or empty inputs are provided by input validation.

 The program is adaptable to different data entry styles because it robustly extracts all numerical values from a free-form input string using a Regular Expression (re).

 #Language: Python 3

 Tkinter (a standard Python library) is the GUI library.

 Regular Expressions: The integrated re module for parsing data.

 #1. Requirements
 Python 3 needs to be installed on your computer.  No additional installations (like pip install) are usually needed because Tkinter and the re module are part of the standard Python installation.

 2. Get the Code
 Get the file or clone this repository: git clone https://github.com/YourUsername/tkinter-stats-error-calculator.git cd tkinter-stats-error-calculator

 #Save the supplied code as error_calculator.py and execute it using the following command in your terminal: python error_calculator.py
 The GUI window ought to open right away.
