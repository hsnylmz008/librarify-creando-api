# 📖 Librarify. Creando una API con Symfony 5 📖

<img src="https://raw.githubusercontent.com/ger86/librarify-back/master/cover.jpg" alt="Librarify. Creando una API con Symfony 5">

## Support me buying me a coffe

[☕️ Buy me a coffe](https://www.buymeacoffee.com/hsnylmz008)

## Descripción

**Librarify. Creando una API con Symfony 5** es un curso completo sobre Symfony 5 en el que cuento cómo desarrollar una API desde cero empleando FOS Rest Bundle (los motivos de esta decisión los cuento en el episodio número 5). Esta API nos permitirá gestionar nuestra biblioteca personal, es decir, nos permitirá:

- Realizar operaciones CRUD sobre nuestros libros.
- Realizar operaciones CRUD sobre los autores.
- Realizar operaciones CRUD sobre las categorías que les asignemos.

Además el curso también estará centrado en buenas prácticas a la hora de trabajar con Symfony. Emplearemos servicios para agrupar la lógica, DTO's para gestionar formularios y trataremos de escribir controladores lo más cortos posible. 

Mi objetivo también es dedicar los capítulos finales del curso a cosas tan interesantes como:

- Creación de un administrador mediante **Easy Admin**.
- Añadir autenticación mediante JWT por medio del bundle LexikJWTAuthenticationBundle.
- Desplegar el proyecto en una instancia EC2 de AWS empleando la herramienta **PHP Deployer**.
- **Dockerizar** el proyecto. 

Como véis, es un curso completo si queréis comenzar a trabajar sobre Symfony y que pretendo mantener actualizado conforme vayan saliendo actualizaciones de este framework de PHP.

## Capítulos

Este curso sobre **Symfony 5** consta de los siguientes capítulos hasta la fecha:

1. [Capítulo 1. Configuración del proyecto](https://youtu.be/cYCCCgrFSi4)
2. [Capítulo 2. Controllers y rutas](https://youtu.be/1A5MjnagJgE)
3. [Capítulo 3. Servicios y container](https://youtu.be/6YTn5QaOeQA)
4. [Capítulo 4. Base de datos e integración con Doctrine](https://youtu.be/e_3ycxP02ig)
5. [Capítulo 5. FOS Rest Bundle](https://youtu.be/xPjpoC1BNII)
6. [Capítulo 6. Formularios](https://youtu.be/9rRkryF-JK8)
7. [Capítulo 7. DTO's y carga de imágenes](https://youtu.be/Jw-vTsBJ30c)
8. [Capítulo 8. Servicios y PHP Unit](https://youtu.be/qLoaGwWuvIM)
9. [Capítulo 9. Categorías y Collection Type](https://youtu.be/akrxXdp9LdQ)

## Ejecutar el proyecto

1. Clona el repositorio.
2. Asegúrate de tener un servidor MySQL corriendo en tu ordenador.
3. Ejecuta `composer install` en la raíz del proyecto.
4. Instala las migraciones de base de datos: `bin/console doctrine:migrations:migrate`.
5. Levanta el servidor local de desarrollo: `symfony server:start`.
6. Happy codding!
