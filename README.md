<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-white">
        <div class="container">
            <svg xmlns="http://www.w3.org/2000/svg" width="35" height="30" fill="currentColor" class="bi bi-box-seam"
                viewBox="2 0 12 15">
                <path
                    d="M8.186 1.113a.5.5 0 0 0-.372 0L1.846 3.5l2.404.961L10.404 2zm3.564 1.426L5.596 5 8 5.961 14.154 3.5zm3.25 1.7-6.5 2.6v7.922l6.5-2.6V4.24zM7.5 14.762V6.838L1 4.239v7.923zM7.443.184a1.5 1.5 0 0 1 1.114 0l7.129 2.852A.5.5 0 0 1 16 3.5v8.662a1 1 0 0 1-.629.928l-7.185 2.874a.5.5 0 0 1-.372 0L.63 13.09a1 1 0 0 1-.63-.928V3.5a.5.5 0 0 1 .314-.464z" />
            </svg>
            <a class="navbar-brand" href="#">Move It</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button"
                            data-bs-toggle="dropdown">Services</a>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">Action</a></li>
                    <li><a class="dropdown-item" href="#">Another action</a></li>
                    <li><hr class="dropdown-divider"></li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="text" placeholder="Postcode">
                    <button class="btn btn-outline-secondary" type="button">Check</button>
                </form>
            </div>
        </div>
    </nav>

    <section class="py-5">
        <div class="container text-center">
            <h1 class="display-5 fw-bold mb-2">Move With Joy</h1>
            <p class="lead col-lg-6 mx-auto mb-4">
                Welcome to our website, where we are on a mission to provide
                exceptional moving services to customers in the US. As a startup, we
                believe that moving doesn't have to be stressful or complicated, and we
                are passionate about making the process as seamless and enjoyable as possible.
            </p>
            <div class="mb-5">
                <button class="btn btn-primary btn-lg me-2">Get a Quote</button>
                <button class="btn btn-outline-dark btn-lg">Contact Us</button>
            </div>
            <img src="https://lh3.googleusercontent.com/drive-storage/AJQWtBOXmp_6s-jdTtYpzYj9DHkB5vHtE6vT1xUMNSnundgNqyJNUGt6O1uzfqWxyAS5w4yuKzQmF5DEaeASfWje7-DFMR7r-ItRxRp4wWkU2eEYQTQszQ=w1897-h877?auditContext=forDisplay"
                alt="Moving services team" class="img-fluid rounded shadow-sm" style="max-width: 700px;">
        </div>
    </section>

    <section class="py-5 bg-light">
        <div class="container">
            <h2 class="h1 mb-5 pb-2 border-bottom">Why Move With Us?</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="h1 text-primary mb-3">
                        <i class="bi bi-briefcase-fill"></i>
                    </div>
                    <h3 class="h4 fw-bold mb-3">Professional</h3>
                    <p class="text-muted mb-3">
                        Our team of professional movers are trained to prioritize efficiency, organization, and
                        attention to detail. We understand that your possessions are more than just objects - they are a
                        reflection of your life, memories, and experiences. That's why we take extra care to ensure that
                        everything is packed and transported with the utmost care and attention.
                    </p>
                    <a href="#" class="text-primary text-decoration-none">Get a quote <i
                            class="bi bi-arrow-right"></i></a>
                </div>

                <div class="col-md-4">
                    <div class="h1 text-primary mb-3">
                        <i class="bi bi-bus-front-fill"></i>
                    </div>
                    <h3 class="h4 fw-bold mb-3">Countrywide</h3>
                    <p class="text-muted mb-3">
                        We offer <a href=""></a> range of services to suit your individual needs, whether you're moving
                        locally or across the country. Our team can handle everything from packing and loading to
                        unloading and unpacking, so you can focus on settling into your new home. And with our
                        transparent pricing and no hidden fees, you can trust that you're getting a fair and competitive
                        rate for our services.
                    </p>
                    <a href="#" class="text-primary text-decoration-none">Get a quote <i
                            class="bi bi-arrow-right"></i></a>
                </div>

                <div class="col-md-4">
                    <div class="h1 text-primary mb-3">
                        <i class="bi bi-chat-square-text-fill"></i>
                    </div>
                    <h3 class="h4 fw-bold mb-3">Personal Touch</h3>
                    <p class="text-muted mb-3">
                        At our core, we believe that moving should be an exciting and positive experience, not a
                        stressful one. By providing exceptional moving services in the US, we hope to revolutionize the
                        way people think about moving and provide a better, more personalized experience for our
                        customers. Contact us today to learn more about how we can help you with your next move.
                    </p>
                    <a href="#" class="text-primary text-decoration-none">Get a quote <i
                            class="bi bi-arrow-right"></i></a>
                </div>
            </div>
        </div>
    </section>
    <div id="carouselExample" class="carousel slide" style="margin: 68px;">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="c:\Users\Maam Jhoza\Downloads\couple.jpg" class="d-block w-100" alt="happy couple">
            </div>
            <div class="carousel-item">
                <img src="c:\Users\Maam Jhoza\Downloads\dog.jpg" class="d-block w-100" alt="dog">
            </div>
            <div class="carousel-item">
                <img src="c:\Users\Maam Jhoza\Downloads\family.jpg" class="d-block w-100" alt="family">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <footer class="py-5">
        <div class="container">
            <div class="row">

                <div class="col-md-4 d-flex align-items-center">
                    <p class="mb-0">&copy; 2023</p>
                </div>

                <div class="col-md-2">
                    <h6 class="fw-bold mb-3">Section</h6>
                    <ul class="list-unstyled mb-0">
                        <li><a href="#" class="text-decoration-none text-dark">Home</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">Features</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">Pricing</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">FAQs</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">About</a></li>
                    </ul>
                </div>

                <div class="col-md-2">
                    <h6 class="fw-bold mb-3">Section</h6>
                    <ul class="list-unstyled mb-0">
                        <li><a href="#" class="text-decoration-none text-dark">Home</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">Features</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">Pricing</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">FAQs</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">About</a></li>
                    </ul>
                </div>

                <div class="col-md-2">
                    <h6 class="fw-bold mb-3">Section</h6>
                    <ul class="list-unstyled mb-0">
                        <li><a href="#" class="text-decoration-none text-dark">Home</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">Features</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">Pricing</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">FAQs</a></li>
                        <li><a href="#" class="text-decoration-none text-dark">About</a></li>
                    </ul>
                </div>
                <div class="col-md-2"></div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
        crossorigin="anonymous"></script>
</body>
</html>
