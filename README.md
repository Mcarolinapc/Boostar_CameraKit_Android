# Boostar 

> 
> **"Pruébate el futuro"** 
>

[![Descargar PDF](https://img.shields.io/badge/Descargar-PDF-red?style=for-the-badge&logo=adobeacrobatreader)](Documentacion/Documentacion_Boostar.pdf)


---
**Boostar** es una aplicación móvil de comercio electrónico de ropa que integra tecnologías de **realidad aumentada (AR)** para transformar la experiencia de compra online. La aplicación permite a los usuarios visualizar cómo les quedaría una prenda antes de comprarla mediante un sistema virtual de "Try It On".

---

## 📋 Resumen del Proyecto

* **Problema que soluciona**: Reduce la gran cantidad de dinero perdido en devoluciones al permitir que el cliente vea cómo le queda la ropa antes de la compra.


* **Propósito**: Actuar como un e-commerce interactivo que mejora la confianza del usuario final.



Aquí tienes la sección del **Core Tecnológico** actualizada con los badges (escudos) correspondientes para que tu README luzca mucho más profesional y visual:

---

### 🛠️ Core Tecnológico

#### Mobile Development
* ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) 
* ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white) 
* ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

#### Realidad Aumentada (AR)
* ![Snapchat](https://img.shields.io/badge/Snapchat%20CameraKit-FFFC00?style=for-the-badge&logo=snapchat&logoColor=black)

#### Backend & Infrastructure
* ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) 
* ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) 
* ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white) 
##  Arquitectura de la App

El desarrollo sigue el patrón **MVVM (Modelo-Vista-ViewModel)**, separando el código en tres capas principales:

1. **Interfaz de Usuario**: Construida con **Jetpack Compose** bajo una mentalidad de *System Design* y componentes reutilizables.


2. **ViewModel**: Cada pantalla gestiona su propio estado y llamadas al repositorio.


3. **Repositorios**: Se utilizan interfaces para abstraer la fuente de datos, permitiendo intercambiar implementaciones entre Supabase y repositorios *mock* para pruebas.
![Arquitectura](Imagenes/arquitectura.png)



## 📊 Base de Datos y Backend

El sistema gestiona una base de datos relacional compleja que incluye:

* **Productos**: Tablas vinculadas a marcas, estilos, colores, tallas y elementos multimedia (imágenes/videos).


* **Usuarios**: Clasificados en dos roles principales: **Clientes** (con carrito e historial) y **Empresas** (con productos asociados).


* **Endpoints clave**: Gestión de onboarding, filtrado de productos (`get_products`), gestión de likes (`toggle_like`) y perfiles de partners.



##  Flujo de la Aplicación

![Grafo navegación](Imagenes/navegacion.png)


##  Estado del Proyecto y Mejoras

* **Bugs conocidos**: Problemas de persistencia en la paginación al volver de la pantalla AR y carga lenta de la Home en dispositivos de bajo rendimiento.


* **Mejoras pendientes**: Optimización del consumo de datos en videos y desarrollo completo de la funcionalidad del carrito.

---

## Video Demostrativo App

[![Ver demostración](https://img.youtube.com/vi/sAxPIa9pQGA/0.jpg)](https://youtu.be/sAxPIa9pQGA)
---

##  Autores

* **Marc Díaz Seuma** 


* **Michelle Carolina Posligua Contreras** 


* **Institución**: Institut Tecnològic Barcelona (ITB) 


* **Fecha**: 12/05/2026
![Marc y Mich](Imagenes/marcymich.jpeg)
