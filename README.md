<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset ="UTF-8">
    <meta name="viewpoint" content="width=device-width" initial-scale="1.0">
    <title>Patient History Form</title>
    <style>
        h2{
            color: blue;
        }
        h3{
            color: green;
        }
        input{
            width: 10%;
            padding: 10px;
            margin: 10px;
            border: 2px solid black;
            border-radius: 5px;
        }
        button{
            width: 20%;
            padding: 10px;
            margin: 10px;
            border: 2px solid black;
            border-radius: 5px;
            background-color: green;
            color: white;
        }
        button:hover{
            background-color: blue;
        }
    

    </style>
   
</head>
<body>
    <h2>Patient History Form</h2>
    <h3>Personal Information</h3>
  
    Name: <input type="text"placeholder="Enter your name"><br><br>
    Date of Birth: <input type="date" placeholder="Date of birth"><br><br>
    Age:    <input type="number" placeholder="Enter your age"><br><br>
    Select Gender: <input type="radio" name="Gender">male
                    <input type="radio" name="Gender">female<br><br>
    Date of appointment: <input type="date" placeholder="Select date"><br><br>
    Contact details:<input type="number" placeholder="Enter phone number"><br><br>
    Time: <input type="time" placeholder="Select time"><br><br>
    <button onclick="Press()">Submit</button>
    <script>
        function Press(){
            alert ('Form Submitted Successfully');
        }
    </script>




</body>
</html># Patient-History
