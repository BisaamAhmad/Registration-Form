# Registration-Form
Designed Form
HTML
<html>
<head>
    <meta charset="UTF-8">
    <title>Registration Form</title>
    <link rel="stylesheet" href="form.css">
</head>
<body>
    <form>
    <center>
        <div class="box">
    <div class="reg">
        <h1><u>Registration form</u></h1>
    </div>
    <div class="label">
        <label for="FirstName">First Name</label>
        <input type="text" id="FirstName"><br><br>
        <label for="LastName">Last Name</label>
        <input type="text" id="LastName"><br><br>
        <label for="NickName">Nick Name</label>
        <input type="text" id="NickName"><br><br>
    </div>
    <div class="email">
        <label for="email">email</label>
        <input type="email" id="email"><br><br>
    </div>
    <div class="pas">
        <label for="Password">Password</label>
        <input type="password" id="Password"><br><br>
    </div>
    <div class="radio">
        <div class="gender">
            <label for="radio">Gender</label>
        </div>
        <div class="option">
        <input type="radio" id="Male" name="fav_language" value="Male">
        <lable for="Male">Male</lable>
        <input type="radio" id="Female" name="fav_language" value="Female">
        <lable for="Female">Female</lable>
        <input type="radio" id="Others" name="fav_language" value="Others">
        <lable for="Others">Others</lable>
    </div>
    </div>
    <br>
    <div class="Mobile">
        <label for="Mobile">Mobile Number</label>
        <input type="Monile" id="Mobile"><br><br>
    </div>
    <div class="submit">
        <label for="Address">Address</label>

        <textarea name="text" id="text" cols="27" rows="5"></textarea>
     <br><br>
     <button type="submit">submit</button>
     <button type="reset">reset</button>

    </div>
    </div>
</center>
</form>
</body>
</html>










CSS
body{
    background:url(https://cdn5.vectorstock.com/i/1000x1000/70/59/technology-background-color-for-web-and-design-vector-34277059.jpg);
    margin: 0;
    padding: 0;
    
   
}
.reg h1{
    text-align: center;
    padding-top: 40px;
}

.label label{
    padding-left: 0px;
    font-size: 18px;
    gap: 10px;
}
.label input{
    width: 40%;
    height: 30px;
    margin-left: 90px;
    border-color: hsl(0, 0%, 90%);
}
.box{
    width: 553px;
    height: 582px;
    background-color: hsl(0, 0%, 90%);
    margin-top: 40px;
}
.email input{
    width: 40%;
    height: 30px;
    margin-left: 110px;
    border-color: hsl(0, 0%, 90%);
}
.email label{
    padding-left: 10px;
    padding-right: 5PX;
    margin-right: 10PX;
    font-size: 18px;
    gap: px;
}
.pas input{
    width: 40%;
    height: 30px;
    margin-left: 105px;
    padding-right: 30px;
    border-color: hsl(0, 0%, 90%);
}
.pas label{
    padding-left: 0px;
    font-size: 18px;
}
.gender{
    display: flex;
    padding-left: 80px;
    padding-right: 5PX;
    margin-right: 10PX;
    font-size: 18px;
}

.radio{
    display: flex;
    align-items: center;
    gap: 90px;
}
.mobile input{
    width: 40%;
    height: 30px;
    margin-left: 60px;
    border-color: hsl(0, 0%, 90%);
}
.mobile label{
    padding-left: 0px;
    font-size: 18px;

}
.submit label{
    margin-right: 140px;
    font-size: 18px;
}
.submit textarea{
    margin-left: -40px;
}
.option{
    padding-right: 20px;
    margin-right: 20px;
}
.submit button:hover{
    background-color: #00d6fc;
}
