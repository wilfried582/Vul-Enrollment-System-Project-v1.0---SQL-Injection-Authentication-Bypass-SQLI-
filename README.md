# Vul-Enrollment-System-Project-v1.0---SQL-Injection-Authentication-Bypass-SQLI-
Test de culnérabilité
# Description
Enrollment System Project V1.0, developed by Sourcecodester, has been found to be vulnerable to SQL Injection (SQLI) attacks. This vulnerability allows an attacker to manipulate the SQL queries executed by the application. The system fails to properly validate user-supplied input in the username and password fields during the login process, enabling an attacker to inject malicious SQL code. By exploiting this vulnerability, an attacker can bypass authentication and gain unauthorized access to the system.
# Réalisation de l'exploit
1- Télécharger l'application web "enrollment-system-using-php" sur la plateforme https://www.sourcecodester.com/php/14444/enrollment-system-project-source-code-using-phpmysql.html
2- Décompresser le fichier zip obtenu
3- Installer wamp puis mettre l'application dans le dossier www/
4- Lancer l'application http://localhost/enrollment/login.php
5- Déployer la base de données "enrollment_db"
6- Au niveau des champs d'authentification, mettre {' or 1=1 #} pour le password et le username et la dernière étape est de cliquer sur le login puis l'injection sql (bypass authentification) est réalisé, ce qui n'a pas marché.
# Capture de ca qui a été fait
![sw15](https://github.com/wilfried582/Vul-Enrollment-System-Project-v1.0---SQL-Injection-Authentication-Bypass-SQLI-/assets/61844545/c7d6793c-b5a0-4029-92a1-f62ad94e6837)
![sw16](https://github.com/wilfried582/Vul-Enrollment-System-Project-v1.0---SQL-Injection-Authentication-Bypass-SQLI-/assets/61844545/260b983f-9750-4a13-8e12-738687e78493)
![sw17](https://github.com/wilfried582/Vul-Enrollment-System-Project-v1.0---SQL-Injection-Authentication-Bypass-SQLI-/assets/61844545/103dbf2b-91a7-4a1a-b494-b144d1875909)

