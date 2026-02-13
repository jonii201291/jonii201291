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
}

body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: var(--light);
  color: var(--secondary);
}

/* HEADER */
header {
  text-align: center;
  padding: 40px 20px;
  background: linear-gradient(135deg, var(--primary), var(--accent));
  color: white;
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
}

header p a {
  color: white;
  text-decoration: none;
  font-weight: 500;
  margin: 0 5px;
}

/* Pseudoclases */
header p a:hover {
  text-decoration: underline;
  color: #dbeafe;
}

header p a:active {
  color: #93c5fd;
}

section {
  max-width: 1000px;
  margin: 40px auto;
  padding: 0 20px;
}

h2 {
  border-left: 5px solid var(--primary);
  padding-left: 10px;
  margin-bottom: 20px;
}

/* TARJETAS */
.card {
  background: white;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 18px rgba(0,0,0,0.15);
}

/* LISTAS */
ul {
  list-style: none;
  padding: 0;
}

ul li {
  padding: 8px 0;
  border-bottom: 1px solid #e2e8f0;
}

ul li:nth-child(even) {
  background-color: #f1f5f9;
}

ul li:last-child {
  border-bottom: none;
}

/* TECNOLOGÍAS */
.tech-container {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}

.tech {
  background: var(--primary);
  color: white;
  padding: 8px 15px;
  border-radius: 20px;
  font-size: 0.9rem;
  transition: background 0.3s ease;
}

.tech:hover {
  background: var(--accent);
  cursor: pointer;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 20px;
  background: var(--secondary);
  color: white;
  margin-top: 40px;
}
</style>
</head>

<body>

<header>
  <h1>👋 Hola, soy Jonatan</h1>
  <p>
    <strong>FullStack Junior</strong> · Málaga ·
    <a href="mailto:jonatangamino@outlook.es">Email</a> ·
    <a href="#">LinkedIn</a>
  </p>
</header>

<section>
  <h2>🧑‍💻 Sobre mí</h2>
  <div class="card">
    <p>
      Desarrollador Junior con experiencia en <strong>Java</strong> y especial interés en Bases de Datos.
      9 meses en el sector IT y más de 5 años en atención al cliente.
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
    <div class="tech">Kotlin</div>
  </div>
</section>

<section>
  <h2>💼 Experiencia</h2>

  <div class="card">
    <h3>Desarrollador Junior - Advanced Quality Solutions</h3>
    <ul>
      <li>Desarrollo en Java</li>
      <li>Uso de Docker, SQL, Jenkins</li>
      <li>Resolución de incidencias</li>
    </ul>
  </div>

  <div class="card">
    <h3>Reponedor - Carrefour</h3>
    <ul>
      <li>Atención al cliente</li>
      <li>Gestión de productos</li>
    </ul>
  </div>

</section>

<footer>
  <p>📫 jonatangamino@outlook.es | Disponibilidad inmediata</p>
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
