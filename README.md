Source Code:
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Registration Form</title>
 <style>
 table {
 width: 50%;
 margin: 20px auto;
 border-collapse: collapse;
 }
 td, th {
 padding: 10px;
 text-align: left;
 border: 1px solid #ccc;
 }
 h2 {
 text-align: center;
 }
 input[type="text"], input[type="password"], input[type="number"], input[type="date"], select {
 width: 100%;
 padding: 8px;
 margin: 5px 0;
 border: 1px solid #ccc;
 }
 input[type="submit"], input[type="reset"] {
 width: 48%;
 padding: 10px;
 margin: 10px 1%;
 background-color: #4CAF50;
 color: white;
 border: none;
 cursor: pointer;
 }
 input[type="submit"]:hover, input[type="reset"]:hover {
 background-color: #45a049;
 }
 </style>
</head>
<body>
 <h2>Registration Form</h2>
 <form action="#" method="POST">
 <table>
 <tr>
 <th colspan="2">Personal Information</th>
 </tr>
 <tr>
 <td>Full Name:</td>
 <td><input type="text" name="fullname" required></td>
 </tr>
 <tr>
 <td>Email:</td>
 <td><input type="text" name="email" required></td>
 </tr>
 <tr>
 <td>Password:</td>
 <td><input type="password" name="password" required></td>
 </tr>
 <tr>
 <td>Phone Number:</td>
 <td><input type="number" name="phone" required></td>
 </tr>
 <tr>
 <td>Date of Birth:</td>
 <td><input type="date" name="dob" required></td>
 </tr>
 <tr>
 <th colspan="2">Gender</th>
 </tr>
 <tr>
 <td>Gender:</td>
 <td>
 <input type="radio" name="gender" value="Male" required> Male
 <input type="radio" name="gender" value="Female" required> Female
 <input type="radio" name="gender" value="Other" required> Other
 </td>
 </tr>
 <tr>
 <th colspan="2">Preferences</th>
 </tr>
 <tr>
 <td>Hobbies:</td>
 <td>
 <input type="checkbox" name="hobbies" value="Reading"> Reading
 <input type="checkbox" name="hobbies" value="Traveling"> Traveling
 <input type="checkbox" name="hobbies" value="Music"> Music
 </td>
 </tr>
 <tr>
 <td>Country:</td>
 <td>
 <select name="country">
 <option value="USA">USA</option>
 <option value="Canada">Canada</option>
 <option value="UK">UK</option>
 <option value="India">India</option>
 <option value="Australia">Australia</option>
 </select>
 </td>
 </tr>
 <tr>
 <td colspan="2" style="text-align: center;">
 <input type="submit" value="Submit">
 <input type="reset" value="Reset">
 </td>
 </tr>
 </table>
 </form>
</body>
</html>
