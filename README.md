# nuevo-Imports System.Runtime.InteropServices
Imports System.Windows

<!DOCTYPE html>
<html lang = "es" >
<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0"

    <meta name="description" content="Portafolio de Carlos Pérez, desarrollador frontend especializado en React, HTML5, CSS3 y JavaScript."/>
    <meta name="keywords" content="Carlos Pérez, frontend, React, HTML5, CSS3, JavaScript, portafolio"/>
    <meta name="author" content="Carlos Pérez"/>
    <title>Carlos Pérez | Frontend Developer</title>

    <!-- Bootstrap 5.3.3 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"/>
    <!-- Font Awesome 6.5.1 -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" rel="stylesheet"/>
    <!-- Custom CSS -->
    <link rel="stylesheet" href="style.css"/>
</head>
<body>

  <!-- Navbar -->
  <nav Class="navbar navbar-expand-lg fixed-top bg-light" aria-label="Menú principal">
    <div Class="container">
      <a Class="navbar-brand fw-bold" href="#">Carlos Pérez 🚀</a>
      <button Class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span Class="navbar-toggler-icon"></span>
      </button>
      <div Class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul Class="navbar-nav">
          <li Class="nav-item"><a class="nav-link" href="#inicio">Inicio</a></li>
          <li Class="nav-item"><a class="nav-link" href="#sobre-mi">Sobre Mí</a></li>
          <li Class="nav-item"><a class="nav-link" href="#proyectos">Proyectos</a></li>
          <li Class="nav-item"><a class="nav-link" href="#experiencia">Experiencia</a></li>
          <li Class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
        </ul>
        <button id = "toggleDark" Class="btn btn-outline-light ms-3"><i Class="fas fa-moon"></i></button>
      </div>
    </div>
  </nav>

  <!-- Homepage -->
  <header id = "inicio" Class="vh-100 d-flex flex-column justify-content-center align-items-center text-center text-white">
    <img src = "https://cdn3.iconfinder.com/data/icons/data-science-set-01-2/65/20-512.png" alt="Carlos Pérez" Class="rounded-circle mb-4" width="200" height="200" />
    <h1 Class="animate__fadeInUp">Carlos Pérez</h1>
    <p Class="lead">Desarrollador Frontend especializado en React, HTML5, CSS3 y JavaScript 🚀</p>
  </header>

  <!-- Sobre Mí -->
  <section id = "sobre-mi" Class="py-5">
    <div Class="container text-center">
      <h2> <i Class="fas fa-user text-primary"></i> Sobre Mí</h2>
      <p Class="lead">Soy Carlos Pérez 📸, apasionado por crear interfaces modernas y accesibles. Me encanta transformar ideas en experiencias digitales intuitivas.</p>
      <div Class="row mt-4">
        <div Class="col-md-4">
          <i Class="fas fa-laptop-code fa-2x text-primary"></i>
          <h5 Class="mt-2">Tecnologías</h5>
          <p> React, HTML5, CSS3, JavaScript</p>
        </div>
        <div Class="col-md-4">
          <i Class="fas fa-users fa-2x text-primary"></i>
          <h5 Class="mt-2">Colaboración</h5>
          <p> Trabajo en equipo, metodologías ágiles</p>
        </div>
        <div Class="col-md-4">
          <i Class="fas fa-bullseye fa-2x text-primary"></i>
          <h5 Class="mt-2">Objetivo</h5>
          <p> Crear experiencias digitales memorables</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Proyectos -->
  <section id = "proyectos" Class="py-5 bg-light">
    <div Class="container">
      <h2 Class="text-center"><i class="fas fa-project-diagram text-primary"></i> Proyectos</h2>
      <div Class="row mt-4">
        <div Class="col-md-4">
          <div Class="card project-card h-100">
            <img src = "https://www.tucanit.com/wp-content/uploads/2021/10/almadraba.jpg" alt="E-commerce" Class="card-img-top" />
            <div Class="card-body">
              <h5 Class="card-title">Tienda Virtual</h5>
              <p Class="card-text">E-commerce con React, Bootstrap y API de pagos.</p>
              <a href = "#" Class="btn btn-primary">Ver Proyecto</a>
            </div>
          </div>
        </div>
        <div Class="col-md-4">
          <div Class="card project-card h-100">
            <img src = "https://www.tucanit.com/wp-content/uploads/2021/10/oficina.jpg" alt="Dashboard" Class="card-img-top" />
            <div Class="card-body">
              <h5 Class="card-title">Panel Administrativo</h5>
              <p Class="card-text">Dashboard con gráficos dinámicos y control de usuarios.</p>
              <a href = "#" Class="btn btn-primary">Ver Proyecto</a>
            </div>
          </div>
        </div>
        <div Class="col-md-4">
          <div Class="card project-card h-100">
            <img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMIjzhc7m8zFXXhW09E_ZnBNVNRCAwdKZHAQ&s" alt="App Móvil" Class="card-img-top" />
            <div Class="card-body">
              <h5 Class="card-title">App Móvil</h5>
              <p Class="card-text">Aplicación híbrida con interfaz responsiva y notificaciones push.</p>
              <a href = "#" Class="btn btn-primary">Ver Proyecto</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Experiencia -->
  <section id = "experiencia" Class="py-5">
    <div Class="container">
      <h2> <i Class="fas fa-briefcase text-primary"></i> Experiencia</h2>
      <div Class="row mt-4">
        <div Class="col-md-4">
          <div Class="card experience-card h-100 border-primary">
            <div Class="card-body text-center">
              <i Class="fas fa-building fa-3x text-primary"></i>
              <h5 Class="mt-3">Senior Frontend - TechCorp</h5>
              <p>2021–2025 | Desarrollo de interfaces SaaS con React y Bootstrap.</p>
            </div>
          </div>
        </div>
        <div Class="col-md-4">
          <div Class="card experience-card h-100 border-primary">
            <div Class="card-body text-center">
              <i Class="fas fa-building fa-3x text-primary"></i>
              <h5 Class="mt-3">UI Designer - PixelForge</h5>
              <p>2019–2021 | Diseño de componentes visuales y prototipos interactivos.</p>
            </div>
          </div>
        </div>
        <div Class="col-md-4">
          <div Class="card experience-card h-100 border-primary">
            <div Class="card-body text-center">
              <i Class="fas fa-building fa-3x text-primary"></i>
              <h5 Class="mt-3">Freelance Developer</h5>
              <p>2018–2019 | Sitios web personalizados para clientes locales.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id = "contacto" Class="py-5 bg-light">
    <div Class="container">
      <h2> <i Class="fas fa-envelope text-primary"></i> Contacto</h2>
      <form Class="mt-4">
        <div Class="mb-3">
          <label for="nombre" class="form-label">Nombre</label>
          <Input type = "text" Class="form-control" id="nombre" required />
        </div>
        <div Class="mb-3">
          <label for="correo" class="form-label">Correo electrónico</label>
          <Input type = "email" Class="form-control" id="correo" required />
