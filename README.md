<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="./Source/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css">

</head>
<style>
    div.card {
        align-items: center;
    }

    body {
        background-color: #bd9642;
    }
</style>

<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-info">
        <div class="container-fluid">
            <span class="bi bi-house-door-fill"></i> </span>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link " href="aboutus.html">About Us</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            Tools
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="Full Stack.html">Full Stack</a></li>
                            <li><a class="dropdown-item" href="WebDesign.html">WebDesign</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Help</a></li>
                            <li><a class="dropdown-item" href="#">Write for Us</a></li>
                        </ul>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
                </form>
            </div>
            <div class="mx-2">
                <button type="button" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#loginModal">
                    Login
                </button>
                <button type="button" class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#signupModal">
                    SignUp
                </button>
            </div>
        </div>
    </nav>


    <!-- LoginModal -->
    <div class="modal fade" id="loginModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="loginModalLabel">Login to iCoder</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="mb-3">
                            <label for="exampleInputEmail1" class="form-label">Username</label>
                            <input type="email" class="form-control" id="exampleInputEmail1"
                                aria-describedby="emailHelp">
                            <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                        </div>
                        <div class="mb-3">
                            <label for="exampleInputPassword1" class="form-label">Password</label>
                            <input type="password" class="form-control" id="exampleInputPassword1">
                        </div>
                        <div class="mb-3 form-check">
                            <input type="checkbox" class="form-check-input" id="exampleCheck1">
                            <label class="form-check-label" for="exampleCheck1">Check me out</label>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>


    <!-- SignUp Modal -->

    <div class="modal fade" id="signupModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="loginModalLabel">Login to iCoder</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="mb-3">
                            <label for="exampleInputEmail1" class="form-label">Username</label>
                            <input type="email" class="form-control" id="exampleInputEmail1"
                                aria-describedby="emailHelp">
                            <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
                        </div>
                        <div class="mb-3">
                            <label for="exampleInputPassword1" class="form-label">Password</label>
                            <input type="password" class="form-control" id="exampleInputPassword1">
                        </div>
                        <div class="mb-3">
                            <label for="cexampleInputPassword1" class="form-label">Confirm Password</label>
                            <input type="password" class="form-control" id="cexampleInputPassword1">
                        </div>
                        <button type="submit" class="btn btn-primary">Create Account</button>
                    </form>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>


    <h1 class="text-bold fm-bold text-center bg-success text-warning">Style for the I-Coder</h1>
    <div class="container row mx-auto"></div>


    <div id="carouselExampleCaptions" class="carousel slide carousel-fade" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="images/code2.jpg" class="d-block w-100" alt="Full Stack">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Full Stack Devloper</h5>
                    <p>Full Stack Development is an immersive program, meticulously curated to provide you with the
                        tools and technologies to build, deploy, test, run, and manage full-stack applications.</p>
                    <button class="btn-danger">Technology</button>
                    <button class="btn-warning">Web Devlopment</button>
                    <button class="btn-success">Tech Fun</button>
                </div>
            </div>
            <div class="carousel-item">
                <img src="images/code6.jpg" class="d-block w-100" alt="Web Designer">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Web Designer</h5>
                    <p>We create beautifully customized websites that meet your business needs, whether they are
                        e-commerce or informational, and allow for easy navigation.</p>
                    <button class="btn-danger">Technology</button>
                    <button class="btn-warning">Web Devlopment</button>
                    <button class="btn-success">Tech Fun</button>
                </div>
            </div>
            <div class="carousel-item">
                <img src="images/code7.jpg" class="d-block w-100" alt="Graphic Designer">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Graphic Designer</h5>
                    <p>A graphic designer is a professional within the graphic design and graphic arts industry who
                        assembles together images, typography, or motion graphics to create a piece of design. A graphic
                        designer creates the graphics primarily for published, printed, or electronic media, such as
                        brochures (sometimes) and advertising.</p>
                    <button class="btn-danger">Technology</button>
                    <button class="btn-warning">Web Devlopment</button>
                    <button class="btn-success">Tech Fun</button>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <div class="alert alert-primary" role="alert">
        This is I-Coder Site
    </div>

    <div class="container">
        <div class="row">
            <div class="col-12 col-sm-6 col-md-4 mx-auto my-3">
                <div class="card">
                    <img src="images/code2.jpg" class="card-img-top" alt="code4">
                    <div class="card-body">
                        <h5 class="card-title">Java Devloper</h5>
                        <p class="card-text">A Java developer is a specialized programmer who collaborates with software
                            engineers and web developers to integrate Java into business software, applications, and
                            websites </p>
                        <a href="#" class="btn btn-primary">About More Information</a>
                    </div>

                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-4 mx-auto my-3">
                <div class="card">
                    <img src="images/code6.jpg" class="card-img-top" alt="code6">
                    <div class="card-body">
                        <h5 class="card-title">FontendDevloper</h5>
                        <p class="card-text">This Full Stack Java Developer Job Guarantee Program is a comprehensive
                            six-month program, in partnership with HIRIST and HackerEarth.</p>
                        <a href="#" class="btn btn-primary">About More Information</a>
                    </div>

                </div>
            </div>
            <div class="col-12 col-sm-6 col-md-4 mx-auto my-3">
                <div class="card">
                    <img src="images/code7.jpg" class="card-img-top" alt="code7">
                    <div class="card-body">
                        <h5 class="card-title">Web Designer</h5>
                        <p class="card-text">Web Design Technologies: custom WordPress website, php, MySQL database,
                            css3 design, modern, easy-to-use website with subtle animations and a full product database.
                        </p>
                        <a href="#" class="btn btn-primary">About More Information</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <br>

    <div class="container-fluid mt-1 my-3">
        <div class="row">
            <div class="col-sm-3 p-3 border bg-warning">FrontEnd Devloper</div>
            <div class="col-sm-3 p-3 border bg-info">Graphic Designer</div>
            <div class="col-sm-3 p-3 border bg-danger">Software Engineer</div>
            <div class="col-sm-3 p-3 border bg-success">Full Stack</div>
        </div>
    </div>
    <br>

    <footer>
        <div class="container-fluid bg-info">
            <div class="row">
                <div class="col-12 col-sm-6 col-md-4 mx-auto">
                    <div class="container-fluid p-3">
                        <h5> <i class="bi bi-person-lines-fill"></i> Contact Us: 7058900319 </h5>
                        <h5> <i class="bi bi-chat-left-dots-fill"></i> Massage US</h5>
                        <h5><i class="bi bi-whatsapp"></i> WhatsApp Me</h5>
                    </div>
                </div>
                <div class="col-12 col-sm-6 col-md-4 mx-auto">
                    <div class="container-fluid p-3">
                        <h5><i class="bi bi-github"></i> GitHub: ShuebaliMomin</h5>
                        <h5><i class="bi bi-envelope-fill"></i> Email Us: shuaibalimomin123@gmail.com </h5>
                    </div>
                </div>
            </div>
        </div>

    </footer>

    <script src="Source/jquery.min.js"></script>
    <script src="Source/bootstrap.min.js"></script>

</body>

</html>
