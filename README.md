# Guía de Configuración de Moodle

Esta guía describe los pasos para configurar un entorno Moodle, gestionar usuarios y cursos, personalizar la apariencia y aplicar medidas de seguridad.

## 1. Configuración Inicial
### a) Modificación de Perfil
1. Inicia sesión como administrador.
2. Ve a tu perfil (parte superior derecha) > **Editar perfil**.
3. Cambia el correo electrónico y la contraseña.
4. Sube un avatar.

![Modificar perfil](images/Captura%20de%20pantalla%20de%202025-03-19%2013-02-48.png)

### b) Configuración del Sitio
1. Ve a **Administración del sitio > Primera plana > Parámetros**.
2. Cambia el nombre del sitio (largo y corto).
3. Configura la visibilidad para usuarios no autenticados.

![Configuración del sitio](images/Captura%20de%20pantalla%20de%202025-03-19%2013-26-43.png)

### c) Configuración de Zona Horaria
1. Accede a **Administración del sitio > Ubicación > Parámetros**.
2. Selecciona la zona horaria correcta.

![Zona horaria](images/Captura%20de%20pantalla%20de%202025-03-12%2012-41-44.png)

### d) Configuración de Idioma
1. Ve a **Administración del sitio > Idioma > Parámetros**.
2. Ajusta el idioma predeterminado y activa la detección automática.
3. Para nuevos idiomas, instala paquetes en **Idioma > Paquetes de idioma**.

![Configuración de idioma](images/Captura%20de%20pantalla%20de%202025-03-12%2012-41-55.png)

### e) Política de Contraseñas
1. Ve a **Administración del sitio > Seguridad > Normativas del sitio**.
2. Ajusta la política para exigir mínimo 4 caracteres, incluyendo mayúsculas, minúsculas y números.

![Política de contraseñas](images/Captura%20de%20pantalla%20de%202025-03-12%2012-42-20.png)

## 2. Creación de Cursos
1. Accede a **Administración del sitio > Gestiona cursos y categorías**.
2. Crea:
   - Curso **A** con 3 temas.
   - Curso **B** con 5 temas.

![Creación de cursos](images/Captura%20de%20pantalla%20de%202025-03-12%2012-42-25.png)

## 3. Gestión de Contenidos
1. Accede a uno de los cursos creados.
2. Activa la edición.
3. Agrega un archivo PDF.
4. Modifica títulos y experimenta con opciones de edición.

![Gestión de contenidos](images/Captura%20de%20pantalla%20de%202025-03-12%2012-50-31.png)

## 4. Creación y Gestión de Usuarios
### a) Crear Usuario Manualmente
1. Ve a **Administración del sitio > Usarios > Cuentas > Agregar un usuario**.
2. Crea el usuario **Bob** con autenticación manual.

![Crear usuario Bob](images/bob.png)

### b) Creación Masiva de Alumnos
1. Accede a **Administración del sitio > Usarios > Cuentas > Cargar usuarios**.
2. Sube un archivo CSV con 10 alumnos.

![Carga masiva de usuarios](images/usuarios%20A.png)

### c) Eliminación de Usuarios
1. Accede a **Administración del sitio > Usarios > Acciones con usuarios en bloque**.
2. Elimina dos de los alumnos creados.

![Eliminar usuarios](images/usuarios%20B.png)

## 5. Matriculación de Usuarios
### a) Configurar Métodos de Inscripción
1. En el curso **A**, permite solo acceso de visitante.
2. En el curso **B**, habilita la inscripción manual.

![Métodos de inscripción](images/Captura%20de%20pantalla%20de%202025-03-12%2012-51-31.png)

### b) Asignar Usuarios
1. Asigna a **Bob** como profesor del curso **B**.
2. Matricula a los alumnos creados en el curso **B**.

![Asignar usuarios](images/bob2.png)

### c) Verificación de Accesibilidad
1. Confirma que el curso **A** es público.
2. Confirma que el curso **B** requiere autenticación.

![Verificación de accesibilidad](images/Captura%20de%20pantalla%20de%202025-03-12%2012-57-14.png)

## 6. Personalización del Moodle
1. Descarga e instala un tema desde **Administración del sitio > Connectors > Instalar complemento**.
2. Cambia la cabecera y el pie de página en **Administración del sitio > Apariencia > Temas > Selector de temas**.

![Personalización](images/Captura%20de%20pantalla%20de%202025-03-19%2012-23-16.png)

## 7. Seguridad
1. Bloquea una IP en **Administración del sitio > Seguridad**.
2. Aplica una política de seguridad y justifica su implementación.

![Seguridad](images/4c.png)

---

Las capturas de pantalla correspondientes a cada paso se encuentran en la carpeta `/images/` del repositorio.
