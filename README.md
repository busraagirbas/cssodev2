# cssodev2
Kodluyoruz Eğitimi CSS Ödev 2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <link rel="stylesheet" href="google.css">
</head>
<body>
    <div class="content">
        <img style="display: block; margin: auto;" width="400" src="https://web.archive.org/web/19990504112211im_/http://www.google.com/google.jpg" alt="google.1998">
    </div>
    
    <div style="text-align: center;" class="content">
    Search the web using Google! <br>
    <input type="text" size="50"> <br>
    <input type="button" value="Google Search">
    <input type="button" value="I'm feeling lucy">
    </div>

    <div class="content">
        <div class="box1">
        Special Searches <br>
        <a href="">Standford Search</a><br>
        <a href="">Linux Search</a>
        </div>

        <div class="box2">
            <a href="">Help!</a> <br>
            <a href="">About Google!</a><br>
            <a href="">Company Info</a><br>
            <a href="">Google! Logos</a>
        </div>

        <div class="box3">
        Get Google <br>
        Updates Monthly: <br>
        <input type="text" value="your e-mail" size="25"><br>
        <input type="button" value="Subscribe">
        <a href="">Archive</a>
        </div>

        <div class="clear"></div>
        <div class="content" style="text-align: center;">
            <p>Copyright ©1998 Google Inc.</p>
    </div>
</body>
</html>

.content{
    width: 1350px;
    height: min-content;
    margin-bottom: 15px;
    margin-top: 30px
}

.box1{
    width: 39%;
    height: 85px;
    float: left;
    text-align: center;
    background-color: #84e9df;
    font-size: 18px;
}

.box2{
    background-color: #6ae2d6;
    width: 20%;
    height: 85px;
    float: left;
    text-align: center;
    font-size: 15px;
    margin:0 0.2%;
}

.box3{
    background-color: #53c5b9;
    width: 39%;
    height: 85px;
    text-align: center;
    font-size: 15px;
    float: left;    

}

.clear{
    clear: both;
}
