# Informatics
Session 4: Q* Anonymous - Information treatment
Etant donné que votre travail était remarquable, Anonymous vous a à nouveau contacté avec une autre tâches risquée. Ils manquent de main d'oeuvre et aimeraient que traitiez les données que vous leur avez donné.

Ils veulent que vous construisiez une fonction qui transformera votre précédente sortie en quelque chose de plus simple et plus rapide à traiter. C'est à vous de voir comment transformer l'information en un pattern utilisable!

Créez une fonction treatment(data) pour transformer l'information que vous avez précédemment retourné en un pattern :

Chaque suite d'éléments communs devrait être indiqué par la nature de l'élément suivi de '*' et le nombre d’occurrence sans autre éléments entre.

Exemple:

Avec le code '66AeB7' votre précédente fonction sortirait 'number number vowel-up vowel-low consonant-up number'.

Avec cette sortie en entrée votre nouvelle fonction treatment sortirait la string suivante 'number*2 vowel-up*1 vowel-low*1 consonant-up*1 number*1'

N'hésitez pas à utiliser autant de sous-méthodes que vous jugez nécessaires.
_________________________________________________________________________________________________________________________________________________________________________________

Session 4: Q* Anonymous - Information extraction
Anonymous vient de vous engager sur le dark web pour une tâche dangereuse. Ils essayent de craquer un code depuis quelques jours mais ne sont arrivés à rien... pour le moment!

Ils veulent que vous construisiez une fonction qui analysera chaque caractère dans un code donné et que vous déterminiez sa nature. Le but est simple : ils ont l'intention d'utiliser les informations que vous leur fournirez pour trouver un pattern dans le code.

Créez une fonction extract(code) pour fournir des infos concernant la nature de chaque élément du code :

Par exemple, si le code 'AeB7' est donné en entrée, la fonction devrait produire 'vowel-up vowel-low consonant-up number' comme sortie. En général :

Ajoutez un number à la réponse si l'élément du code est un chiffre.
Ajoutez un vowel à la réponse si l'élément du code est une voyelle.
Ajoutez un consonant à la réponse si l'élément du code est une consonne.
Suivez cela par -up si la voyelle/consonne est en majuscule.
Suivez cela par -low si la voyelle/consonne est en minuscule.
Exemple :

Avec le code '65AeBc7' la fonction devrait sortir number number vowel-up vowel-low consonant-up consonant-up number
