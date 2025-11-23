# Analysing a set of measured data points to ascertain their central tendency and spread, as well as measuring the accuracy of the measurements against a known standard or true value, is often required in scientific, engineering, and data analysis contexts.  It is time-consuming and prone to error to perform these statistical and error calculations by hand.  The lack of a fast, easy-to-use desktop tool that can process multiple measurement values and instantly provide important measurement errors (absolute, relative, and percentage error) and key descriptive statistics (mean, variance, and standard deviation) through an intuitive graphical interface is the problem addressed.

#The project's scope is restricted to offering measurement error quantification and descriptive statistical analysis for one-dimensional numerical data input through a desktop GUI.
 The undertaking will:

 Accept a single string of free-form text input with numbers in it.

 Compute and present the sample variance, sample standard deviation, and mean.

 Calculate Absolute, Relative, and Percentage Errors by optionally accepting a True Value input.

 For non-numeric or empty inputs, apply basic validation and error handling.

 Use only the standard Python libraries (Tkinter and re) to operate as a stand-alone program.

The project won't consist of:

 sophisticated statistical tests (such as regression and hypothesis testing).

 Data visualisation, such as box plots or histograms.

 Data persistence (loading or storing data from databases or files).

 It is a desktop application with a single module and intricate architectural patterns.

 People who work in measurement and data analysis and need rapid, preliminary statistical and error results are the application's main target users.

 Researchers and students studying engineering: For evaluating the outcomes of laboratory experiments and calculating measurement uncertainty.

 Professionals in science (chemistry, physics): To process readings and verify that experimental procedures are accurate in comparison to predicted theoretical values.

 Data entry/quality control personnel: For quick assessments of small datasets' consistency and deviations.

 High-Level Characteristics
 Three main functional modules are offered by the application:



 Data Input & Parsing: Regular expressions are used to extract valid numerical data from a list of measured values that the user enters in a flexible format.

 The statistical calculation module computes the mean, sample variance, and sample standard deviation using the extracted numerical data.

 Error Analysis Module: Calculates the Absolute Error, Relative Error, and Percentage Error using the computed Mean and an optional True Value.
