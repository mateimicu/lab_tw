---
title: "05 - PHP"
date: 2022-03-03T21:46:18+02:00
draft: false
---

#### Recuperare laborator
Laboratorul 7 (09.04.2022) nu se tine, vom extinde laboratorul 6 (02.04.2022) pentru a recupera. Astfel

* laboratorul de la 10:00-12:00 va incepe la 9:00 si se va termina la 12:00
* laboratorul de la 12:00-14:00 va incepe la 12:00 si se va termina la 15:00

In practica fiecare laborator va fi extins cu o ora.
Pentru a va ajuta cu proiectele o sa avem o ora de consultatii in saptamana 8, dar o sa stabilim mai tarziu exact cand (in functie de partialele voastre).
[Laborator PHP](./php.pdf)

[Prezentarea Curs si informatii utile](https://profs.info.uaic.ro/~busaco/teach/courses/web/web-film.html#week5)


### Informatii Utile

Tools:

* ⭐ [ReplIT](https://replit.com/) este recomandat
* [JSFiddle](https://jsfiddle.net/)
* [VisualStudioCode](https://code.visualstudio.com/)

Documentatie:

* [PHP Manual](https://www.php.net/manual/en/index.php)
* [PHP W3schools](https://www.w3schools.com/php/)
* [Exemple de programe PHP](https://profs.info.uaic.ro/~busaco/teach/courses/web/demos/php/php.zip)
* [PHP Tutorial for Beginners](https://www.guru99.com/php-tutorials.html)
* [Clean Code PHP](https://github.com/jupeter/clean-code-php#readme)
* [Design Patterns in PHP](https://refactoring.guru/design-patterns/php)
* [PHP Usage Statistics](https://w3techs.com/technologies/overview/programming_language)

* [Popular tech stacks](https://stackshare.io/stacks)
* [ddosify](https://github.com/ddosify/ddosify)
* [Master the command line, in one page](https://github.com/jlevy/the-art-of-command-line)
* [Awesome design patterns](https://github.com/DovAmir/awesome-design-patterns)
* [Naming-cheatsheet](https://github.com/kettanaito/naming-cheatsheet)
* [How to be a Programmer](https://github.com/braydie/HowToBeAProgrammer)
* [Awesome distributed systems books](https://github.com/zhenlohuang/awesome-distributed-systems)
* [The Good Docs Project](https://thegooddocsproject.dev/)
* [Mega Project List](https://github.com/karan/Projects)
* [Free for devs](https://free-for.dev/#/)
* [SAAS](https://sass-lang.com/guide)
* [Sass Guidelines](https://sass-guidelin.es/)


### Exercitii

1. Creati un formular cu doau camputi "Nume" si "Email".
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <title>PHP Form</title>
</head>
<body>
    <main>
        <?php if ($_SERVER['REQUEST_METHOD'] === 'GET') : ?>
          <div class="well">
            <form action="..." method="post">
            ...
            </form>
          </div>
        <?php else : ?>
        ...
        <?php endif ?>
    </main>
</body>
</html>
```
![formular subscribe](./ex1_1.png)
![rezultat formular subscribe](./ex1_02.png)

2. Creati un formular care va ajuta sa adunati doua numere. Folotiti o functie pentru adunarea a doua numere.
![formular adunare](./ex2_1.png)
![rezultat formular adunare](./ex2_2.png)

3. Completati codul de mai jos
```php
<html>
<body>
  <p> What is the closest number to 79 in the array [ 1, 4, 20, 69, 100, 145, 163, 244, 268]?</p>

  <?php
    function computeClosestNumber($target, $array) {
      return "fix me"
    }

    $closestNumber = computeClosestNumber(79, array(1, 4, 20, 69, 100, 145, 163, 244, 268));

    echo "The closest number is $closestNumber";
  ?>
</body>
</html>
```

