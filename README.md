¡Nuevo! Combinaciones de teclas … Las combinaciones de teclas de Drive se han actualizado para que puedas navegar escribiendo las primeras letras
# **Tarea de investigación**

---

**Eduardo Enrique López Rodríguez**
Carnet: LR21008
Asignatura: Diseño de Sistema II  
Docente: Ing. Karen Elvira Peñate Avilés
---

Fecha: Sábado, 28 de septiembre de 2024

---

**Universidad de El Salvador**  
Facultad de Ingeniería y Arquitectura  
El Salvador, San Salvador

![Logo](https://seeklogo.com/images/U/universidad-de-el-salvador-logo-BE187B09C3-seeklogo.com.png)

---
## Introducción

Una buena aplicación no lo es en sí misma por su funcionamiento, sino por la garantía de que se ha sometido a pruebas que se acomplan a los requerimientos planteados. Dichas pruebas deben satisfacerse para poder decir que está lista para ser liberada al público o usuario final.

De igual forma, la documentación durante el desarrollo es vital. Si se basa en un modelo de desarrollo como SCRUM, se requiere documentar una serie de elementos, sobretodo en las etapas iniciales que se está diseñando y analizando como será dispuesta nuestra aplicación o software.

El presente trabajo tiene por objetivo mostrar el funcionamiento y hacer uso de herramientas que nos permiten probar nuestro software y documentarlo.Dentro del mercado hay una amplia gama de opciones, cada una ofrece características que puedan acoplarse mejor según las necesidades.

Se muestran en el primer apartado, 4 herramientas que nos permiten probar nuestro software en diferente tipos de pruebas y escenarios. En la sección 2, se presentan 2 herramientas para la documentación. En ambas partes se muestran sus características, pros y contras, asimismo, se detalla un cuadro comparativo de los puntos más relevantes para finalmente, hacer una valoración y seleccionar una de ellas para cada sección y elaborar la tarea asignada.

---

# 1. Herramientas automatizadas de pruebas de software

## 1.1 PHPUnit

### Breve descripción  
PHPUnit es un framework para PHP que facilita la creación de clases de pruebas sobre aplicaciones basadas en PHP. PHP es un lenguaje que posibilita la creación de páginas web complejas, lo que provoca la necesidad de controlar el correcto funcionamiento de las mismas.

### Características
- Integración con otros frameworks de prueba.
- Soporte para Mock Objects mediante jMock.
-  almacenar los resultados en una Test Database.
- Compatible con el grupo de frameworks de xUnit y puerto completo de JUnit para PHP5.  

### Tipos de pruebas
- Pruebas unitarias: Verificación de componentes individuales o unidades de código.
- Pruebas de integración: Evaluación de cómo interactúan diferentes módulos o componentes.
- Pruebas funcionales: Validación de la funcionalidad general de la aplicación (con herramientas adicionales).

### Ventajas y desventajas
**Ventajas**  
- Sencillo de programar y fácil de utilizar.
- Muy recomendado por los desarrolladores debido a su similitud con otros frameworks de testeo.
- Forma parte del grupo de frameworks de xUnit.
- Puerto completo de JUnit para PHP5.
- Soporte para Mock Objects (jMock).
- Almacena los resultados en una Test Database.
- Se integra con varias aplicaciones de test.

**Desventajas**  
- Limitado a pruebas unitarias e integración, no soporta pruebas de sistema o de carga sin herramientas adicionales.
- Sin interfaz gráfica para la ejecución de pruebas, lo que puede ser menos accesible para algunos usuarios.
- Limitado a PHP

---

## 1.2 Selenium

### Breve descripción  
Selenium es un entorno de pruebas que se utiliza para comprobar si el software que se está desarrollando funciona correctamente. Esta herramienta permite: grabar, editar y depurar casos de pruebas que se pueden automatizar. Lo más atractivo de Selenium es que se pueden editar acciones o crearlas desde cero. Esta herramienta también ayuda mucho en las pruebas de regresión porque consigue pruebas automatizadas que luego se pueden reutilizar cuando se necesite. Comenzó a desarrollarse en 2004 por Jason Huggins y poco a poco se fueron uniendo varios especialistas. Este software es de código abierto (bajo licencia apache 2.0) y puede ser descargado y usado de forma gratuita.

### Características
- Las acciones se pueden ejecutar punto a punto.
- Contiene la opción de autocompletar a la hora de escribir código.
- Se puede referenciar a objetos DOM: nombre, ID o con XPath.
- Ejecuta test complejos que ahorra tiempo de trabajo.
- Abarca puntos de verificación y una gran depuración.
- Permite el almacenamiento en varios formatos de los test realizados.

### Tipos de pruebas
- Pruebas de Interfaz de Usuario (UI): Verificación del comportamiento de la interfaz de usuario.
- Pruebas End-to-End: Verificación de flujos completos de una aplicación web.

### Ventajas y desventajas
**Ventajas**  
- Gran compatibilidad
- Versatilidad con lenguajes de programación
- Flexibilidad e integración
- Automatización de pruebas de regresión
- Capacidad para pruebas paralelas
- Soporte para pruebas en múltiples plataformas
- Amplia comunidad y recursos 

**Desventajas**  
- Fragilidad de los scripts
- Falta de soporte para aplicaciones móviles
- Dependencia de los navegadores web
- Rendimiento y velocidad
- Curva de aprendizaje
- Dificultad para pruebas de aplicaciones complejas
- Limitaciones de las pruebas visuales
- Mantenimiento y escalabilidad 

---

## 1.3 Cypress

### Breve descripción  
Es una herramienta de prueba front-end de próxima generación diseñada para aplicaciones web modernas. Permite automatizar pruebas end-to-end, de componente, integración y unitarias, aunque se utiliza principalmente para pruebas end-to-end. Cypress es adecuada para cualquier prueba que se ejecute en un navegador web, incluyendo configuración, scripting, ejecución y depuración.

### Características
- Soporta pruebas end-to-end, de componentes, integración y unitarias
- Capacidad para interactuar con la interfaz a nivel de navegador
- Registro de acciones durante la ejecución de pruebas (time travel)
- Generación de reportes detallados
- Documentación extensa y actualizada
- Herramientas integradas para la automatización de pruebas
- Compatible con APIs para integración con otros sistemas
- Capacidad de manejar pruebas asíncronas
- Compatible con múltiples navegadores, incluyendo Chrome, Firefox, Edge
- Versión experimental para simulación de Safari en iOS

### Tipos de pruebas
- Pruebas end-to-end (E2E)
- Pruebas de componentes
- Pruebas de integración
- Pruebas unitarias

### Ventajas y desventajas
**Ventajas**  
- Fácil instalación y rápida curva de aprendizaje
- Permite escribir pruebas "más rápidas, fáciles y confiables"
- No requiere la adición de drivers para funcionar
- Proporciona una experiencia fluida en la automatización sin necesidad de manejar múltiples herramientas por separado

**Desventajas**  
- No permite automatización de aplicaciones móviles
- Limitación en la interacción con múltiples pestañas

---

## 1.4 Tosca

### Breve descripción  
Tosca Testsuite es la aplicación principal de Tricentis para automatización integral. Ofrece un enfoque basado en modelos que facilita la creación y mantenimiento de scripts de prueba, permitiendo la colaboración entre equipos y la ejecución de pruebas en todas las capas de la arquitectura de aplicaciones.

### Características
- Automatización integral de pruebas funcionales, de carga y rendimiento
- Enfoque basado en modelos para crear y mantener scripts de prueba
- Colaboración entre equipos
- Ejecución de pruebas en todas las capas de la arquitectura de aplicaciones

### Tipos de pruebas
- Pruebas funcionales
- Pruebas de carga
- Pruebas de rendimiento

### Ventajas y desventajas
**Ventajas**  
- Automatización extensiva en diversas capas de la aplicación
- Facilita la colaboración entre equipos
- Reduce el esfuerzo en el mantenimiento de scripts de prueba
- Enfoque basado en modelos que simplifica la creación de pruebas

**Desventajas**  
- Puede ser complejo de aprender y configurar
- Costoso en comparación con otras herramientas
- Requiere una inversión significativa en tiempo y recursos para implementación y mantenimiento

---

## 1.5 Cuadro comparativo de las herramientas


| **Criterio** | **PHPUnit**   | **Selenium** | **Cypress**| **Tosca**|
|-|-|-|-|-|
| **Facilidad de Uso**| Fácil de usar, curva de aprendizaje baja                  | Curva de aprendizaje moderada, requiere conocimiento de scripting| Muy fácil de usar, curva de aprendizaje rápida |Curva de aprendizaje alta debido a su enfoque basado en modelos|
| **Tipos de Prueba Soportados**  | Pruebas unitarias, de integración                                             | Pruebas UI, end-to-end, regresión                                         | Pruebas end-to-end, unitarias, de integración, de componentes                  | Pruebas funcionales, de carga, rendimiento                                              |
| **Integración Continua (CI/CD)**| Sí, soporta integración con CI/CD como Jenkins, GitHub Actions               | Sí, se integra fácilmente con CI/CD                                       | Sí, soporta CI/CD                                                             | Sí, soporta integración con CI/CD                                                        |
| **Automatización**              | Automatiza pruebas unitarias y de integración; no automatiza pruebas de carga o sistema | Automatiza pruebas de regresión y UI, pero los scripts pueden ser frágiles | Excelente automatización de pruebas end-to-end y unitarias, pero limitada en interacción con múltiples pestañas | Automatización avanzada en todas las capas, pero complejo de configurar               |
| **Documentación**               | Documentación extensa y soporte comunitario activo                           | Amplia documentación y una comunidad grande                               | Documentación actualizada y comunidad activa                                  | Documentación sólida, pero menos comunidad que otras herramientas                      |
| **Multiplataforma**             | Windows, macOS, Linux                                                         | Windows, macOS, Linux                                                     | Windows, macOS, Linux                                                          | Windows (principalmente)                                                                  |
| **Multilenguaje**               | Exclusivo para PHP                                                             | Multilenguaje: Java, C#, Python, JavaScript, etc.                         | JavaScript (exclusivo)                                                          | Multilenguaje, pero menos flexible en comparación con Selenium o Cypress                |

---

# 2. Herramientas para documentación de software

## 2.1 LaTeX

### Breve descripción  

LaTeX es una herramienta para componer documentos de aspecto profesional. Es un sistema que emplea comandos para presentar contenidos complejos, sobre todo relacionados con las matemáticas como fracciones, subíndices, superíndices, matrices, derivadas parciales e integrales. 

A diferencia de los programas de tratamiento de textos como Word o Libre Office, LaTeX funciona de forma muy diferente: el documento es un archivo de texto sin formato intercalado con comandos LaTeX que se utilizan para expresar los resultados deseados.

### Características
- Sistema basado en comandos para formateo y presentación de documentos.
- Soporte avanzado para la composición de matemáticas complejas.
- Capacidad para crear índices, glosarios, y bibliografías.
- Gran personalización y extensión mediante paquetes complementarios. 

### Ventajas y desventajas
**Ventajas**  
- Soporte para la composición tipográfica de matemáticas extremadamente complejas, tablas y contenido técnico
- Facilidades para notas a pie de página, referencias cruzadas y gestión de bibliografías
- Facilidad para producir elementos documentales complicados o tediosos, como índices, glosarios, índices de contenido o listas de figuras
- Gran capacidad de personalización para crear documentos a medida, gracias a su programabilidad y a las múltiples opciones gracias a miles de paquetes complementarios gratuitos

**Desventajas**  
- Escribir en LaTeX es como programar un ordenador: hay que seguir reglas estrictas sobre cómo se representan las ecuaciones. Si el usuario infringe una de estas reglas al escribir una ecuación LaTeX, el proceso de convertir el código en ecuaciones legibles no funcionará.
- El editor señalará los puntos de error e indicará cuáles son, lo que permite al usuario depurar el documento LaTeX. Sin embargo, puede ser desafiante para principiantes debido a la complejidad del sistema.

---

## 2.2 Dillinger

### Breve descripción  

Dillinger es un editor Markdown en línea de código abierto que ofrece un entorno de escritura sin distracciones. Permite escribir en formato Markdown en una sección y previsualizar el documento ya formateado en tiempo real en la sección opuesta. Además, ofrece la posibilidad de visualizar el código fuente HTML correspondiente. Dillinger soporta exportación a formatos HTML, PDF y Markdown y facilita la integración con servicios en la nube como Dropbox, GitHub, Medium, Google Drive y OneDrive.

### Características
- Entorno de escritura en formato Markdown con previsualización en tiempo real.
- Visualización del código fuente HTML generado.
- Exportación a formatos HTML, PDF y Markdown.
- Integración con servicios en la nube como Dropbox, GitHub, Medium, Google Drive y OneDrive.
- Importación de documentos desde Dropbox, GitHub, Medium, Google Drive y OneDrive.
- Contador de caracteres y palabras.
- Almacenamiento automático mediante cookies

### Ventajas y desventajas
**Ventajas**  
- Interfaz limpia y sin distracciones.
- Vista previa en tiempo real.
- Integración con varios servicios en la nube.
- Sin necesidad de registro previo.
- Código abierto.

**Desventajas**  
- Funciones de colaboración limitadas.
- Problemas de rendimiento ocasionales.
- Falta de soporte para características avanzadas de Markdown, sin soporte para plugins o extensiones.
- Exportación a PDF limitada en personalización.
- Dependencia de conexión a Internet.
- Almacenamiento automático basado en cookies puede ser poco fiable.

---

## 2.3 Cuadro comparativo de las herramientas

| **Criterio**              | LaTeX                                                     | Dillinger                                          |
|-------------------------|------------------------------------------------------------|----------------------------------------------------|
| **Facilidad de uso**  | Curva de aprendizaje pronunciada; requiere conocimiento de comandos. | Fácil de usar; curva de aprendizaje baja.          |
| **Online**              | No es una herramienta en línea por sí misma; se puede usar en editores en línea como Overleaf. | Sí, es una herramienta en línea accesible desde el navegador. |
| **Gratuito o paga**     | Gratuito; editores en línea pueden ser gratuitos o de pago. | Gratuito; algunas funcionalidades avanzadas pueden requerir suscripciones o servicios adicionales. |
| **Código abierto**      | Sí, LaTeX es de código abierto.                           | Sí, Dillinger es de código abierto.                |
| **Funcionalidades**     | Excelente para documentos técnicos y científicos; manejo avanzado de bibliografías y contenido matemático; requiere paquetes adicionales para ciertas funcionalidades. | Permite edición y visualización en tiempo real; exportación a varios formatos; integración con servicios en la nube; soporte básico de marcado. |
| **Colaborativo**        | La colaboración puede ser complicada sin herramientas adicionales; editores en línea como Overleaf facilitan la colaboración en tiempo real. | Funciones de colaboración limitadas; integración con servicios como Dropbox y GitHub facilita la gestión de archivos. |

---

## 3. Selección de herramientas basada en el cuadro comparativo

1. Razones para Seleccionar PHPUnit

Se seleccionó PHPUnit debido a su compatibilidad directa con Laravel, el framework que se utiliza en el proyecto. PHPUnit permite ejecutar pruebas unitarias de manera eficiente, lo que es ideal para garantizar que las funciones del sistema se comporten como se espera desde el desarrollo inicial. Además, su integración nativa con MySQL facilita la validación de bases de datos en este contexto.

2. Razones para Seleccionar Dillinger

Para la documentación del proyecto, se eligió Dillinger por su facilidad de uso y su enfoque en la escritura de Markdown, lo que permite generar documentación técnica limpia y exportarla a distintos formatos como PDF o HTML. A diferencia de LaTeX, Dillinger es más intuitivo y rápido para un flujo de trabajo ágil, sin perder la formalidad necesaria para proyectos académicos o profesionales.

---

## 4. Manual de instalación

**Instrucciones para la instalación de la herramienta seleccionada apra el testeo.**

Dado que se está utilizando Laravel 10 para el desarrollo del proyecto, resulta conveniente utilizar una dependencia ya incluída para php. Dicha herramienta es el phpunit, nos permite realizar pruebas unitarias y de características. 

Las pruebas unitarias se centran en verificar el funcionamiento de componentes individuales, como métodos o clases, mientras que las pruebas de características evalúan el comportamiento completo de la aplicación desde la perspectiva del usuario.

Es importante cumplir con los requisitos para poder hacer uso de la misma, los cuáles son:

- PHP: PHPUnit requiere PHP 7.3 o superior.
- Composer: Es recomendable instalar PHPUnit a través de Composer.

Su instalación es sencilla, solamente debemos seguir los siguientes pasos:

1. Instalar PHPUnit 
-- Usar comando composer

![paso 1.1](https://i.pinimg.com/736x/b5/1f/b8/b51fb8d69ace23e536e12ca825c4fae9.jpg)

-- Verificar instalación
![paso 1.2](https://i.pinimg.com/736x/84/34/7f/84347feebf7971a62c418a6cd0776e24.jpg)

2. Configurar PHPUnit

Después de correr el comando de instalación, se añadirá un archivo llamado phpunit.xml. Aquí deberemos configurar algunas cosas relacionadas a la conexión de la base de datos

- Archivo xml
 ![paso 2.1](https://i.pinimg.com/736x/52/4a/78/524a788d8b5d37bd78be96f2b836434c.jpg)

- Configurando conexión a base de datos en archivo phpunit.xml, etiqueta php
![paso 2.2](https://i.pinimg.com/736x/08/49/f0/0849f09a3d9358782f90f8da013caad9.jpg)

3. Crear una prueba

Una vez hecho lo anterior podemos inicar creando nuestros archivos de prueba, usualmente para cada modulo se generá uno solo dónde contendrá todas los métodos de pruebas para verificar el cumplimiento de los requerimientos. Para crear una archivo de pruebas se debe ejecutar el siguiente comando:

      php artisan make:test NombreDeLaPrueba

Para el caso, creamos las pruebas:
- EmpleadosTest
- DescuentosTest
- AuthenticationTest

![paso 3](https://i.pinimg.com/736x/9f/d4/97/9fd497d49b764a2c5e3a227fb82c72c5.jpg)

4. Ejecutar prueba

Por último, solo queda comprobar que las pruebas definidas en cada archivo de testeo sean validadas correctamente. Ejecutar el comando siguiente:

 ```
      php artisan test --filter NombreDeLaPrueba
```

Esto ejecuta directamente el archivo de prueba especificado
![paso 4](https://i.pinimg.com/736x/6d/9d/d1/6d9dd14d1a07c588f87dfb4065842f7c.jpg)

---

## 5. Uso de la herramienta para 10 requerimientos

A continuación, se muestran los detalles de las pruebas realizadas

### EmpleadosTest

| **Nombre del Test**           | **Requerimiento Probado**                        | **Resultado Esperado**                                                                                                                                                      |
|-------------------------------|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `test_can_create_employee`     | Agregar un nuevo empleado.                      | Empleado registrado, redirigido a la lista de empleados y verificado en la base de datos.                                                                                    |
| `test_can_view_employee_details`| Ver detalles de un empleado.                    | Vista cargada con los detalles correctos del empleado.                                                                                                                       |
| `test_can_update_employee`     | Editar un empleado existente.                   | Datos del empleado actualizados, redirigido a la lista, y verificado que los datos antiguos fueron reemplazados.                                                             |
| `test_can_delete_employee`     | Eliminar un empleado.                           | Empleado eliminado, redirigido a la lista, y verificado que ya no está en la base de datos.                                                                                 |

![img](https://i.pinimg.com/736x/4c/1c/6f/4c1c6fcdaae0afbd42ce3ba92612b204.jpg)

### DescuentosTest

| **Nombre del Test**           | **Requerimiento Probado**                        | **Resultado Esperado**                                                                                                                                                      |
|-------------------------------|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `test_listar_descuentos`       | Listar los descuentos disponibles.               | Respuesta 200, vista muestra "Lista de descuentos".                                                                                                                          |
| `test_agregar_descuento`       | Agregar un nuevo descuento.                      | Descuento registrado, redirigido a la lista, y verificado en la base de datos.                                                                                               |

![img](https://i.pinimg.com/736x/a7/95/d4/a795d4a29fb2e0b649f65837836370b2.jpg)

### AuthenticationTest

| **Nombre del Test**           | **Requerimiento Probado**                        | **Resultado Esperado**                                                                                                                                                      |
|-------------------------------|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `test_login_screen_can_be_rendered` | Pantalla de login renderizada correctamente.   | Pantalla de inicio de sesión cargada con éxito, estado 200.                                                                                                                  |
| `test_users_can_authenticate_using_the_login_screen` | Iniciar sesión con credenciales válidas.   | Usuario autenticado, redirigido al dashboard.                                                                                                                               |
| `test_users_can_not_authenticate_with_invalid_password` | Error con credenciales incorrectas.       | Usuario no autenticado, redirigido a login, error en la sesión: "Estas credenciales no coinciden con nuestros registros".|

![img](https://i.pinimg.com/736x/b7/1d/71/b71d712193142a043292b7fc17917653.jpg)


---

## 6. Video tutorial
### Pruebas de software 
Ingresar al siguiente enlace para ver el testeo de 3 requerimientos usando PHPUnit [Ver video tutorial](https://drive.google.com/file/d/1YnqJI1ZNla55dgLW5HjycDfe92Nvz9ii/view?usp=drive_link).

### Documentación de software
Ingresar al siguiente enlace para ver como es el uso de la herramienta Dillinger para la documentación [Ver video tutorial](https://drive.google.com/file/d/1Zjgh1pZQB3OCh58VrQoLiGXXrK-T1j-M/view?usp=drive_link).

### Extra

Para ver el contenido de este PDF en su forma markdown, html o en un repositorio, ver en la carpeta compartida de google drive

[Otros formatos](https://drive.google.com/file/d/1Zjgh1pZQB3OCh58VrQoLiGXXrK-T1j-M/view?usp=drive_link)

---

## Bibliografía

Referencias utilizadas en el desarrollo del documento.

1. Sentrio. (2023, 13 septiembre). ¿Qué es Selenium? Sentrio. https://sentrio.io/blog/que-es-selenium/
2. Cruz, E. (2023, 26 mayo). Todo lo malo de Selenium: Limitaciones y desafíos. https://www.linkedin.com/pulse/todo-lo-malo-de-selenium-limitaciones-y-desaf%C3%ADos-erick-cruz/
3. Jimenezh, F. (2024, 14 febrero). Introducción a Cypress: ventajas y desventajas | Pragma. Medium. https://medium.com/somos-pragma/cypress-c8c985ef36b5
4. Moultamis, R. (2024, 4 septiembre). Tricentis y su impacto en el desarrollo de software. Blog de Hiberus. https://www.hiberus.com/crecemos-contigo/tricentis-impacto-desarrollo-software/
5. PHPUnit | Marco de Desarrollo de la Junta de Andalucía. (s. f.). https://www.juntadeandalucia.es/servicios/madeja/contenido/recurso/273
6. Jesús. (2023, 26 diciembre). ¿Qué es PHPUnit? Explorando el corazón de las pruebas en PHP. Tutoriales Dongee. https://www.dongee.com/tutoriales/que-es-phpunit/
7. LaTeX Fácil: Guía rápida de LaTeX. (s. f.). https://nokyotsu.com/latex/guia.html#:~:text=LaTeX%20es%20un%20sistema%20de,papel%20o%20mostrar%20en%20pantalla.
---
