<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary p-3 " id="menu">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">BMD</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto me-auto mb-2 mb-lg-0 ">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="index2.html">Inicio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"> Moca Helado</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"> Expreso</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"> Capuchino</a>
          </li>
        </ul>

        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">

          <button class="icon-button"> <i class="fas fa-search"> </i></button>
        </form>
      </div>
    </div>
  </nav>
</template>

<style>
.icon-button{
    padding: 10px 20px;
    font-size: 16px;
    background-color: #cd966c;
    color: white;
    border: none;
    border-radius: 40px;
    cursor: pointer;
    display: flex;
    align-items: center;
}
.icon-button i {
margin-right: 10px;
}
body{
    font-family: 'Times New Roman', Times, serif;
    overflow-x: hidden;

}
#menu li > a{
    font-size: 15px;
    font-weight: bold;
    color:black;
}

</style>