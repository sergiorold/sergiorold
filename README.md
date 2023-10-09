<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>carriti</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
</head>
<body>
    <nav class="navbar bg-dark navbar-expand-lg bg-body-tertiary" data-bs-theme="dark">
                <div class="container-fluid">
                <a class="navbar-brand" href="#">Tienda Sara</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Acerca de</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        catalogos
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Muebles</a></li>
                        <li><a class="dropdown-item" href="#">Electronica</a></li>
                        <li><a class="dropdown-item" href="#">Ropa</a></li>
                        <li><a class="dropdown-item" href="#">Accesorios</a></li>
                        <li><hr class="dropdown-divider"></li>
                        <li><a class="dropdown-item" href="#">llantas</a></li>
                        </ul>
                    </li>
                    </ul>
                    <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Buscar</button>
                    </form>
                </div>
                </div>
            </nav>
            <div class="container" style="margin-top: 30px;">
                <div class="row">
                   <div class="col-2"></div>
                   <div class="col-8">
                    <div class="card text-center">
                        <div class="card-header">
                          Carrito de Compra 
                        </div>
                        <div class="card-body">
                            <table class="table">
                                <thead>
                                  <tr>
                                    <th scope="col">#</th>
                                    <th scope="col">Nombre</th>
                                    <th scope="col">Precio</th>
                                    <th scope="col">Cantidad</th>
                                    <th scope="col">Total</th>
                                  </tr>
                                </thead>
                                <tbody>
                                  <tr>
                                    <th scope="row">1</th>
                                    <td><img src="https://th.bing.com/th/id/OIP.wrE2qCIPd7uLAp1dfkJ1FQHaJ4?w=157&h=209&c=7&r=0&o=5&dpr=1.3&pid=1.7" class="card-img-top" alt="Pantalon para tienda" height="300">Pantal Para Tienda</td>
                                    <td>$600.00</td>
                                    <td><input type="text" class="form-control" value="3"></td>
                                    <td>$1800.00</td>
                                  </tr>
                                </tbody>
                              </table>
                            
                                  </div>
                          <h5 class="card-title">Subtotal: $1512.00  </h5>
                          <p class="card-text">Iva: $288.00</p>
                          <h3 class="card-title">Total: 1800</h3>
                          <a href="#" class="btn btn-primary">Pagar</a>
                        </div>
                        <div class="card-footer text-body-secondary">
                          envio gratis
                        </div>
                      </div>
                   </div>
                   <div class="col-2"></div>
            </div>
            <div class="container" style="margin-top: 30px;">
                <div class="row">
                    <div class="col">
                        <div class="card" style="width: 18rem;">
                            <img src="https://th.bing.com/th/id/OPHS.uqniwrpEMhnsVA474C474?w=174&h=226&o=5&dpr=1.3&pid=1.7" class="card-img-top" alt="Pantalon Dama" height="300">
                            <div class="card-body">
                              <h5 class="card-title">Pantalones Cortos </h5>
                              <p class="card-text">Pantalones cortos Yoga .</p>
                              <a href="#" class="btn btn-primary">$450.00</a>
                            </div>
                          </div>
                    </div>
                    <div class="col">
                        <div class="card" style="width: 18rem;">
                            <img src="https://th.bing.com/th/id/OIP.wrE2qCIPd7uLAp1dfkJ1FQHaJ4?w=157&h=209&c=7&r=0&o=5&dpr=1.3&pid=1.7" class="card-img-top" alt="Pantalon para tienda" height="300">
                            <div class="card-body">
                              <h5 class="card-title">Pantalon para tienda</h5>
                              <p class="card-text">Pantalon dama asul moda.</p>
                              <a href="#" class="btn btn-primary">$600.00</a>
                            </div>
                          </div>
                    </div>
                    <div class="col">
                        <div class="card" style="width: 18rem;">
                            <img src="https://th.bing.com/th/id/OIP.Khsw50scEkQqz1ihaFl7tQHaJL?w=161&h=200&c=7&r=0&o=5&dpr=1.3&pid=1.7" class="card-img-top" alt="Pantalon Casual Dama" height="300">
                            <div class="card-body">
                              <h5 class="card-title">Pantalon De Caballero </h5>
                              <p class="card-text">Pantalones de vestir de caballero.</p>
                              <a href="#" class="btn btn-primary">$290.00</a>
                            </div>
                          </div>
                    </div>
                    <div class="col">
                        <div class="card" style="width: 18rem;">
                            <img src="https://th.bing.com/th/id/OIP.HyeFrL_G-ztgaPquDgIQ7AHaJa?w=182&h=231&c=7&r=0&o=5&dpr=1.3&pid=1.7" class="card-img-top" alt="Pantalon Deportivo" height="300">
                            <div class="card-body">
                              <h5 class="card-title">Pantalon Deportivo</h5>
                              <p class="card-text">Pantalon Deportivo.</p>
                              <a href="#" class="btn btn-primary">$600.00</a>
                            </div>
                          </div>
                    </div>
                </div>
            </div>
    <script src="js/bootstrap.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    
</body>
</html>Y
