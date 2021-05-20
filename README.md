# Teaching-HEIGVD-RES-2021-Challenge-TE-2

A la fin du challenge, vous pourrez envoyer vos réponses et captures d'écran dans le formulaire suivant: https://forms.gle/54dExdhVcsSqeCKs6

## Exercice 1 Docker

* Nous avons publié une image avec le nom **`oliechti/quest`** sur Docker Hub
* Dans cette image, nous avons créé **un fichier texte** que nous avons placé dans le répertoire **`/j/en/ai/`**
* Votre mission est de retrouver **le nom** et le **contenu** de ce fichier
* Quand vous l'avez trouvé, faites une **capture d'écran** avec votre terminal et gardez **une copie du texte** (pour pouvoir le mettre dans le formulaire Google Forms)



## Exercice 2 HTTP

L'objectif du challenge est de vérifier que vous connaissez la **syntaxe du protocole HTTP** et que vous avez compris la notion de **négociation de contenu**. 

L'objectif est également de vérifier que vous êtes capable **d'utiliser des outils et/ou d'écrire du code** pour faire des opérations de base avec HTTP.

### Etape 1 (Padawan): Etes-vous capable de dialoguer avec un serveur?

Nous avons développé une application web, disponible sur Internet. Elle permet d'accéder à la resource suivante: http://194.182.161.159/challenge-padawan.

* Vous devez d'abord ajouter un **query string** à cette URL, dans lequel vous donnez un paramètre appelé très précisément **`email`** ayant pour valeur **votre adresse** à la HEIG-VD (e.g. `olivier.liechti@heig-vd.ch`).
* Vous devez ensuite **demander une représentation JSON** de cette ressource au serveur.
* Dans l'objet JSON que vous aurez reçu, vous trouverez un attribut appelé **`token`** contenant une chaîne alphanumérique. Vous devez **transformer** cette chaîne alphanumérique en mettant toutes les lettres en **majuscule** et en changeant toutes les occurrences du chiffre **9** par la lettre **`N`** (e.g. **`a83b99`** > **`A83BNN`**).
* Vous devez ensuite **préparer un nouvel objet JSON**, dans lequel vous indiquerez **3 attributs**: l'attribut **`oldToken`** avec la valeur récupérée dans la première réponse, l'attribut **`newToken`** avec votre la transformation appliquée, et l'attribut **`email`** avec votre adresse.
* Vous devez finalement **envoyer cet objet JSON** vers l'URL http://194.182.161.159/challenge-padawan/responses/}. La réponse vous indiquera si vous avez réussi cette partie du challenge, grâce à l'attribut **`result`**. Faites une capture d'écran et copiez le texte de la réponse pour pouvoir les donner dans le formulaire Google Forms à la fin.

### Etape 2 (Jedi): Etes-vous capable de dialoguer *rapidement*?

Dans cet exercice, vous devez faire la même chose, mais très, très rapidement. Vous devez aussi utiliser 2 URLs différents:

* http://194.182.161.159/challenge-jedi
* http://194.182.161.159/challenge-jedi/responses

Comme dans l'exercice 1, faites une capture d'écran et copiez le texte de la réponse pour pouvoir les fournir dans le formulaire Google Forms.