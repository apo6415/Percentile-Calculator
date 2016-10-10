# Percentile-Calculator
php command line

PERCENTILE CALCULATOR:
This Project calculates Percentile rank of students reading data from CSV file. It validates the format of student name to dislplay from CSV file and calculates Percentile using following Formula:

(No of scores lesser than student GPA) *100         0.5*(No of times student GPA is repeated)*100
______________________________________       *     ____________________________________________

         (No Of Students)                                         (No of Students)

 

 INSTALLATION AND SETUP

 1. Install PHP 5.6* 'http://php.net/manual/en/install.php' deppending on the platform.
 2. Download the 'HobsonsAssignment.zip' and extract the source.
 3. To run Percentile Calculator:
      a. In command line,  go to 'path/to/source/HobsonsAssignment'
      b. Run "php PercentileCalc/calculateP.php"
      c. Sample Output: "STUDENT NAME: Randy Perez      GPA: 1.60             PERCENTILE: 5.56"


 FUTURE ENHANCEMENTS:

 1. Percentile Calculator's  code structure helps to easily scale to process larger data files/MySQL DB/JSON store. 
 2. Duplicate Records can be omitted while processing data files.
 3. Output format can be customized as requested.
 4. 
