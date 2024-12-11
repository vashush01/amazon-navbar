# amazon-navbar
this is the most basic navbar of amazon 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Css-Level-2</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="navbar">
    <a id="logo">amazon.in</a>
    <a hrf="#"> Account</a>
    <a href="#"> My Cart</a>
    <a href="#"> Contact US</a>
        <input placeholder="search Amazon.in">
        <button>Search</button>
    </div>
</body>
</html>
THE FOLLOWING BELOW CONTAINS CSS 
*{
    padding:0;
    margin:0;
    color:white;
    
}

#navbar{
    height: 60px;
    background-color: #0f1111;
}
button{
    background-color: #f08804;
}
#logo{
    background-color: #f08804;
    font-size: 25px;
}
a{
    margin-right: 200px;
    text-decoration: none;
}
