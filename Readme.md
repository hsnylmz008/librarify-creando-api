# 📖 Librarify. Creating an API with Symfony 5 📖

<img src = "https://raw.githubusercontent.com/ger86/librarify-back/master/cover.jpg" alt = "Librarify. Creating an API with Symfony 5">

## Support me buying me a coffe

[☕️ Buy me a coffe] (https://www.buymeacoffee.com/hsnylmz008)

## Description

** Librarify. Creating an API with Symfony 5 ** is a complete course on Symfony 5 in which I tell how to develop an API from scratch using the FOS Rest Bundle (the reasons for this decision are explained in episode number 5). This API will allow us to manage our personal library, that is, it will allow us to:

- Carry out CRUD operations on our books.
- Carry out CRUD operations on the authors.
- Carry out CRUD operations on the categories that we assign to them.

In addition, the course will also focus on good practices when working with Symfony. We will use services to group the logic, DTO's to manage forms and we will try to write controllers as short as possible.

My goal is also to dedicate the final chapters of the course to such interesting things as:

- Creation of an administrator using ** Easy Admin **.
- Add authentication through JWT through the LexikJWTAuthenticationBundle.
- Deploy the project on an AWS EC2 instance using the ** PHP Deployer ** tool.
- ** Dockerize ** the project.

As you can see, it is a complete course if you want to start working on Symfony and that I intend to keep updated as updates to this PHP framework come out.

## Chapters

This ** Symfony 5 ** course consists of the following chapters to date:

1. [Chapter 1. Project Configuration] (https://youtu.be/cYCCCgrFSi4)
2. [Chapter 2. Controllers and routes] (https://youtu.be/1A5MjnagJgE)
3. [Chapter 3. Services and container] (https://youtu.be/6YTn5QaOeQA)
4. [Chapter 4. Database and integration with Doctrine] (https://youtu.be/e_3ycxP02ig)
5. [Chapter 5. FOS Rest Bundle] (https://youtu.be/xPjpoC1BNII)
6. [Chapter 6. Forms] (https://youtu.be/9rRkryF-JK8)
7. [Chapter 7. DTO's and image uploads] (https://youtu.be/Jw-vTsBJ30c)
8. [Chapter 8. Services and PHP Unit] (https://youtu.be/qLoaGwWuvIM)
9. [Chapter 9. Categories and Collection Type] (https://youtu.be/akrxXdp9LdQ)

## Run the project

1. Clone the repository.
2. Make sure you have a MySQL server running on your computer.
3. Run `composer install` at the root of the project.
4. Install the database migrations: `bin / console doctrine: migrations: migrate`.
5. Start the local development server: `symfony server: start`.
6. Happy codding!
