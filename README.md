# DAMN VULNERABLE WEB APPLICATION

Ce projet est une copie du projet original disponible ici : https://github.com/ethicalhack3r/DVWA

> Damn Vulnerable Web Application (DVWA) est une application Web PHP / MySQL qui est sacrément vulnérable. Son objectif principal est d'aider les professionnels de la sécurité à tester leurs compétences et leurs outils dans un environnement juridique, à aider les développeurs Web à mieux comprendre les processus de sécurisation des applications Web et à aider les étudiants et les enseignants à en apprendre davantage sur la sécurité des applications Web dans une classe contrôlée. 

Cette copie a été modifiée afin d'ajouter des extensions afin de tester les ateliers du site de promulgation des techniques de sécurisation des sites Web, disponible ici : https://secuweb.aesisoft.fr/

___

## ATTENTION !

Attention : n'installez PAS cette application sur un serveur accessible via Internet ! <br/>
DVWA signife Damn Vulnerable Web Application : les failles qui y sont contenues pourrait permettre de faire des ravages sur un serveur. <br/>
Installez cette application que sur votre localhost à des fins de tests, ou encore mieux, sur une VM.

## Avertissement
Nous déclinons toute responsabilité quant à la manière dont quiconque utilise cette application (DVWA). Nous avons précisé les objectifs de la demande et elle ne doit pas être utilisée à des fins malveillantes. Nous avons donné des avertissements et pris des mesures pour empêcher les utilisateurs d'installer DVWA sur des serveurs Web en direct. Si votre serveur Web est compromis via une installation de DVWA, ce n'est pas notre responsabilité, c'est la responsabilité de la personne / des personnes qui l'a téléchargé et installé.

___

## Licence

Ce fichier fait partie de Damn Vulnerable Web Application (DVWA).

Damn Vulnerable Web Application (DVWA) est un logiciel gratuit: vous pouvez le redistribuer et / ou le modifier selon les termes de la GNU General Public License telle que publiée par la Free Software Foundation, soit la version 3 de la licence, ou (à votre choix) toute version ultérieure.

Damn Vulnerable Web Application (DVWA) est distribué dans l'espoir qu'il sera utile, mais SANS AUCUNE GARANTIE; sans même la garantie implicite de QUALITÉ MARCHANDE ou D'ADÉQUATION À UN USAGE PARTICULIER. Voir la Licence Publique Générale GNU pour plus de détails.

Vous devriez avoir reçu une copie de la Licence Publique Générale GNU avec Damn Vulnerable Web Application (DVWA). Sinon, voir http://www.gnu.org/licenses/ .

___

## Installation

1. Cloner l'application sur votre serveur Apache localhost
2. Configurer l'accès au serveur de données dans le fichier config/config.inc.php
3. Lancer l'application et cliquer sur le bouton Create / Reset Database
4. Connectez-vous avec le login "admin" et le password "password".

## Configuration pour tester les vulnérabilités

Pour tester les failles indiqués dans les ateliers, mettez-vous sur le niveau le plus faible pour commencer : <br/>
Cliquer sur le bouton "DVWA Security" et choississez "Low", enregistrer.

Il faut le refaire à chaque connexion.
