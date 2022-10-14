# booking_webpage---Dhivi
webpage for booking tour.....
<!DOCTYPE html>
<html>
<head>
    <title>tourist_com</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
    <link href="1stcss.css" rel="stylesheet">
    <style>
.card {
    background-image: url('india-in-pictures-beautiful-places-to-photograph-golden-temple-amritsar.jpg');
   
    text-align: center;
    margin-bottom: 250px;
    margin-left: 250px;
    margin-right: 250px;
    background-size: cover
}
    .main{
    background-image: url('india-in-pictures-beautiful-places-to-photograph-gateway-of-india-mumbai.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    
    }
    .price {
    color: yellow;
    font-size: 18px;
    }
    
h3{
    font-size: 50px;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    margin-top: 150px;
}
.links{
text-align: right;
font-size: x-large;
font-style: italic;

}
#main{
    text-align: center;
    color: rgb(231, 17, 17);
}
input{
    width: 250px !important;
    margin-bottom: 10px ;
    margin-left: auto ;
    margin-right: auto ;
}
</style>

    </head>
    <body class="main">
    <fieldset class="center">
          
        <h3 style="text-align:center"><i>WWW.tourist_place.com</i></h3>
    <br>
    <hr>
    <div class="card">
    <h1><b>Explore Best In India</b></h1>
    <h2 class="price">INR 30,000/-</h2>
    
    <b>
    <li>Manali</li>
    <li>idukki</li>
    <li>kodaikanal</li>
    <li>Andaman and Nicobar</li>
    <li>vagamon</li>
    <li>varkala</li>
    </b>
    
 
    <p><button type="button" class="btn btn-primary">Book_Now</button></p>


    </div>
    </fieldset>
    <div id="main">
        <h1>Save Time,Save money!</h1>
        <p><i>Sign up and we will send the best deals of the day...</i></p>
        <input type="text" aria-label="First name" class="form-control" placeholder="email address.." required>
        <input type="password" aria-label="Last name" class="form-control" placeholder="password.." required>


        <button type="button" class="btn btn-outline-dark">Log_In</button>>
    </div>
    <hr>
    <section class="links">
    <footer>
        <a href="#" class="link-primary"><b>HOME</b></a>|
        <a href="#" class="link-secondary"><b>PHOTOS</b></a>|
        <a href="#" class="link-success"><b>CONTACT_DETAILS</b></a>|
        <a href="#" class="link-danger"><b>ABOUT_US</b>
        </a>|
    </footer>
    </section>
    
    </body>
</html>
