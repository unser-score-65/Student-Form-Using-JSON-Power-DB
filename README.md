# Student-Form-Using-JSON-Power-DB

## _Introduction:_

_JsonPowerDB_ is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database.

## _Benifits of JSONPowerDB:_

-Faster Development.

-Better Performance.

-Low Development and Maintenance Cost.

-Low Infrastucture Cost.

-Improved Time to Market.

-Minimum Learning Curve.

## _Description:_

A simple form for maintaining student record , using Login2Explore web API.

Student Enrollment Form that will store data in STUDENT-TABLE relation of SCHOOL-DB database.

Input Fields: {Roll-No, Full-Name, Class, Birth-Date, Address, Enrollment-Date}

Primary key: Roll No.

## _Functioning_

There are three control buttons [Save], [Update] and [Reset] at the bottom of the form. On page load or any control button click, an empty form will be displayed and the cursor will remain at the first input field in the form which will have the primary key (Roll No.) in the relation. All other fields and buttons should be disabled at this time.

Enter data in the field having primary key and,

-If the primary key value does NOT exist in the database, [Save] and [Reset] buttons are enabled and the cursor is moved to the next field, allowing you to enter data in the form.

  The data should be valid i.e. no empty fields.

  Complete the data entry form and click the [Save] button to store the data in the database and go to initial state.

-If the primary key value is present in the database, data is displayed in the form. [Update] and [Reset] buttons are enabled and the cursor is moved to the next field in the form. Now, the primary key field is kept disabled and allow users to change other form fields.

  The data should be valid i.e. no empty fields.

  Click on [Update] button to update the data in the database and go to initial state.

 Click [Reset] to reset the form .
 
 ## _Release History_
 
 (i) 8 Januaury, 2023 (Initial Commit)

## _Sources:_

https://careers.login2explore.com/

https://login2explore.com/jpdb/docs.html

http://api.login2explore.com:5577/user/register_dev.html
