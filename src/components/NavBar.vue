<template>
  <header id="header" class="page-header fixed">
      <div class="navbar navbar-expand-lg">
        <a href="#" class="navbar-brand text-white"
          ><img src="../assets/img/logos/nhuzik-logo-inverted.png" alt="">
          <span class="hidden-folded d-inline l-s-n-1x">Nhuzik</span></a
        >
        <div
          class="collapse navbar-collapse order-2 order-lg-1"
          id="navbarCollapse"
        >
          <ul class="navbar-nav" data-nav>
            <li class="nav-item">
              <a href="#" class="nav-link"
                ><span class="nav-text">Artistas</span></a
              >
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link no-ajax"
                ><span class="nav-text">Músicas</span></a
              >
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link no-ajax"
                ><span class="nav-text">MMA</span></a
              >
            </li>
          </ul>
        </div>
        <ul class="nav navbar-menu order-1 order-lg-2">
          <li class="nav-item">
            <a class="nav-link no-ajax" href="#">Logar</a>
          </li>
          <li class="d-flex align-items-center">
            <a
              class="btn btn-rounded btn-sm btn-primary no-ajax"
              href="#"
              >Registar</a
            >
          </li>
          <li class="nav-item d-lg-none">
            <a
              href="#"
              class="nav-link px-2"
              data-toggle="collapse"
              data-toggle-class
              data-target="#navbarCollapse"
              ><i data-feather="menu"></i
            ></a>
          </li>
        </ul>
      </div>
    </header>
</template>

<script>
export default {

}
</script>

<style>

</style>