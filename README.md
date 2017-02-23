# tlphotosite
Intro to HTML/CSS Final Project 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Taryn Lewis, Photographer</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css?family=Lato:100,300" rel="stylesheet">
</head>
<body>

<!--- Header -->

<div class="container">
<div class="row">
    <div class="col-md-6">
        <img class="title-logo" src="images/cameratattoo-1.jpg" alt="Logo">
    </div>
    <div class="text-align:right col-md-6">
        <h1 class="title">Taryn Lewis</h1>
        <h4 class="subtitle">Photographer</h4>
    </div>
</div>

<!--- Separator -->

    <div class="row">
        <div class="col-md-12">
            <div class="separator">
            </div>
        </div>
    </div>

<!--- Main Image -->
    <div class="row">
        <div class="col-md-12">
            <img src="images/rileysteve-beach.jpg" class="main img-responsive" alt="Riley & Steve">
        </div>
    </div>

<!--- Featured Work -->

    <div class="row">
        <div class="col-md-12">
            <h2 class="text-mute featured">Featured Work</h2>
        </div>
    </div>

<!--- Work Sample -->

    <div class="row">
        <div class="col-md-4 samples" align="left">
            <img src="images/honey.jpg" class="Calmimg img-responsive" alt="Calm">
            <h3 class="sampletext text-uppercase calm">Calm</h3>
            <a href="http://github.com/udacity/calm"><p class="pleft">http://github.com/Calm</p></a>
        </div>

        <div class="col-md-4 samples" align="center">
            <img src="images/eric.jpg" class="Coffeeimg img-responsive" alt="Coffee">
            <h3 class="sampletext text-uppercase coffee">Coffee</h3>
            <a href="http://github.com/udacity/coffee"><p class="pcenter">http://github.com/udacity.com/Coffee</p></a>
        </div>

        <div class="col-md-4 samples" align="right">
            <img src="images/bribw.jpg" class="Powerimg img-responsive" alt="Power">
            <h3 class="sampletext text-uppercase power">Power</h3>
            <a href="http://github.com/udacity/power"><p class="pright">http://github.com/udacity/Power</p></a>
        </div>
    </div>

</div>
</body>
</html>
