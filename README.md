<!DOCTYPE html>
<html style="text-align: right;">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
    <title>Tryffer</title>
    <link rel="stylesheet" href="assets/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.2.0/aos.css">
    <link rel="stylesheet" href="assets/css/styles.css">
        <link rel="stylesheet" href="assets/css/Footer-Dark.css">
    
</head>
<!--Black Navbar-->
<body style="background: url(assets/img/Ciudad%20vector%202.png) fixed center bottom no-repeat ;  background-color: gray ; width: 100%; height: 400px;">
    <nav class="navbar navbar-light navbar-expand-lg" style="background-color: #2d2d2d">
        <a class="navbar-brand" style="text-shadow:2px 2px #025fa6; color: #ffffff" href="index.html">Tryffer</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"       aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item">
                            <a class="nav-link" style="color: #ffffff" href="negocio.html">Negocio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" style="color: #ffffff" href="oferta.html">Oferta</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" style="color: #ffffff" href="#" data-toggle="modal" data-target="#loginmodal">Login</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" style="color: #ffffff" href="#"data-toggle="modal" data-target="#signupmodal">Sign up</a>
                        </li>
                    </ul>
                </div>
<!--Blue Navbar-->
</nav>
    <nav class="navbar navbar-light navbar-expand-lg" style="background-color: #025fa6">
</nav>
<!--Container Tryffer logo-->
    <div class="container w-50 p-3">
        <div class="row">
            <div class="col-xl-9 mx-auto " class="w-25 p-3" >
                <object data="Tryffer-logo.svg" type="image/svg+xml"></object>
            </div>
        </div>
    </div>
<!--Container Tryffer Description-->
<div class="container">
    <div class="row">
        <div class="col-xl-9 mx-auto " class="w-25 p-3" >
            <font class="text-center" style="text-shadow:2px 2px 5px #025fa6; color: #ffffff" size="15px">Las mejores ofertas personalizadas al alcance de un click 🧡</font>
        </div>
    </div>
</div>
<!--Container Tryffer Buttom-->
<div class="container w-25 p-3">
    <div class="row">
        <div class="col-xl-9 mx-auto " class="w-25 p-3" >
            <object data="Leer mas.svg" type="image/svg+xml"></object>
        </div>
    </div>
</div>
<!-- Signup Button trigger modal -->
<div class="modal fade" id="signupmodal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Join us!</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
            </div>
            <div class="modal-body">
                <form id="signup-form">
                    <div class="form-group">
                        <input type="email" id="signup-email" class="form-control" placeholder="email" required>
                    </div>
                    <div class="form-group">
                        <input type="password" id="signup-password" class="form-control" placeholder="password" required>
                    </div>
                    <button type="submit" class="btn btn-primary">Sign Up</button>
                </form>
            </div>
        </div>
    </div>
</div>
<!-- Login Button trigger modal -->
<div class="modal fade" id="loginmodal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Welcome back!</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
            </div>
            <div class="modal-body">
                <form id="login-form">
                    <div class="form-group">
                        <input type="email" id="login-email" class="form-control" placeholder="email" required>
                    </div>
                    <div class="form-group">
                        <input type="password" id="login-password" class="form-control" placeholder="password" required>
                    </div>
                    <button type="submit" class="btn btn-primary">Login</button>
                </form>
            </div>
        </div>
    </div>
</div>
<!-- Footer -->
    <!--Scripts de Firebase-->
<script src="https://www.gstatic.com/firebasejs/7.23.0/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/7.23.0/firebase-analytics.js"></script>
<script src="https://www.gstatic.com/firebasejs/7.23.0/firebase-firestore.js"></script>
<script src="https://www.gstatic.com/firebasejs/7.23.0/firebase-auth.js"></script>

<script>

var firebaseConfig = {
    apiKey: "AIzaSyBlYkJU5jhlxDnBwX7Zc2RMOciqUvVQs54",
    authDomain: "datac-app.firebaseapp.com",
    databaseURL: "https://datac-app.firebaseio.com",
    projectId: "datac-app",
    storageBucket: "datac-app.appspot.com",
    messagingSenderId: "642150143792",
    appId: "1:642150143792:web:23b1c0c740f62d9a0e9af5",
    measurementId: "G-GG78NXDBYX"
};
  // Initialize Firebase
firebase.initializeApp(firebaseConfig);
firebase.analytics();
</script>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous">
</script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous">
</script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous">
</script>

    <script src="index.js"></script>
    <script src="assets/js/jquery.min.js"></script>
    <script src="assets/bootstrap/js/bootstrap.min.js"></script>
    <script src="assets/js/bs-init.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.2.0/aos.js">
    </script>
</body>

</html>
