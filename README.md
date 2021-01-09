# index.htmal
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

<body>
    <a href="https://www.google.com/">Home</a> | <a href="https://www.google.com/">Contact</a> | <a
        href="https://www.google.com/">About</a> |<a href="https://www.google.com/">Projects</a>
    <h1>Student Registration Form</h1>
    <form>
        <label for="fname">First name:</label><br>
        <input type="text" id="fname" name="fname"><br>
        <label for="lname">Last name:</label><br>
        <input type="text" id="lname" name="lname"><br><br>
        <label for="dob">DOB:</label><br>
        <input type="date" id="dob" name="dob"><br><br>
        <label for="father">Father's name:</label><br>
        <input type="text" id="father" name="father"><br><br>

        <label>Document:</label><br>
        <input type="radio" id="aadhar" name="document" value="aadhar">
        <label for="aadhar">Aadhar</label><br>
        <input type="radio" id="driving license" name="document" value="driving license">
        <label for="female">Driving License</label><br>
        <input type="radio" id="other" name="document" value="other">
        <label for="other">Other</label><br><br>

        <label for="gender">Gender:</label><br>
        <select name="gender" id="gender">
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        <br><br>


        Description :<br>
        <textarea rows="5" cols="40" name="description"></textarea><br>
        <input type="checkbox" value="Confirm">
        <label for="Confirm">Confirm</label><br><br>
        <input type="submit">
    </form>
</body>
<footer>
    Made By Geekhaven
    <i class="fa fa-facebook-square" aria-hidden="true"></i>
    <i class="fa fa-instagram" aria-hidden="true"></i>
    <i class="fa fa-twitter-square" aria-hidden="true"></i>
    <i class="fa fa-reddit-square" aria-hidden="true"></i>
</footer>

</html>
