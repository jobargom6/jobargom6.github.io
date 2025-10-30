---
layout: default
title: "Contacto"
---

<section class="container py-5">
  
  <h2 class="text-center mb-5 display-4 fw-bold" data-aos="fade-up">Contacto</h2>

  <div class="row gy-4 align-items-center">

    <div class="col-lg-6" data-aos="fade-right">
      <h3 class="mb-3">¡Hablemos!</h3>
      <p class="lead mb-4">
        Si te interesa mi perfil o te gustó mi trabajo, me encantaría conectar contigo. 
        Puedes contactarme directamente a mi correo electrónico o, si lo prefieres, 
        llena el siguiente formulario.
      </p>

      <ul class="list-unstyled fs-5">
        <li class="mb-3">
          <a href="mailto:jobargom06@gmail.com" class="text-decoration-none text-dark">
            <i class="fas fa-envelope fa-fw me-2 text-primary"></i>
            <strong>jobargom06@gmail.com.com</strong>
          </a>
        </li>
        <li class="mb-3">
          <a href="https://www.linkedin.com/in/joana-bg/" target="_blank" class="text-decoration-none text-dark">
            <i class="fab fa-linkedin fa-fw me-2 text-primary"></i>
            LinkedIn
          </a>
        </li>
        <li class="mb-3">
          <a href="https://github.com/jobargom6" target="_blank" class="text-decoration-none text-dark">
            <i class="fab fa-github fa-fw me-2 text-dark"></i>
            GitHub
          </a>
        </li>
      </ul>
    </div>

    <div class="col-lg-6" data-aos="fade-left" data-aos-delay="200">
      <div class="card shadow-sm border-0">
        <div class="card-body p-4 p-md-5">
          <form>
            <div class="mb-3">
              <label for="nombre" class="form-label">Nombre</label>
              <input type="text" id="nombre" class="form-control" required>
            </div>
            <div class="mb-3">
              <label for="correo" class="form-label">Correo electrónico</label>
              <input type="email" id="correo" class="form-control" required>
            </div>
            <div class="mb-3">
              <label for="mensaje" class="form-label">Mensaje</label>
              <textarea id="mensaje" rows="4" class="form-control" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary w-100">Enviar mensaje</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</section>