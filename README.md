# 📝 Blog en Ruby on Rails

Aplicación web tipo blog desarrollada con **Ruby on Rails 8**, siguiendo buenas prácticas de arquitectura MVC, autenticación, manejo de archivos enriquecidos y despliegue en producción.

🌐 **Demo en vivo:** [https://onrender.com](https://onrender.com)

---

## ✨ Características principales

* **Gestión completa de artículos (CRUD):** Creación, lectura, edición y eliminación con confirmación.
* **Estados de publicación:** Soporte para artículos en borrador (*Draft*), programados a futuro (*Scheduled*) y publicados (*Published*).
* **Autenticación y seguridad:** Inicio de sesión protegido con **Devise** y registro público deshabilitado para administración privada.
* **Editor de texto enriquecido:** Integración con **Action Text (Trix)** para dar formato al contenido.
* **Imágenes de portada:** Carga y vista previa con **Active Storage**, y eliminación instantánea sin recargar la página mediante **Turbo Streams**.
* **Paginación inteligente:** Navegación entre páginas con **Pagy** y manejo de errores de rango.
* **Diseño minimalista:** Interfaz limpia y responsiva estilizada con **Tailwind CSS**.

---

## 🛠️ Tecnologías utilizadas

* **Ruby:** 4.0.9
* **Framework:** Ruby on Rails 8.1
* **Base de datos:** PostgreSQL
* **Estilos:** Tailwind CSS
* **Autenticación:** Devise
* **Paginación:** Pagy
* **Despliegue:** Render

---

## 🚀 Instalación y ejecución local

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com
   cd learning-path-blog
   ```

2. **Instalar dependencias:**
   ```bash
   bundle install
   ```

3. **Configurar la base de datos y datos iniciales:**
   ```bash
   bin/rails db:create
   bin/rails db:migrate
   bin/rails db:seed
   ```

4. **Iniciar el servidor de desarrollo (Rails + Tailwind CSS):**
   ```bash
   bin/dev
   ```

5. Abrir `http://localhost:3000` en el navegador.
