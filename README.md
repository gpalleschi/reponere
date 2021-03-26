###
# Reponere 
 Copyright (C) 2021 GPSoft S.A.
 Version: 1.0, date: 15 Mar 2021

Reponere is a bash utility script to replace values in ascii files, the name is latin translation of english word "replace".  
 
Script accepts these arguments [Not positional] : 

<table>
    <tr style="background-color:#A9A9A9">
        <td width="30%" style="text-align:center;color:black;font-weight:bold;border:1px solid black">Option</td>
        <td style="text-align:center;color:black;font-weight:bold;border:1px solid black">Description</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-h]</td>
        <td style="border:1px solid black">for Help</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-r]</td>
        <td style="border:1px solid black">for Recursive search `[Optional if not present take only files in directory]`</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-fv]</td>
        <td style="border:1px solid black">for File contains couple old value, new value separated by space `[Optional]`</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-p]</td>
        <td style="border:1px solid black">for Directory path where are presentes file to substitute `[Optional if not present take execution directory]`</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-f]</td>
        <td style="border:1px solid black">for file names to take for substitutions `[Optional if not present take all files, is expressed with a regular expression]`</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-o]</td>
        <td style="border:1px solid black">old value `[Optional]`</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-n]</td>
        <td style="border:1px solid black">new value `[Optional]`</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-e]</td>
        <td style="border:1px solid black">suffix for file modified `[Optional if is not present suffix is .wrk]`</td>
    </tr>
    <tr>
        <td width="30%" style="font-weight:bold;border:1px solid black">[-d]</td>
        <td style="border:1px solid black">debug mode show differences in files `[Optional]`</td>
    </tr>
</table>     

 Examples of execution :

       reponere -r -opippo -npluto -f*.txt  
       reponere -fv./filevalues.txt -p./DirectoryToWork  
       reponere -fv./filevalues.txt -p./DirectoryToWork -f*.txt -d
