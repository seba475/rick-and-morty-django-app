# 🧪 Buscador de personajes – Rick & Morty

Aplicación web desarrollada con **Django** que permite explorar personajes de
la serie **Rick & Morty** usando su API pública. Realizado como trabajo
práctico para la materia **Introducción a la Programación** (UNGS).

---

## 📝 Descripción

La aplicación consume datos de la Rick & Morty API y muestra los personajes en
una galería de tarjetas. Cada tarjeta incluye información del personaje y cambia
su borde de color según su estado (vivo, muerto o desconocido).

---

## 📸 Capturas

### Galería de personajes
<p align="center">
  <img src="img/galeria.png" width="700">
</p>

### Buscador en funcionamiento
<p align="center">
  <img src="img/buscador.png" width="700">
</p>

### Personajes favoritos
<p align="center">
  <img src="img/favoritos.png" width="700">
</p>

---

## 🚀 Funcionalidades

- Galería de personajes obtenidos desde la API, con imagen, nombre, estado,
  última ubicación y primer episodio.
- Borde de color según el estado del personaje: verde (vivo), rojo (muerto),
  naranja (desconocido).
- Buscador de personajes por nombre.
- Inicio de sesión básico.
- Sistema de favoritos para usuarios autenticados.

---

## 🛠️ Tecnologías

- Python
- Django

---

## 🧱 Sobre el proyecto

Desarrollado sobre una base provista por la cátedra, que incluía la
arquitectura en capas (transport, services, persistence, utilities), los
templates y la capa de consumo de la API.

Mi trabajo consistió en implementar la lógica de la galería en `views.py` y
`services.py`, el coloreado de las tarjetas según el estado del personaje, y
los tres módulos opcionales del enunciado: buscador, inicio de sesión y sistema
de favoritos.

---

## ▶️ Ejecución

1. Instalar Python
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el servidor: `python manage.py runserver 3000`
4. Abrir en el navegador: `http://localhost:3000`

### Usuario de prueba
- **usuario:** admin
- **contraseña:** admin
