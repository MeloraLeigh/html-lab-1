<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Project Showcase</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">My Projects</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#carousel">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#projects">Projects</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
            </ul>
        </div>
    </nav>

<div id="carousel" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://via.placeholder.com/800x400?text=Slide+1" class="d-block w-100" alt="Slide 1">
            </div>
            <div class="carousel-item">
                <img src="https://via.placeholder.com/800x400?text=Slide+2" class="d-block w-100" alt="Slide 2">
            </div>
            <div class="carousel-item">
                <img src="https://via.placeholder.com/800x400?text=Slide+3" class="d-block w-100" alt="Slide 3">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carousel" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carousel" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>

  <div class="container my-5" id="projects">
        <h2 class="text-center mb-4">My Projects</h2>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="https://via.placeholder.com/300x200?text=Project+1" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title">Project 1</h5>
                        <p class="card-text">Description of Project 1 goes here. It highlights the main features and technologies used.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="https://via.placeholder.com/300x200?text=Project+2" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title">Project 2</h5>
                        <p class="card-text">Description of Project 2 goes here. It highlights the main features and technologies used.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="https://via.placeholder.com/300x200?text=Project+3" class="card-img-top" alt="Project 3">
                    <div class="card-body">
                        <h5 class="card-title">Project 3</h5>
                        <p class="card-text">Description of Project 3 goes here. It highlights the main features and technologies used.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

</body>

</html>
