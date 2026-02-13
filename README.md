<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jonatan | FullStack Junior</title>

<style>
:root {
  --primary: #2563eb;
  --secondary: #1e293b;
  --light: #f8fafc;
  --accent: #0ea5e9;
  --gray: #64748b;
}

body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: var(--light);
  color: var(--secondary);
  line-height: 1.6;
}

/* HEADER */
header {
  text-align: center;
  padding: 50px 20px;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
}

header p {
  margin-top: 10px;
}

header a {
  color: white;
  text-decoration: none;
  font-weight: 500;
  margin: 0 8px;
  transition: 0.3s ease;
}

header a:hover {
  color: #dbeafe;
  text-decoration: underline;
}

header a:active {
  color: #93c5fd;
}

/* SECCIONES */
section {
  max-width: 1100px;
  margin: 50px auto;
  padding: 0 20px;
}

h2 {
  border-left: 6px solid var(--primary);
  padding-left: 12px;
  margin-bottom: 25px;
}

/* TARJETAS */
.card {
  background: white;
  padding: 25px;
  margin-bottom: 25px;
  border-radius: 12px;
  box-shadow: 0 6px 15px rgba(0,0,0,0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 12px 25px rgba(0,0,0,0.15);
}

/* LISTAS */
ul {
  padding-left: 20px;
}

ul li {
  margin-bottom: 8px;
}

ul li:nth-child(even) {
  color: var(--gray);
}

ul li:last-child {
  margin-bottom: 0;
}

/* TECNOLOGÍAS */
.tech-container {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.tech {
  background: var(--primary);
  color: white;
  padding: 8px 15px;
  border-radius: 20px;
  font-size: 0.85rem;
  transition: 0.3s ease;
}

.tech:hover {
  background: var(--accent);
  transform: scale(1.05);
  cursor: pointer;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  background: var(--secondary);
  color: white;
  margin-top: 50px;
}
</style>
</head>

<body>

<header>
  <h1>👋 Hola, soy Jonatan</h1>
  <p><strong>FullStack Junior</strong> · Málaga</p>
  <p>
    <a href="mailto:jonatangamino@outlook.es">📧 Email</a> |
    <a href="#">💼 LinkedIn</a>
  </p>
</header>

<section>
  <h2>🧑‍💻 Sobre mí</h2>
  <div class="card">
    <p>
      Desarrollador Junior con experiencia en <strong>Java</strong> y especial interés en Bases de Datos.
      Cuento con <strong>9 meses de experiencia en el sector IT</strong> y más de
      <strong>5 años en atención al cliente</strong>, lo que me ha permitido desarrollar
      gran capacidad de trabajo en equipo y rendimiento bajo presión.
    </p>
    <p>
      Persona proactiva, con ganas de evolucionar profesionalmente y en continuo aprendizaje.
    </p>
  </div>
</section>

<section>
  <h2>🚀 Tecnologías</h2>
  <div class="tech-container">
    <div class="tech">Java</div>
    <div class="tech">PHP</div>
    <div class="tech">JavaScript</div>
    <div class="tech">Python</div>
    <div class="tech">C</div>
    <div class="tech">C#</div>
    <div class="tech">Kotlin</div>
    <div class="tech">HTML</div>
    <div class="tech">CSS</div>
    <div class="tech">SQL</div>
  </div>
</section>

<section>
  <h2>💼 Experiencia Profesional</h2>

  <div class="card">
    <h3>Reponedor - Carrefour (Junio 2024 - Actualidad)</h3>
    <ul>
      <li>Atención al cliente</li>
      <li>Perfilado y reposición de productos</li>
    </ul>
  </div>

  <div class="card">
    <h3>Desarrollador Junior - Advanced Quality Solutions (2023 - 2024)</h3>
    <ul>
      <li>Desarrollo de soluciones software en sector retail en Java</li>
      <li>Colaboración en resolución de incidencias</li>
      <li>Desarrollo de nuevas especificaciones para clientes</li>
      <li>Uso de Docker, SQL, Postman, Jenkins y JSON</li>
    </ul>
  </div>

  <div class="card">
    <h3>Vendedor - Okaidi / Kiabi (2017 - 2022)</h3>
    <ul>
      <li>Atención al cliente y cobro en caja</li>
      <li>Gestión de producto y uso de PDA</li>
      <li>Manejo de programas internos</li>
      <li>Funciones de mayor responsabilidad</li>
    </ul>
  </div>

</section>

<section>
  <h2>🎓 Formación</h2>
  <div class="card">
    <ul>
      <li><strong>Grado Superior DAW</strong> - IES Playamar (2025 - 2026)</li>
      <li><strong>Curso Back-End</strong> - Consultoría e Integración de Sistemas (2024)</li>
      <li><strong>Grado Superior DAM</strong> - IES Rosa Chacel (2021 - 2023)</li>
    </ul>
  </div>
</section>

<section>
  <h2>🌍 Idiomas</h2>
  <div class="card">
    <p><strong>Inglés:</strong> B1</p>
  </div>
</section>

<section>
  <h2>🧠 Aptitudes Técnicas</h2>
  <div class="card">
    <p><strong>IDEs:</strong> Eclipse, Android Studio, NetBeans, VS Code, Spyder, Notepad++</p>
    <p><strong>Bases de Datos:</strong> SQL Server, MySQL, Oracle</p>
    <p><strong>Lenguajes:</strong> Java, Kotlin, HTML, CSS, Python, C, C#, PHP, JavaScript</p>
  </div>
</section>

<section>
  <h2>ℹ️ Otros datos</h2>
  <div class="card">
    <ul>
      <li>🚗 Vehículo propio</li>
      <li>📅 Incorporación inmediata (preaviso)</li>
      <li>⏰ Disponibilidad completa</li>
    </ul>
  </div>
</section>

<footer>
  <p>📧 jonatangamino@outlook.es | 💼 LinkedIn</p>
  <p><em>Gracias por visitar mi perfil 🙌</em></p>
</footer>

</body>
</html>

<!--
<h1 align="center">👋 Hola, soy Jonatan</h1>

<p align="center">
  <strong>FullStack Junior</strong><br>
  Málaga · 
  <a href="mailto:jonatangamino@outlook.es">jonatangamino@outlook.es</a> · 
  <a href="[LINKEDIN]">LinkedIn</a>
</p>

---

## 🧑‍💻 Sobre mí

Desarrollador Junior de software con experiencia en **Java** y especial interés en **Bases de Datos**.  
Cuento con **9 meses de experiencia en el sector IT** y más de **5 años en atención al cliente**, lo que me ha permitido desarrollar una gran capacidad de trabajo en equipo y buen rendimiento bajo presión.

Me considero una persona proactiva, con ganas de evolucionar profesionalmente y en continuo aprendizaje.

---

## 🚀 Tecnologías

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
</p>

---

## 💼 Experiencia profesional

**Reponedor**  
Carrefour · Junio 2024 - Actualidad  
- Atención al cliente  
- Perfilado y reposición de productos  

**Desarrollador Junior de Software**  
Advanced Quality Solutions · 2023 - 2024  
- Desarrollo de soluciones software en el sector retail para cadenas comerciales en **Java**  
- Colaboración con equipos para la resolución de incidencias  
- Desarrollo de nuevas especificaciones para clientes  
- Uso de tecnologías y herramientas:
  - Docker
  - SQL
  - Postman
  - Jenkins
  - JSON  

**Vendedor**  
Okaidi / Kiabi · 2017 - 2022  
- Atención al cliente y cobro en caja  
- Perfilado y gestión de producto  
- Uso de PDA para tareas internas  
- Manejo de programas informáticos internos  
- Funciones de mayor responsabilidad dentro del equipo  

---

## 🎓 Formación

**Grado Superior en Desarrollo de Aplicaciones Web**  
IES Playamar · Málaga · 2025 - 2026  

**Curso de Desarrollo Web Back End**  
Consultoría e Integración de Sistemas · Madrid · 2024  

**Grado Superior en Desarrollo de Aplicaciones Multiplataforma**  
IES Rosa Chacel · Madrid · 2021 - 2023  

---

## 🌍 Idiomas

- **Inglés**: B1  

---

## 🧠 Aptitudes técnicas

- **IDEs y herramientas**
  - Eclipse (Maven)
  - Android Studio
  - NetBeans (Laravel)
  - Visual Studio Code (Laravel, Django, Python)
  - Spyder
  - Notepad++

- **Bases de datos**
  - SQL Server / SQL Server Management Studio
  - MySQL / phpMyAdmin / MySQL Workbench
  - Oracle / Oracle SQL Developer

- **Lenguajes**
  - Java, Kotlin
  - HTML / CSS
  - Python, C, C#
  - PHP, JavaScript

---
<!--
## 📂 Proyectos destacados

- **[Nombre del proyecto]**  
  Breve descripción del proyecto y tecnologías usadas.

- **[Nombre del proyecto]**  
  Breve descripción del proyecto y tecnologías usadas.

---

## 📫 Contacto

- 📧 Email: jonatangamino@outlook.es  
- 💼 LinkedIn: [link]  

---

## ℹ️ Otros datos

- 🚗 Vehículo propio  
- 📅 Incorporación inmediata (preaviso)  
- ⏰ Disponibilidad completa  

---

<p align="center">
  <em>Gracias por visitar mi perfil 🙌</em>
</p>
-->
