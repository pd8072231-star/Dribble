# Project Responsive Web Design using Bootstrap
## Date:11.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
bootstrap.html
```
<html>
<head>
  <title>Dribbble Style Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: pink;
    }
    .subtext {
      color:black;
    }
    .btn-learn {
      background-color: grey;
      color: blue;
    }
    .btn-signup {
      background-color: #ea4c89;
      color:blue;
    }
    .image-label {
      font-size: 14px;
      text-align: center;
      margin-top: 5px;
    }
    .navbar-brand {
      color: #ea4c89 !important;
      font-weight: bold;
      font-size: 20px;
    }
  </style>
</head>
<body>
    <h3>dribble nature</h3>

  


  <!-- Top Bar for Sign In / Sign Up -->
  <div class="d-flex justify-content-end p-3 bg-white">
    <a href="#" class="me-3 text-decoration-none">Sign in</a>
    <a href="#" class="btn btn-signup">Sign up</a>
  </div>

  <!-- Header Section -->
  <div class="text-center my-4">
    <h4 class="fw-bold">What are you working on?</h4>
    <p class="subtext">Dribbble is show and tell for designers.</p>
    <button class="btn btn-learn me-2">Learn more</button>
    <button class="btn btn-signup">Sign up</button>
  </div>

  <!-- Image Grid -->
  <div class="container">
    <!-- Row 1 -->
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="image1.png" class="img-fluid rounded">
        <div class="image-label">nature 1</div>
      </div>
      <div class="col-2 text-center">
        <img src="image2.png" class="img-fluid rounded">
        <div class="image-label">nature 2</div>
      </div>
      <div class="col-2 text-center">
        <img src="image3.png" class="img-fluid rounded">
        <div class="image-label">nature 3</div>
      </div>
      <div class="col-2 text-center">
        <img src="image4.png" class="img-fluid rounded">
        <div class="image-label">nature 4</div>
      </div>
      <div class="col-2 text-center">
        <img src="image5.png" class="img-fluid rounded">
        <div class="image-label">nature 5</div>
      </div>
      <div class="col-2 text-center">
        <img src="image6.png" class="img-fluid rounded">
        <div class="image-label">nature 6</div>
      </div>
    </div>

    <!-- Row 2 -->
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="image7.png" class="img-fluid rounded">
        <div class="image-label">nature 7</div>
      </div>
      <div class="col-2 text-center">
        <img src="image8.png" class="img-fluid rounded">
        <div class="image-label">nature 8</div>
      </div>
      <div class="col-2 text-center">
        <img src="image9.png" class="img-fluid rounded">
        <div class="image-label">nature 9</div>
      </div>
      <div class="col-2 text-center">
        <img src="image10.png" class="img-fluid rounded">
        <div class="image-label">nature 10</div>
      </div>
      <div class="col-2 text-center">
        <img src="image11.png" class="img-fluid rounded">
        <div class="image-label">nature 11</div>
      </div>
      <div class="col-2 text-center">
        <img src="image12.png" class="img-fluid rounded">
        <div class="image-label">nature 12</div>
      </div>
    </div>

    <!-- Row 3 -->
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="image13.png" class="img-fluid rounded">
        <div class="image-label">nature 13</div>
      </div>
      <div class="col-2 text-center">
        <img src="image14.png" class="img-fluid rounded">
        <div class="image-label">nature 14</div>
      </div>
      <div class="col-2 text-center">
        <img src="image15.png" class="img-fluid rounded">
        <div class="image-label">nature 15</div>
      </div>
      <div class="col-2 text-center">
        <img src="image16.png" class="img-fluid rounded">
        <div class="image-label">nature 16</div>
      </div>
      <div class="col-2 text-center">
        <img src="image17.png" class="img-fluid rounded">
        <div class="image-label">nature 17</div>
      </div>
      <div class="col-2 text-center">
        <img src="image18.png" class="img-fluid rounded">
        <div class="image-label">nature 18</div>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center">
    <p>&copy;Designed by P.Dharshini(25010127)</p>
  </footer>

</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (257).png>)
![alt text](<Screenshot (258).png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
