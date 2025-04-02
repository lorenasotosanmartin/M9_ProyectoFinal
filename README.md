# Proyecto final: Desarrollo de sistema clínica Chillán
## Descripción
A lo largo del curso, se desarrolló una plataforma de gestión y reserva de servicios médicos, diseñada para facilitar la administración de citas. Con una interfaz intuitiva y responsiva, garantiza un acceso rápido y seguro desde cualquier dispositivo. 

Mediante un desarrollo incremental, se abordaron e implementaron funcionalidades asociadas a diversas temáticas durante las nueve unidades contempladas por el curso, las cuales implicaron desde la creación de la estructura básica en lenguaje HTML, incorporación de la libreria React, seguridad, PWA, hasta elementos de integración y despliegue continuo con herramientas como Dockers.

Es importante destacar que mediante el desarrollo de este proyecto, se recibio feeedback que permitio realizar mejoras referente a estructura del proyecto, aplicación de estilos y aspectos de seguridad.

### Principales funcionalidades
- **Listado de servicios**: En la página principal del sitio web, se puede ver el listado de los principales servicios médicos disponibles en la clínica, esta información se muestra de forma dinámica mediante el consumo de un api. 
- **Listado de doctores**: En la página “servicios” del sitio web, se puede ver el listado e información de los profesionales médicos, destacando información asociada a su especialidad, años de experiencia y descripción de los servicios brindados, esta información se muestra de forma dinámica mediante el consumo de un api. 
- **Formulario de contacto**: En la pagina “contacto” del sitio web, se encuentra un formulario para que los usuarios del sitio se puedan contactar con personal de la clínica.
- **Agenda de cita**: Al seleccionar el botón “reservar en cita” en el navbar o pagina de servicios del sitio web, se puede acceder a un formulario que permite realizar una reserva con algunos de los profesionales disponibles. 
- **Dashboard Administrador**: Esta sección, está disponible solo para el usuario con el rol “administrador” y presenta un listado resumen con todas las citas médicas agendadas en la clinica y la opción de confirmar la asistencia del paciente o cancelarla. Cabe destacar, que para ingresar a esta sección se deben validar los datos de usuario en un Login inicial y cuenta con rutas protegidas para bloquear el acceso a cualquier otro tipo de usuario.
  - **datos de acceso**: user: adminsitrador, clave: admin123! 
- **Dashboard Doctor**: Esta sección, está disponible solo para los usuarios con el rol “doctor” y presenta un listado resumen con todas las citas médicas asociadas al doctor que inicio sesión. Cabe destacar, que para ingresar a esta sección se deben validar los datos de usuario en un Login inicial y cuenta con rutas protegidas para bloquear el acceso a cualquier otro tipo de usuario.
  - **datos de acceso**: user: felipeZapata, clave: felipeZapata123! 

### Tecnologías utilizadas
- **React**: Biblioteca JavaScript para construir interfaces de usuario
- **Vite**: Herramienta de desarrollo rápida para React
- **Booststrap**: Framework que permite el uso de  componentes y estilos CSS y JavaScript predefinidos. 
  
### Visualización del proyecto
Para visualizar este proyecto se necesita que previamente cuentes con la instalación de:
- **Git**: [sitio de descarga] (https://git-scm.com/downloads)
- **Node.js**: [sitio de descarga] (https://nodejs.org/en/download/package-manager)
- **Visual Studio Code**: [sitio de descarga] (https://code.visualstudio.com/download)
  
Una vez que ya cuentes con lo descrito anteriormente, debes clonar este repositorio en una carpeta local, mediante el siguiente comando:
```bash
git clone https://github.com/lorenasotosanmartin/M9_ProyectoFinal.git
```
cuando ya este clonado, escribir el siguiente comando en la consola: 
```bash
npm  i
```
y ejecutar el comando, para inicializar el proyecto: 
```bash
npm run dev
```
Finalmente, para visualizar el proyecto en tu navegador debes abrir la url: http://localhost:5173/

### Alojamiento del proyecto
De igual forma, el proyecto se encuentra alojado en la web, mediante el uso de la herramenta Vercel, para visitarlo, puedes ingresar a la siguiente URL: https://clinica-chillan.vercel.app/

### Autores
- **Lorena Soto San Martin** 
  [GitHub](https://github.com/brayandiazc)
  [Portafolio](https://portafolio-lorena-soto.vercel.app/)
