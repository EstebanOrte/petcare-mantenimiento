# PetCare: plataforma de servicios para mascotas en Bogotá

PetCare es una aplicación web para que los propietarios de mascotas busquen y reserven servicios (veterinaria, peluquería, paseo y cuidado temporal) por tipo y localidad, y para que los proveedores publiquen sus servicios y acepten o rechacen las solicitudes.

Este repositorio se usa en el taller de control de versiones de la asignatura **Mantenimiento de Software** (Universidad Iberoamericana).

## Cómo ejecutarlo

1. Descargue o clone el repositorio.
2. Abra `index.html` con doble clic en Chrome, Edge o Firefox. No requiere servidor.
3. Ingrese con una cuenta de prueba (contraseña `123456`):
   - Propietaria: `laura@petcare.co`
   - Proveedores: `jorge@petcare.co` y `patitas@petcare.co`

Los datos se guardan en el navegador (localStorage). Para volver a los datos iniciales use "Restablecer datos de prueba" al pie de la página.

## Historias de usuario del taller

Las cinco historias de usuario que se implementan en este taller están en [`docs/historias-de-usuario.md`](docs/historias-de-usuario.md). Cada una se desarrolla en su propia rama (`feature/hu-XX-...`) y se integra a `main` con un *merge*.

## Autor

Esteban Ortega — Facultad de Ingeniería, Universidad Iberoamericana.
