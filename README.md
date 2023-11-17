# Ex03 Time Table
## Date: 17.11.2023

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

## PROGRAM
```
<html>
  <title>title</title>
      <body>
       <img src="/static/logo.png" height="100" width="540">
         <table boarder="6"  cellspacing="4" cellpadding="4" bgcolor="violet">
             <caption>MY TIME TABLE</caption>

                 <tr>
                   <th bgcolor="pink" align="center">day/time</th>
                   <th bgcolor="pink" align="center">8:9 am</th>
                   <th bgcolor="pink" align="center">9:10 am</th>
                   <th bgcolor="pink" align="center">10:11 am</th>
                   <th bgcolor="pink" align="center">11:12 am</th>
                   <th bgcolor="pink" align="center">12:1 pm</th>
                   <th bgcolor="pink" align="center">1:2 pm</th>
                   <th bgcolor="pink" align="center">2:3 pm</th>
                   <th bgcolor="pink" align="center">3:4 pm</th>
                   <th bgcolor="pink" align="center">4:5 pm</th>
                </tr>

                 <tr>
                   <th bgcolor="pink" align="center" bgcolor="red">MONDAY</th>
                   <td colspan="2" align="center" bgcolor="red">soft skills</td> 
                   <td colspan="2" align="center" bgcolor="red">python</td>
                   <td align="center" bgcolor="red">LUNCH</td>
                   <td colspan="2" align="center" bgcolor="red">physics</td>
                   <th colspan="2" align="center" bgcolor="red">free</th>                   
                   </tr>

                 <tr>
                   <th bgcolor="pink" align="center" >TUESDAY</th>
                   <th colspan="4" align="center" bgcolor="red">free</th>
                   <td align="center" bgcolor="red">LUNCH</td>
                   <th colspan="4" align="center" bgcolor="red">free</thh>
                   </tr>

                 <tr>
                   <th bgcolor="pink" align="center">WEDNESDAY</th>
                   <td colspan="2" align="center" bgcolor="red">web application</td>
                   <td colspan="2" align="center" bgcolor="red">computer architecture</td>                    
                   <td align="center" bgcolor="red">LUNCH</td>
                   <td colspan="2" align="center" bgcolor="red">maths</td>                    
                   <th colspan="2" align="center" bgcolor="red">free</th>                    
                </tr>

                 <tr>
                   <th bgcolor="pink" align="center">THURSDAY</th>
                   <td colspan="2" align="center" bgcolor="red">maths</td>
                   <td colspan="2" align="center" bgcolor="red">web application</td>                    
                   <td align="center" bgcolor="red">LUNCH</td>
                   <td colspan="2" align="center" bgcolor="red">python</td>                    
                   <th colspan="2" align="center" bgcolor="red">free</th>                    
                </tr>

                   <tr>
                   <th bgcolor="pink" align="center">FRIDAY</th>
                   <th colspan="2" align="center" bgcolor="red">free</th>                    
                   <td align="center" bgcolor="red">computer architecture</td>
                   <th align="center" bgcolor="red">free</th>
                   <td align="center" bgcolor="red">LUNCH</td>
                   <td colspan="2" align="center" bgcolor="red">web application</td>                    
                   <td align="center" bgcolor="red">physics</td>
                   <th align="center" bgcolor="red">free</th>
                </tr>

         </table>
         <table boarder="6" cellspacing="4" cellpadding="4" bgcolor="white">                                        

<caption>SUBJECT AND THEIR RESPECTIVE SUBJECT CODES </caption>
                    <tr>
                   <th align="center" bgcolor="cyan">S.NO</th>
                   <th align="center" bgcolor="cyan">Subject Code</th>
                   <th align="center" bgcolor="cyan">Subject Name</th>
                   </tr>

                    <tr>
                   <td align="center" bgcolor="cyan">1.</td>
                   <td align="center" bgcolor="cyan">19AI414</td>
                   <td align="center" bgcolor="cyan">Fundamentals Of Web Application Development (web application)</td>
                   </tr>

                    <tr>
                   <th align="center" bgcolor="cyan">2.</th>
                   <td align="center" bgcolor="cyan">19AI301</th>
                   <td align="center" bgcolor="cyan">Python Programming (python)</th>
                   </tr>

                    <tr>
                   <th align="center" bgcolor="cyan">3.</th>
                   <td align="center" bgcolor="cyan">19CS305</th>
                   <td align="center" bgcolor="cyan">Computer Architecture</th>
                   </tr>

                    <tr>
                   <th align="center" bgcolor="cyan">4.</th>
                   <td align="center" bgcolor="cyan">19EY701</th>
                   <td align="center" bgcolor="cyan"> Soft Skills </th>
                   </tr>

                    <tr>
                   <th align="center" bgcolor="cyan">5.</th>
                   <td align="center" bgcolor="cyan">19MA222</th>
                   <td align="center" bgcolor="cyan">Probablity And Queing Models (Maths)</th>
                   </tr>

                    <tr>
                   <th align="center" bgcolor="cyan">6.</th>
                   <td align="center" bgcolor="cyan">19PH214</th>
                   <td align="center" bgcolor="cyan">Physics For Qantum Computing (physics)</th>
                   </tr>

         </table>    
    </body>
</html>
```
## OUTPUT
![Alt text](<Screenshot (14).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
