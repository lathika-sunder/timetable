# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program


# CODE

```
<!DOCTYPE html>
<html>
<head>
<title>TIME TABLE</title>
<style>
    body{
        background-color: rgb(5, 5, 5); color:aqua 
    }
</style>
</head>
<body>
    <img src=logo.png style="width: 40cm;">
    <h2>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <u>TIME TABLE</u></h2>
    <table border="1" style="width: 40cm; border-color: bisque;">
        <tr>
            <th style="size: 10800px;">DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
        </tr>
        <tr>
            <td style="background-color:rgb(167, 1, 1)">MONDAY</td>
            <td>19AI401</td>
            <td>19MA221</td>
            <td>lunch break</td>
            <td>19MA220</td>
        </tr>
        <tr>
            <td style="background-color:rgb(167, 1, 1)">TUESDAY</td>
            <td style="background-color:white color:black">-</td>
            <td>19AI302</td>
            <td>ECA051</td>
            <td>19AI303</td>
        </tr>
        <tr>
            <td style="background-color:rgb(167, 1, 1)">WEDNESDAY</td>
            <td style="background-color:white color:black">-</td>
            <td>19AI301</td>
            <td>lunch break</td>
            <td>19AI401</td>
        </tr>
        <tr>
            <td style="background-color:rgb(167, 1, 1)">THURSDAY</td>
            <td>19AI303</td>
            <td>19AI301</td>
            <td>lunch break</td>
            <td>19AI302</td>
        </tr>
        <tr>
            <td style="background-color:rgb(167, 1, 1)">FRIDAY</td>
            <td>19EY701</td>
            <td>19MA220</td>
            <td>lunch break</td>
            <td>19AI401</td>
        </tr>
    </table>
<hr/><b>COURSE TITTLE:</b>
<ul  style="background-color:rgb(106, 0, 133) ; color:white">19AI401 - Fundamentals Of Web Technology And Laboratory<br/>
19MA220 - Mathematics For Artificial Intelligence<br/>
19MA221 - Linear Algebra Laboratory<br/>
19AI301 - Python Programming<br/>
19AI302 - Engineering Design And Modelling<br/>
19AI303 - Engineering Mechanics And Product Development<br/>
19EY701 - Soft Skills<br/>
19AI401 - Web Technology
ECA051-AD - Mentoring
</ul>
</body>
</html>
```

# OUPUT

![output](./1.png)
