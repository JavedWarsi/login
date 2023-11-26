<!--# login
1st login
<br>
Author-Javed
-->
<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>loginForm</title>
  <style>
    form{
      height:300px;
      width: 280px;
      border:2px solid #ccc;
      background-color: white;
      margin:40px;
      padding:8px;
      border-radius: 10%;
      margin-top: 200px;
      content: center;
    }
    body{
      background-color: #ccc;
    }
    div{
      margin:auto;
    }
    input{
      box:none;
    }
    button{
      font-size:16px;
      width:180px;
      background-color:blue;
    }
    input[type=text] {
  border: none;
  border-bottom: 2px solid grey;
}
     input[type=password]{
       border:none;
       border-bottom:2px solid grey;
     }
  </style>
</head>

<body>
  <div><center>
    <form>
      <h1>Login</h1>
      
      <input type="text" placeholder="Username"><br><br>
      <input type="password" placeholder="password"><br><br>
      <button disabled>Submit</button>
  
  </form></center>
  </div>

</body>

</html>
