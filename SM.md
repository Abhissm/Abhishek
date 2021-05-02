<!DOCTYPE html>
<html>
<head>
    <title></title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="/bootstrap/css/bootstrap.min.css">
  <script src="/bootstrap/js/jquery-3.4.1.min.js"></script>
  <script src="/bootstrap/js/popper.min.js"></script>
  <script src="/bootstrap/js/bootstrap.min.js"></script>
   
  <script>
     
  </script>
  </head>


<html>
    <head>
        <title>SUNIL GOLD SMITH</title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
    </head>

    <body>
        <header>
            <div class="container">
                <div class="logo">
                    <img src="SM11.jpg">
                </div>
                <ul>
                    <li class="active"><a href="#">HOME</a></li>
                    <li><a href="#">OFFERS</a></li>
                    <li><a href="#">CONTACT</a></li>
                    <li><a href="#">PROFILE</a></li>
                </ul>
            </div>
            <div class="title">
                <h1>SUNIL GOLD SMITH</h1>
            </div>
            <div class="title1">
                <h2>SINCE 1998</h2>
            </div>
            <div class="button">
                <a href="#" class="btn">WATCH VIDEO</a>
            <a href="#" class="btn">SUPPORT</a>
            </div>
            <form>
               
                <body>
                    <div class="container"></div>
                </body>
                <body>
                    <div class="col-md-6">
                        <div class="card card-info">
                            <div class="card-header">
                                <h2>LOGIN FORM</h2>
                    
                            </div>
                            <div class="container"></div>
                            <div class="card-body">
                               
                                <form>
                                    <div class="container"></div>
                                    <div class="form-group">
                                        <label>NAME</label>
                                        <input type="text" class="form-control" id="t1">
                                        <span class="text-danger" id="s1"></span>
                                    </div>
                                    <div class="form-group">
                                        <label>MOBILE NO</label>
                                        <input type="text" class="form-control" id="t2">
                                        <span class="text-danger" id="s2"></span>
                                    </div>
                                    <div class="form-group">
                                        <label>EMAIL ID</label>
                                        <input type="text" class="form-control" id="t3">
                                        <span class="text-danger" id="s3"></span>
                                    </div>
                                </form>
                            </div>
                            <div class="container"></div>
                            <div class="card-footer">
                                <input type="submit" value="Submit" class="btn btn-info" onclick="val()">
                            </div>
                        </div>
                    </div>
                    </body>
                    
                    
                    <script>
                         <div class="container"></div>
                        function val(){
                    
                            var name=document.getElementById("t1").value;
                            var mob=document.getElementById("t2").value;
                            var email=document.getElementById("t3").value;
                            var reg=/^[a-zA-a-zA-Z]+$/;
                            var reg1=/^[7-9]{1}[0-9]{9}$/;
                            var reg2=/^[a-zA-Z0-9]+@[a-z]+(.)+[a-z]*$/;
                    
                            if(name==""){
                                document.getElementById("s1").innerHTML="please enter name";
                            }
                            else if(reg.test(name)==false){
                                document.getElementById("s1").innerHTML="please enter valid name";
                            }
                            else{
                                document.getElementById("s1").innerHTML="";
                            }
                            if(mob==""){
                                document.getElementById("s2").innerHTML="please enter number";
                            }
                            else if(reg1.test(mob)==false){
                                document.getElementById("s2").innerHTML="please enter valid number";
                            }
                            else{
                                document.getElementById("s2").innerHTML="";
                            }
                            if(email==""){
                                document.getElementById("s3").innerHTML="please enter email";
                            }
                            else if(reg2.test(email)==false){
                                document.getElementById("s3").innerHTML="please enter valid email";
                            }
                            else{
                                document.getElementById("s3").innerHTML="";
                            }
                        }
                    </script>
            </form>
            <div class="container"></div>
            <form class="form-inline" action="">
                <input class="form-control mr-sm-2" type="text" placeholder="Search">
                <button class="btn btn-success" type="submit">Search</button>
            </form> 
        </header> 
    </body>
</html>
