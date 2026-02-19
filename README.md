# Mi Diario Digital

Una aplicación web desarrollada desde cero con **JavaScript** y conectada a la nube mediante **Firebase**. Este proyecto simula un entorno de diario personal donde cada usuario puede registrarse, iniciar sesión y gestionar sus escritos de forma privada y segura.

## Funcionalidades Principales

* ** Autenticación de Usuarios:** Sistema de Login y Registro. Cada usuario tiene acceso exclusivo a sus propias notas.
* ** Almacenamiento en la Nube:** Integración con Firebase Firestore (NoSQL) para guardar las notas en tiempo real. Los datos persisten aunque cambies de dispositivo o navegador.
* ** Operaciones:** Capacidad para crear, leer, actualizar (editar) y borrar escritos.
* ** Buscador y Filtros:** Buscador dinámico por título y selectores para ordenar las notas (alfabético, más recientes, más antiguos) usando métodos de manipulación de Arrays en JS.
* ** Modo Lectura (Modal):** Ventana emergente diseñada con HTML/CSS/JS puros para leer las notas sin distracciones, con soporte para atajos de teclado (tecla `Esc` para salir) y cierre al hacer clic fuera del contenido.
* ** Diseño UI/UX:** Interfaz *responsive*, con un diseño limpio basado en un esquema de colores "Azul Acero" profesional y notificaciones de estado (botones dinámicos durante la carga).

##  Tecnologías Utilizadas

* **Frontend:** HTML, CSS y JavaScript.
* **Backend as a Service (BaaS):** Firebase.
  * *Firebase Authentication* (Email y Contraseña).
  * *Cloud Firestore* (Base de datos en tiempo real).

##  Lo que he aprendido con este proyecto

Este proyecto nació como un reto para dominar los fundamentos del desarrollo web sin depender de frameworks externos (como React o Angular). Me ha permitido profundizar en:
1. Manipulación avanzada del **DOM**.
2. Gestión del asincronismo en JavaScript.
3. Manejo de estado local vs. base de datos externa.
4. Creación de componentes UI (como las ventanas modales) utilizando únicamente CSS y JS nativo.

##  Cómo ejecutar el proyecto localmente

Al ser un proyecto Vanilla con Firebase vía CDN, no requiere Node.js ni procesos de compilación complejos.

1. Clona este repositorio: `git clone https://github.com/tu-usuario/mi-diario-digital.git`
2. Abre la carpeta del proyecto.
3. Abre el archivo `login.html` directamente en tu navegador.

---
*Desarrollado con mucha dedicación para seguir mejorando mis habilidades como desarrollador web.* 
