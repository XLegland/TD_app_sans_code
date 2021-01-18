# TD_app_sans_code

4 On peut connaître la version de vercel en tapant la commande `vercel -v`. La version installée sur ma machine est la 21.1.0.

5 Pour créer un nouveau projet il faut se placer dans le répertoire où sont les fichiers puis entrer la commande `vercel` il y a ensuite plusieurs réponses auxquelles il faut répondre.

6 `vercel --prod`

7 `vercel list`

8 `vercel logs td-jzfrci8hn.vercel.app` td-jzfrci8hn.vercel.app est l'adresse de notre projet

9 `vercel inspect td-jzfrci8hn.vercel.app` elle sert à avoir des informations sur notre projet, comme son id, son nom et les routes 

10 Les variables d'environnement servent à rassembler plusieurs commandes en une seule afin de gagner du temps.

11 `vercel env add plain la`

12 `vercel env ls`

13 Les secrets sont des variables d'environnement spécifiques à un compte. Cela permet de séparer les différents rôles des acteurs du projet.

15 `vercel secret add url https://td-pi.vercel.app/`

16 Les 3 environnements sont Production, Preview et Development. Il permettent de cloisonner et d'organiser plus facilement les projets.



