<template>
    <nav class="navbar navbar-expand-lg border">
      <div class="container d-flex">
        <a class="navbar-brand" href="#"> 
          <img src="../assets/logo2.png" alt="" width="150" height="120" />
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">Features</a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">Upload</a></li>
                  <li><a class="dropdown-item" href="#">Download</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Setting</a></li>
                </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">News</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </template>