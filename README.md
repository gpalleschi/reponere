###
## Reponere 
 Copyright (C) 2021 GPSoft S.A.
 Version: 1.0, date: 15 Mar 2021
##
 Reponere is a bash utility script to replace values in ascii files, the name is latin translation of english word "replace".  
 Script accepts these arguments : -h for Help  
                                  -r for Recursive [Optional if not present take only files in directory]  
                                  -fv for File contains couple old value, new value separated by space [Optional]  
                                  -p for Directory path where are presentes file to substitute [Optional if not present take ./ ]  
                                  -f for file names to take for substitutions [Optional if not present take all files]  
                                  -o old value [Optional]  
                                  -n new value [Optional]  
                                  -e suffix for file modified [Optional]  
                                  -d debug mode show differences in files  

 Examples of execution :

       reponere -r -opippo -npluto -f*.txt  
       reponere -fv./filevalues.txt -d./DirectoryToWork  
