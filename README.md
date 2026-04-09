# Practical 12
<html>
<head>
    <title>Fashion Mart</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<!-- 🔹 Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Fashion Mart</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="nav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Men</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Women</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Kids</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Cart</a></li>
      </ul>
      </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>

    </div>
  </div>
</nav>

<!-- 🔹 Carousel -->
<div id="slider" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">

    <div class="carousel-item active">
      <img src="https://liandli.in/cdn/shop/files/liewg83-4_800x.jpg?v=1686312320" class="d-block w-100">
    </div>

    <div class="carousel-item">
      <img src="https://5.imimg.com/data5/SELLER/Default/2020/12/ML/VG/LK/29174263/haldi-special-party-wear-dresses-500x500.jpeg" class="d-block w-100">    </div>

    <div class="carousel-item">
      <img src="https://www.richaglobal.com/images/mens-pic2a.jpg" class="d-block w-100">
    </div>
    </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>


  </div>
</div>

<!-- 🔹 Products Section -->
<div class="container mt-5">
  <h2 class="text-center mb-4">Trending Products</h2>

  <div class="row">

    <!-- Card 1 -->
    <div class="col-md-4">
      <div class="card">
        <img src="https://surhi.in/cdn/shop/collections/Mens_Wear.webp?v=1721029303" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Men Shirt</h5>
          <p class="card-text">₹999</p>
          <a href="#" class="btn btn-primary">Buy Now</a>
        </div>
      </div>
    </div>

    <!-- Card 2 -->
    <div class="col-md-4">
      <div class="card">
        <img src="https://tiimg.tistatic.com/fp/1/003/092/women-western-dresses-033.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Women Dress</h5>
          <p class="card-text">₹1499</p>
          <a href="#" class="btn btn-success">Add to Cart</a>
        </div>
      </div>
    </div>

    <!-- Card 3 -->
    <div class="col-md-4">
      <div class="card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGReVVBdlQ4PVMzV-bTX0QQJMjMVQzD6RveA&s" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Jeans</h5>
          <p class="card-text">₹1299</p>
          <a href="#" class="btn btn-danger">Buy Now</a>
        </div>
      </div>
    </div>

  </div>

  <!-- Second Row -->
  <div class="row mt-4">

    <div class="col-md-4">
      <div class="card">
        <img src="https://assets.ajio.com/medias/sys_master/root/20250506/kn92/681a251d55340d4b4f1d2383/ausk_grey___women_oversized_fit_cotton_graphic_t-shirt.jpg" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">T-Shirt</h5>
          <p class="card-text">₹599</p>
          <a href="#" class="btn btn-primary">Buy Now</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card">
        <img src="https://www.globalrepublic.in/cdn/shop/files/1_ab54633e-b0b8-4a9b-96c0-30aaf3d6949f.jpg?v=1761421769&width=1080" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Jacket</h5>
          <p class="card-text">₹1999</p>
          <a href="#" class="btn btn-success">Add to Cart</a>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card">
        <img src="https://www.campusshoes.com/cdn/shop/products/RAISE_WHT_f1a5a2ec-8a23-4795-a796-0da7455dc57a.jpg?v=1757593683" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">Shoes</h5>
          <p class="card-text">₹2499</p>
          <a href="#" class="btn btn-danger">Buy Now</a>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- 🔹 Footer -->
<footer class="bg-dark text-white text-center mt-5 p-3">
  <p>© 2026 Fashion Mart | All Rights Reserved</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
