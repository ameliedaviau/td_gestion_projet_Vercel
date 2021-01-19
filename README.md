![Angular Logo](https://github.com/vercel/vercel/blob/master/packages/frameworks/logos/angular.svg)

# Angular Example

This directory is a brief example of an [Angular](https://angular.io/) app that can be deployed with Vercel and zero configuration.

## Deploy Your Own

Deploy your own Angular project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/vercel/tree/master/examples/angular)

_Live Example: https://angular.now-examples.now.sh_

### How We Created This Example

To get started with Angular, you can use the [Angular CLI](https://cli.angular.io/) to initialize the project:

```shell
$ ng new
```


######################################### REPONSES QUESTIONS TD ########################################

Question 4 :	$vercel -v

Question 5 : 	$vercel init

Question 6 : 	en se positionnant dans le dossier angular : $vercel

Question 7 : 	$vercel ls

Question 8 : 	$vercel log tdgestionprojet.vercel.app

Question 9 : 	$vercel inspect tdgestionprojet-bzygd4ovb.vercel.app (avec l'adresse unique de deploiement)
On obtient des informations générales ainsi que les différents builds et routes. 
On a l'id, le name, l'url et l'état (ici READY).

Question 10 : 	Les variables d’environnement sont des variables dynamiques 
pouvant être utilisées par plusieurs processus fonctionnant simultanément. 
Cela permet d'injecter des valeurs qui ne sont pas directement dans le code et de modifier son comportement 
en fonction de l'environnement dans lequel il s'exécute.

Question 11 : 	$vercel env add plain MYVARENV production  (value = 10)

Question 12 : 	$vercel env ls

Question 13 : 	Les secrets sont des variables d'environnement mais dont la valeur 
reste cachée. Utile pour un mot de passe par exemple.

Question 14 : 	sur l'appli web j'ai créé ma variable secrete "mysecret", elle apparait dans les variables
d'environnement lorsque je les liste avec ls.

Question 15 : 	$vercel secrets add mynewsecret daviau   je créée la value avec le secrete
$vercel env add secret MYNEWENVSECRET production   je créee la variable d'environnement 
et lorsqu'elle demande la value je rentre "mynewsecret" 

si je vérifie avec ls, ma variable d'environnement est bien crypté par ma variable secret

Question 16 : 	production, preview et development
Ces trois environnement permettent de mieux organiser le code et de bien séparer les 
différentes parties pour n'en modifier qu'un seul par la suite si besoin.

Question 17 : 	


