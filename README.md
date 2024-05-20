# sample-website
sample website using bootstrap

HTML :


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complex Bootstrap Website</title>
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="boot.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="#">My Website</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#services">Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#portfolio">Portfolio</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#team">Team</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Header Section -->
    <header id="home" class="header">
        <h1>Welcome to My Website</h1>
        <p class="lead">A place where amazing things happen.</p>
        <a class="btn btn-primary btn-lg" href="#services" role="button">Learn More</a>
    </header>

    <!-- Services Section -->
    <section id="services" class="py-5">
        <div class="container">
            <h2 class="section-title">Our Services</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x150" class="card-img-top" alt="Service 1">
                        <div class="card-body">
                            <h5 class="card-title">Service 1</h5>
                            <p class="card-text">Description of service 1.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x150" class="card-img-top" alt="Service 2">
                        <div class="card-body">
                            <h5 class="card-title">Service 2</h5>
                            <p class="card-text">Description of service 2.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x150" class="card-img-top" alt="Service 3">
                        <div class="card-body">
                            <h5 class="card-title">Service 3</h5>
                            <p class="card-text">Description of service 3.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title">Our Portfolio</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x150" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">Project 1</h5>
                            <p class="card-text">Description of project 1.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x150" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title">Project 2</h5>
                            <p class="card-text">Description of project 2.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x150" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title">Project 3</h5>
                            <p class="card-text">Description of project 3.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-5">
        <div class="container">
            <h2 class="section-title">About Us</h2>
            <div class="row">
                <div class="col-md-6">
                    <p>ABOUT 111111.</p>
                </div>
                <div class="col-md-6">
                    <p>ABOUT 222222.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title">Our Team</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x350" class="card-img-top" alt="Team Member 1">
                        <div class="card-body text-center">
                            <h5 class="card-title">Team Member 1</h5>
                            <p class="card-text">Role</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x350" class="card-img-top" alt="Team Member 2">
                        <div class="card-body text-center">
                            <h5 class="card-title">Team Member 2</h5>
                            <p class="card-text">Role</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/350x350" class="card-img-top" alt="Team Member 3">
                        <div class="card-body text-center">
                            <h5 class="card-title">Team Member 3</h5>
                            <p class="card-text">Role</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="section-title">Contact Us</h2>
            <div class="row">
                <div class="col-md-6">
                    <p>CONTACT 1: 9441623079</p>
                </div>
                <div class="col-md-6">
                    <p>CONTACT 2: 9491662040</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer text-center">
        <div class="container">
            <p>&copy; 2024 My Website. All Rights Reserved.</p>
            <a href="#home">Back to top</a>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


CSS :

/* styles.css */
body {
    background-color: #f8f9fa;
    font-family: 'Arial', sans-serif;
}

.navbar {
    background-color: #7190ae;
}

.navbar .navbar-brand,
.navbar .nav-link {
    color: white !important;
}

.header {
    background: url('https://via.placeholder.com/1920x600') no-repeat center center;
    background-size: cover;
    color: white;
    text-align: center;
    padding: 150px 0;
}

.header h1 {
    font-size: 4rem;
    font-weight: bold;
}

.section-title {
    text-align: center;
    margin-bottom: 40px;
}

.card {
    border: none;
    border-radius: 0;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.card img {
    border-radius: 0;
}

.footer {
    background-color: #6d849a;
    color: white;
    padding: 20px 0;
}

.footer a {
    color: #f8a0f2;
}
