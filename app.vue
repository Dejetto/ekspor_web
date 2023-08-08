<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary warnaNav">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <NuxtLink class="nav-link active btn btn-success warnaTulisanNav" aria-current="page" to="/">Home</NuxtLink>
          </li>
          <li class="nav-item dropdown btn btn-success">
            <NuxtLink class="nav-link dropdown-toggle warnaTulisanNav" to="buah sayur" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Our Product
            </NuxtLink>
            <ul class="dropdown-menu">
              <li><NuxtLink class="dropdown-item" to="buah">Buah</NuxtLink></li>
              <li><NuxtLink class="dropdown-item" to="sayur">Another action</NuxtLink></li>
            </ul>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/about">About Us</NuxtLink>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <NuxtPage />
  
  </div>
</template>
