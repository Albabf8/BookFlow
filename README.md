# 📖 BookFlow

> **BookFlow** es una plataforma web moderna diseñada para transformar la gestión de bibliotecas personales, corrigiendo las carencias estéticas y de usabilidad de las herramientas actuales.

---

## 📝 Resumen del Proyecto

**BookFlow** es una plataforma web creada para simplificar la forma en que los lectores organizan su biblioteca personal. La aplicación permite realizar un seguimiento exhaustivo de las lecturas, clasificar libros y descubrir nuevas obras a través de una interfaz moderna que prioriza la estética y la facilidad de uso, mejorando la experiencia de plataformas tradicionales.

## 👥 Público Objetivo

La plataforma está diseñada para **lectores activos** que buscan una herramienta visual para gestionar su "caos" literario. Es la solución ideal para quienes quieren llevar su lista de pendientes y terminados siempre encima, gracias a una interfaz optimizada para su uso en smartphones y tablets.

## 💡 Justificación y Valor Añadido

El proyecto nace de la necesidad de modernizar aplicaciones como Goodreads, cuya interfaz resulta compleja y anticuada para el estándar actual. **BookFlow** aporta valor mediante:
* **Diseño Adaptativo (Responsive):** Una interfaz fluida que se comporta como una App nativa en móviles (requisito DAM) y como una web robusta en escritorio (DAW).
* **Minimalismo Visual:** Enfoque en las portadas y la limpieza de datos para evitar la fatiga visual.
* **Interacción Directa:** Sistema ágil para puntuar y reseñar libros sin pasos innecesarios.

---

## 🔐 Roles

| Funcionalidad | Administrador | Lector Registrado | Invitado |
| :--- | :---: | :---: | :---: |
| Explorar catálogo público | ✓ | ✓ | ✓ |
| Registro de cuenta nueva | | ✓ | ✓ |
| Gestión de biblioteca personal (CRUD) | | ✓ | |
| Escribir y editar reseñas propias | | ✓ | |
| Alta y modificación de libros (Catálogo global) | ✓ | | |
| Moderación de usuarios y comentarios | ✓ | | |

---

## 🛠️ Tecnologías

* **Lenguajes:** JavaScript, SQL y CSS3.
* **Tecnologías Frontend:** React y Tailwind CSS para el estilo.
* **Tecnologías Backend:** Supabase (gestión de base de datos relacional y autenticación de usuarios).
* **Otras herramientas:** * **IDE:** Visual Studio Code.
    * **Control de versiones:** Git y GitHub.
    * **Despliegue:** Vercel.
 
---

## 🗄️ Modelo de Datos

La base de datos en **PostgreSQL** está organizada para gestionar la biblioteca y la comunidad de forma eficiente:

* **perfiles**: Datos extendidos de los usuarios (nombre, avatar) vinculados a la autenticación.
* **libros**: Catálogo general con la información de las obras (título, autor, sinopsis y portadas).
* **resenas**: Opiniones y valoraciones (1-5 estrellas) que los lectores vinculan a cada libro.
* **bibliotecas**: Gestión del estado de lectura personal (Pendiente, Leyendo, Terminado).

> **Seguridad**: Se utilizarán políticas RLS para que cada lector solo gestione sus propios datos privados.

---

# 👨🏼‍🏫 Tutorías

Resumen de las tutorías

* 12-septiembre
     * Presentación de Asignatura y Proyecto.
  
* 19-septiembre
     * Creación de Imagen Corporativa de la Empresa.
  
* 26-septiembre
     * Elaboración de Contrato de Prestación de Servicios con la Empresa, y Recogida de Necesidades del Proyecto.
  
* 3-octubre
     * Definición de Requisitos Funcionales y No Funcionales del Aplicativo, y Presentación a la Empresa.
  
* 10-octubre
     * Desarrollo de las Interfaces Gráficas.
  
* 17-octubre
     * Desarrollo de la Estructura de la Base de Datos.
  
* 24-octubre
     * Definición de Modelo Relacional de la Base de Datos.
  
* 31-octubre
     * Presentación a la Empresa de las Interfaces y la Base de Datos.
  
* 7-noviembre
     * Elección de Tecnologías a Utilizar.
  
* 14-noviembre
     * Estructuración Inicial de Documentación.
  
* 21-noviembre
     * Definición de Puntos de los Manuales de Usuario y Técnico.
  
* 05-diciembre
     * Desarrollo Inicial de Manuales de Usuario y Técnico.
  
* 12-diciembre
     * Opciones de Despliegue de Aplicativos.
  
* 19-diciembre
     * Pruebas de Despliegue en Entorno Local: TomCat.
  
* 09-enero
     * Pruebas de Despliegue en Vercel.

* 16-enero
     * Fase de ajustes finales, corrección de errores (Bugs) y optimización de rendimiento.
 
* 23-enero
     * Cierre definitivo de la documentación y manuales finales.
 
* 30-enero
     * Empaquetado final del software y preparación de la defensa del proyecto.
  
---

**Autor:** Alba Barroso Fernández  
**Centro:** IES Albarregas, Mérida (Badajoz)  
**Tutor de Proyecto:** Francisco José Mera Calderón
