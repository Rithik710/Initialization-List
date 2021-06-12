# Initialization-List
Suppose we have a student class having 2 data members -> 1) int age ; 2) int rollno; 
## now we made this roll no. constant such that each student have only 1 roll nmber. i.e => const int rollno.  
## now as per the rule, constant members needs to be initialized at the time of their initialization only, we cant assign them value after initialization.
but we need to assign different values to different student objestc..
How could we do that ?  
# here comes the role of Initialization list
## class student{ public : int age; const int rollno ; 
                      student(int r, int a) : rollno(r), age(a) {}


} ;

## and its done, it means 
### rllno me r daal do and age me a daal do.
