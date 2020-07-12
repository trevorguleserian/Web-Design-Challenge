<!DOCTYPE html>
<html lang="en-us">



<head>

    <meta charset="UTF-8">
    <title>Lattitude Home</title>
      
        <!-- Bootstrap CDN -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
      
</head>

<body style="background-color: rgb(250, 249, 249);">

  <nav class="navbar navbar fixed-top navbar-expand-lg navbar-light bg-light">
    <a style="color: darkcyan;" class="navbar-brand" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/Index.html#">Lattitude</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/data.html#">Data</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/comparison.html">Comparisons</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Plots
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/max_temp.html">Max Tempurature</a>
            <a class="dropdown-item" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/humidity.html">Humidity</a>
            <a class="dropdown-item" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/cloudiness.html">Cloudiness</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/wind_speed.html">Wind Speed</a>
          </div>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Dropdown
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>
      </ul>
    </div>
  </nav>

      
    <div class="container">
      <div class="jumbotron">
        <h1 style="color: darkcyan; text-align: center;" class="display-4">Welcome to Lattitude</h1>
        
        <hr class="my-4">
        <p style="text-align: center;">An open source data science project proving that weather factors change depending on relation to the equater. The data was obtained using API calls to several websites. It includes thousands of cities. You can see all the data by navigating to the data page on this website. Feel free to do your own alalysis with the following data.  </p>
      </div>
    



        <div class="row">
            <div style="text-align: center; align-content: center;" class="col-md-6">
              <div class="card" style="width: 30rem;">
                <img src="assets/images/fig1.png" class="card-img-top" alt="Max Tempurature">
                <div class="card-body">
                  <h5 class="card-title">Max Tempurature</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a style="background-color: darkcyan;" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/max_temp.html" class="btn btn-primary">Max Tempurature</a>
                </div>
              </div>
              
                
            </div>
            <div style="text-align:center;align-content: center;" class="col-md-6">
              <div class="card" style="width: 30rem;">
                <img src="assets/images/fig2.png" class="card-img-top" alt="Humidity">
                <div class="card-body">
                  <h5 class="card-title">Humidity</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a style="background-color: darkcyan;" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/humidity.html" class="btn btn-primary">Humidity</a>
                </div>
              </div>
            </div>
        </div>
        <div class="row">
            <div style="text-align: center;align-content: center;" class="col-md-6">
              <div class="card" style="width: 30rem;">
                <img src="assets/images/fig3.png" class="card-img-top" alt="Cloudiness">
                <div class="card-body">
                  <h5 class="card-title">Cloudiness</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a style="background-color: darkcyan;" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/cloudiness.html" class="btn btn-primary">Cloudiness</a>
                </div>
              </div> 
            </div>

        
            <div style="text-align: center;align-content: center;" class="col-md-6">
              <div class="card" style="width: 30rem;">
                <img src="assets/images/fig4.png" class="card-img-top" alt="Wind Speed">
                <div class="card-body">
                  <h5 class="card-title">Wind Speed</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a style="background-color: darkcyan;" href="http://localhost:52330/Web-Design-Challenge/WebVisualizations/html/wind_speed.html" class="btn btn-primary">Wind Speed</a>
                </div>
              </div>
        </div>
    </div>
</body>
      
