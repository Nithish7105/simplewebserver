# EX01 Developing a Simple Webserver
## Date:
27/3/2024
## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <nav class="navbar bg-body-tertiary">
        <div class="container-fluid">
          <a class="navbar-brand"><i class="bi bi-instagram"></i>
            <a class="navbar_brand"></a><i class="bi bi-youtube"></i>
            <a class="navbar_brand"><i class="bi bi-facebook"></i>
              <a class="navbar_brand"><i class="bi bi-twitter"></i></a>
          <a class="navbar-brand">Menu</a>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </nav>
      <div style="display:flex;">
        <div style="width:30%;"> <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-03-06 140152.png" class="img-fluid" alt="..."></div>
        <div style="width:5%;"> </div>
        <div style="width: 45%;">Home</div>
        <div style="width:20%;background-color:gray;">For Admission<br>
             <i class="bi bi-whatsapp"></i>8956875295</div>
      </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <div>
         <div><div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false">
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-03-06 140418.png" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-03-06 140356.png" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-03-06 140307.png" class="d-block w-100" alt="...">
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
    </div>
</body>
</html>

## OUTPUT:
![alt text](image.png)


## RESULT:
The program for implementing simple webserver is executed successfully.
