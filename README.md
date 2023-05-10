# Ex03 Time Table

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.


### STEP 3
Create a simple table using ```<table>``` tag in html.


### STEP 4
Add header row using ```<th>``` tag.


### STEP 5
Add your timetable using ```<td>``` tag.


### STEP 6
Execute the program using runserver command.


## CODE
```
<html>
     <head>
              <title> web </title>
     </head>
     <body bgcolor="black" TEXT="white">
<center>
     <img src="/static/images/saveethalogo.png"  height="100" width="1000" align="center" /></center>
          
          <table border= "4" cellspacing="0px" cellpadding="10px" bgcolor=green" align="center" >
          <CAPTION align=“top”> SLOT TIME TABLE - CHARUMATHI R(22006878) </CAPTION>
          <br>
          <br>
               <tr> 
               <th bgcolor="gray">   DAY/TIME </th>
               <th bgcolor="purple">   MONDAY </th>
               <th bgcolor="purple">   TUESDAY </th>
               <th bgcolor="purple">   WEDNESDAY </th>
               <th bgcolor="purple">   THURSDAY </th>
               <th bgcolor="purple">   FRIDAY </th>
               </tr>
               <tr>
                <th bgcolor="purple"> 8-10 </th>
                <td> -- </td>
                <td> C programming </td>
                  <td> -- </td>
                <td> FWAD </td>
                <td> FWAD </td>
               </tr>
               <tr>
                <th bgcolor="purple"> 10-12 </th>
                <td> -- </td>
                <td> DL </td>
                <td> DIP </td>
                <td> DIP </td>
                <td> DL </td>
               </tr>
               <tr>
                <th bgcolor="purple"> 12-1 </th>
                 <td colspan="5" align="center">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="purple"> 1-3 </th>
                <td> -- </td>
                <td> -- </td>
                <td> FWAD </td>
                <td> -- </td>
                <td> Physics/- </td>
               </tr>
               
              
              <tr>
               <th bgcolor="purple"> 3-5 </th>
               <td> Statictis </td>
               <td> Physics </td>
               <td> C Program </td> 
               <td> -- </td> 
               <td> Statictis </td>
              </tr>
           </table>
            <table border= "4" cellspacing="0px" cellpadding="10px"  align="center" >
           <tr>
           <th> S.No </th>
             <th> SUBJECT CODE </th>
           <th> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td> 1. </td>
           <td> 19AI414 </td>
           <td> Fundamental of web application and development </td>
           </tr>
           <tr>
           <td> 2. </td>
           <td> 19AI406 </td>
           <td> Digital Image Processing techniques </td>
           </tr>
           <tr>
           <td> 3. </td>
           <td> 19AI304 </td> 
           <td> Fundamental of C programming </td>
           </tr>
           <tr>
           <td> 4. </td>
           <td> 19PH214 </td>
           <td> Physics for quantum computing </td>
           </tr>
           <tr>
           <td> 5. </td>
           <td> 19AI413 </td>
           <td> Deep Learning and Applications </td>
           </tr>
           <tr>
           <td> 6. </td>
           <td> 19MA211 </td>
           <td> Statictis and Numerical Methods </td>
           </tr>
           </table>
              
        </body>
</html>
```

## OUTPUT.name
![OUTPUT](./out3.png)

## HTML VALIDATOR
![HTMLVALIDATOR](./out4.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

