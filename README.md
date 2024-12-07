# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
   <title> TIME TABLE </title>
   <body>
   <center>
   <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfVHM7lQHBY3fMmzXE1m0bYnMg3dsccFDu2g&s"height="100"width="600">

<br>
<table border="3" bgcolor="white" cellspacing="10" cellpadding="10">
<caption> SLOT TIME TABLE - DHARURU YOGESH (24000330)</caption>
<br>

<tr bgcolor="white">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday</th>
</tr>

<tr align="center">
   <th bgcolor="white"> 8-10 </th>s
   <td> FREE SLOT</td>
   <td> English</td>
   <td> FREE SLOT</td>
   <td>EDM </td>
   <td> English</td>
   <td>EDM</td>
</tr>

<tr align="center">
    <th bgcolor="white"> 10-12 </th>
    <td>Physics</td>
    <td> FREE SLOT</td>
    <td> CA</td>
    <td> FREE SLOT</td>
    <td> FWAB</td>
    <td> FWAD</td>
</tr>

<tr align ="center">
    <th bgcolor="white"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH </td>
</tr>

<tr align ="center">
    <th bgcolor="white"> 1-3 </th>
    <td>  FWAD </td>
    <td> CA</td>
    <td>  MENTOR MEETING</td>
    <td> DE</td>
    <td>  CA</td>
    <td> DE</td>
</tr>

<tr align ="center">
    <th bgcolor="white"> 3-5 </th>
    
    <td>  FREE SLOT</td>
    <td> FREE SLOT</td>
    <td> FREE SLOT</td>
    <td> FREE SLOT </td>
    <td> FREE SLOT</td>
    <td> FREE SLOT</td>
</tr>

</tr>

</table>
<br>
<table border="7" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>

<tr align="center">
<td> 1. </td>
<td> 19AI414 </td>
<td> Fundamentals of Web Applicaton Development(FWAD) </td>
</tr>

<tr align="center">
<td> 2. </td>
<td> 19AI302</td>
<td> EDM </td>
</tr>

<tr align="center">
<td> 3. </td>
<td> 19EY708</td>
<td> CD</td>
</tr>

<tr align="center">
<td> 4. </td>
<td> 19EN101</td>
<td> English </td>
</tr>

<tr align="center">
<td> 5. </td>
<td> 19EE404</td>
<td> Physics</td>
</tr>

<tr align="center">
<td> 6. </td>
<td> 19CS305</td>
<td>CA</td>
</tr>
```
# OUTPUT
![Screenshot (22)](https://github.com/user-attachments/assets/c4cfb1ec-73f4-46f1-bf49-c478592a4f4b)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
