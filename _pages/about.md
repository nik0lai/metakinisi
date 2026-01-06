---
layout: about
title: signa gel
permalink: /
subtitle: Parker Laboratories

profile:
  align: right
  image: gel.png
  image_circular: false # crops the image to make it circular
  more_info: >
    Tubo de 250 gramos

selected_papers: false # disabled: hide selected publications section
social: false # disabled: hide social icons at the bottom of the page

announcements:
  enabled: false # disabled: hide news section
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Gel de electrolitos multiuso ideal para electrodos. Recomendado para EEG, ECG, biofeedback y EMG.

**Valor:** 12.999 (con IVA)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


---

## Solicitar cotización

<form action="https://formspree.io/f/xwvpdgyg" method="POST" class="contact-form">
  <input type="hidden" name="_next" value="{{ site.baseurl }}/gracias/">
  <input type="hidden" name="_subject" value="Nueva solicitud de cotización - Signa gel">
  
  <div class="form-group">
    <label for="nombre">Nombre <span class="required">*</span></label>
    <input type="text" id="nombre" name="nombre" class="form-control" required>
  </div>
  
  <div class="form-group">
    <label for="email">Correo electrónico <span class="required">*</span></label>
    <input type="email" id="email" name="email" class="form-control" required>
  </div>
  
  <div class="form-group">
    <label for="cantidad">Cantidad <span class="required">*</span></label>
    <input type="number" id="cantidad" name="cantidad" class="form-control" min="1" required>
  </div>
  
  <div class="form-group">
    <label for="direccion">Dirección de envío <span class="required">*</span></label>
    <textarea id="direccion" name="direccion" class="form-control" rows="3" required></textarea>
  </div>
  
  <div class="form-group">
    <label for="comentarios">Comentarios</label>
    <textarea id="comentarios" name="comentarios" class="form-control" rows="4"></textarea>
  </div>
  
  <button type="submit" class="btn btn-primary">Enviar solicitud</button>
</form>

<style>
.contact-form {
  max-width: 600px;
  margin: 2rem 0;
}

.form-group {
  margin-bottom: 1.5rem;
}

.form-group label {
  display: block;
  margin-bottom: 0.5rem;
  font-weight: 500;
}

.required {
  color: #dc3545;
}

.form-control {
  width: 100%;
  padding: 0.5rem;
  border: 1px solid #ced4da;
  border-radius: 0.25rem;
  font-size: 1rem;
}

.form-control:focus {
  outline: none;
  border-color: #80bdff;
  box-shadow: 0 0 0 0.2rem rgba(0,123,255,.25);
}

.btn-primary {
  background-color: #007bff;
  color: white;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 0.25rem;
  cursor: pointer;
  font-size: 1rem;
}

.btn-primary:hover {
  background-color: #0056b3;
}
</style>
