1. Creation d'un fichier top-tech-companies et installation des dependances
composer create-project symfony/website-skeleton top-tech-companies

2. Rentrer dans le projet
cd _______

3. Installation du server Web
composer require symfony/web-server-bundle --dev ^4.4.2

4. Run l'application
php bin/console server:run 
OR symfony serve

5. Fermer le server web
Ctrl+C

6. Creation d'un user
php bin/console make:user

7. Update le fichier 
src/Entity/User.php

8. Creation d'un controller
php bin/console make:controller ListController

9. Update le fichier
./src/Controller/ListController

10. Creation d'un nouveau controller
php bin/console make:controller RegistrationController

11. Update le fichier
 ./src/Controller/RegistrationController

12. Controller pour assurer le processus de login d'un utilisateur
php bin/console make:controller SecurityController

13. Creation de la forme de registre
php bin/console make:form

14. update le fichier
src/Form/UserType.php

15. Generer la forme pour login
php bin/console make:auth

16. update le fichier
src/Controller/SecurityController.php

17. 