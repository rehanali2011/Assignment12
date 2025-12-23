<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Student Registration Form</title>
<style>
body{
    font-family: Arial, sans-serif;
    background: #f2f2f2;
}
.form-container{
    width: 450px;
    margin: 40px auto;
    background: #fff;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
h2{
    text-align: center;
    margin-bottom: 20px;
}
label{
    display: block;
    margin-top: 10px;
    font-weight: bold;
}
input, select, textarea{
    width: 100%;
    padding: 8px;
    margin-top: 5px;
}
.gender{
    margin-top: 5px;
}
.gender input{
    width: auto;
}
button{
    margin-top: 20px;
    width: 100%;
    padding: 10px;
    background: #007bff;
    color: white;
    border: none;
    font-size: 16px;
    cursor: pointer;
}
button:hover{
    background: #0056b3;
}
</style>
</head>

<body>

<div class="form-container">
<h2>Student Registration Form</h2>

<form>
    <label>Full Name</label>
    <input type="text" placeholder="Enter your name" required>

    <label>Email</label>
    <input type="email" placeholder="Enter your email" required>

    <label>Password</label>
    <input type="password" required>

    <label>Gender</label>
    <div class="gender">
        <input type="radio" name="gender"> Male
        <input type="radio" name="gender"> Female
    </div>

    <label>Date of Birth</label>
    <input type="date">

    <label>Course</label>
    <select>
        <option>Select Course</option>
        <option>Web Development</option>
        <option>Graphic Designing</option>
        <option>App Development</option>
    </select>

    <label>Address</label>
    <textarea rows="3"></textarea>

    <button type="submit">Register</button>
</form>
</div>

</body>
</html>
