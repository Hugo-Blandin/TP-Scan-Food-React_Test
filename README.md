# Tests unitaires - TP : App Scan Food

TP App Scan Food et ses tests unitaires

## Installation

Récupérez le dépôt

`git clone https://github.com/R-17/TP-Scan-Food-React_Test.git`

Positionnez vous dans le répertoire de l'application puis lancez :

`npm install`

Une fois les dépendances installées pour lancer l'application, lancez la commande :

`npm start`

## Utilisation de l'APP

Saissez les 13 chiffres sous le code barre d'un produit **alimentaire** puis cliquez sur le bouton +

> Vous pouvez également scannez les codes barre avec votre webcam, pour cela validez les autorisations et appuyez sur le bouton bleu à gauche avec un code barre.

**Nb :** Personellement le scan via la webcam avant ne fonctionne pas mais avec la caméra arrière oui (deux caméras sur une surface)

**Nb :** Pour le scannage restez quelques instants sans bouger tant que l'image du code barre ne devient pas nette.

## Test unitaires

`npm test -- --coverage`
