<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Navbar</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="/">HOME<span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/Projects">PROJECTS</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/Services">SERVICES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/Contact">CONTACT</a>
        </li>
      </ul>
    </div>
  </nav>
  <router-view />
</template>

