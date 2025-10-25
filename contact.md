---
layout: default
title: "Contacto"
---

<section class="container py-5">
  <h2 class="text-center mb-5">Contacto</h2>

  <div class="row justify-content-center">
    <div class="col-md-8">
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
        <button type="submit" class="btn btn-primary">Enviar mensaje</button>
      </form>
    </div>
  </div>
</section>
