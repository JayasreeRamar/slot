# Ex03 Time Table
## Date: 15.11.2023

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
<<html>
    <title>title</title>
        <body>
 <img src="/static/logo.png">
           <table border="6" cellspacing="4" cellpadding="4">
               <caption>MY TIME TABLE</caption>
 
                   <tr>
                     <th bgcolor="yellow" align="center">day/time</th>
                     <th bgcolor="yellow" align="center">8:9 am</th>
                     <th bgcolor="yellow" align="center">9:10 am</th>
                     <th bgcolor="yellow" align="center">10:11 am</th>
                     <th bgcolor="yellow" align="center">11:12 am</th>
                     <th bgcolor="yellow" align="center">12:1 pm</th>
                     <th bgcolor="yellow" align="center">1:2 pm</th>
                     <th bgcolor="yellow" align="center">2:3 pm</th>
                     <th bgcolor="yellow" align="center">3:4 pm</th>
                     <th bgcolor="yellow" align="center">4:5 pm</th>
                  </tr>
 
                   <tr>
                     <th bgcolor="yellow" align="center" bgcolor="cyan">MONDAY</th>
                     <td colspan="2" align="center" bgcolor="cyan">soft skills</td> 
                     <td colspan="2" align="center" bgcolor="cyan">python</td>
                     <td align="center" bgcolor="cyan">LUNCH</td>
                     <td colspan="2" align="center" bgcolor="cyan">physics</td>
                     <th colspan="2" align="center" bgcolor="cyan">free</th>                   
                     </tr>
 
                   <tr>
                     <th bgcolor="yellow" align="center" >TUESDAY</th>
                     <th colspan="4" align="center" bgcolor="cyan">free</th>
                     <td align="center" bgcolor="cyan">LUNCH</td>
                     <th colspan="4" align="center" bgcolor="cyan">free</thh>
                     </tr>
 
                   <tr>
                     <th bgcolor="yellow" align="center">WEDNESDAY</th>
                     <td colspan="2" align="center" bgcolor="cyan">web application</td>
                     <td colspan="2" align="center" bgcolor="cyan">computer architecture</td>                    
                     <td align="center" bgcolor="cyan">LUNCH</td>
                     <td colspan="2" align="center" bgcolor="cyan">maths</td>                    
                     <th colspan="2" align="center" bgcolor="cyan">free</th>                    
                  </tr>
 
                   <tr>
                     <th bgcolor="yellow" align="center">THURSDAY</th>
                     <td colspan="2" align="center" bgcolor="cyan">maths</td>
                     <td colspan="2" align="center" bgcolor="cyan">web application</td>                    
                     <td align="center" bgcolor="cyan">LUNCH</td>
                     <td colspan="2" align="center" bgcolor="cyan">python</td>                    
                     <th colspan="2" align="center" bgcolor="cyan">free</th>                    
                  </tr>
 
                     <tr>
                     <th bgcolor="yellow" align="center">FRIDAY</th>
                     <th colspan="2" align="center" bgcolor="cyan">free</th>                    
                     <td align="center" bgcolor="cyan">computer architecture</td>
                     <th align="center" bgcolor="cyan">free</th>
                     <td align="center" bgcolor="cyan">LUNCH</td>
                     <td colspan="2" align="center" bgcolor="cyan">web application</td>                    
                     <td align="center" bgcolor="cyan">physics</td>
                     <th align="center" bgcolor="cyan">free</th>
                  </tr>
 
           </table>
           <table border="4" cellspacing="4" cellpadding="4">
 
 <caption>SUBJECT AND THEIR RESPECTIVE SUBJECT CODES </caption>
                      <tr>
                     <th align="center" bgcolor="white">S.NO</th>
                     <th align="center" bgcolor="white">Subject Code</th>
                     <th align="center" bgcolor="white">Subject Name</th>
                     </tr>
 
                      <tr>
                     <td align="center" bgcolor="white">1.</td>
                     <td align="center" bgcolor="white">19AI414</td>
                     <td align="center" bgcolor="white">Fundamentals Of Web Application Development (web application)</td>
                     </tr>
 
                      <tr>
                     <th align="center" bgcolor="white">2.</th>
                     <td align="center" bgcolor="white">19AI301</th>
                     <td align="center" bgcolor="white">Python Programming (python)</th>
                     </tr>
 
                      <tr>
                     <th align="center" bgcolor="white">3.</th>
                     <td align="center" bgcolor="white">19CS305</th>
                     <td align="center" bgcolor="white">Computer Architecture</th>
                     </tr>
 
                      <tr>
                     <th align="center" bgcolor="white">4.</th>
                     <td align="center" bgcolor="white">19EY701</th>
                     <td align="center" bgcolor="white"> Soft Skills </th>
                     </tr>
 
                      <tr>
                     <th align="center" bgcolor="white">5.</th>
                     <td align="center" bgcolor="white">19MA222</th>
                     <td align="center" bgcolor="white">Probablity And Queing Models (Maths)</th>
                     </tr>
 
                      <tr>
                     <th align="center" bgcolor="white">6.</th>
                     <td align="center" bgcolor="white">19PH214</th>
                     <td align="center" bgcolor="white">Physics For Qantum Computing (physics)</th>
                     </tr>
 
           </table>    
       </body>
 </html>
```

## OUTPUT
![Alt text](<Screenshot (12).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
