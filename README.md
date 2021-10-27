# Projet 7 OpenClassrooms du parcours Développeur Web d'OpenClassrooms : Créer un réseau social d'entreprise

Compétences évaluées :

- Authentifier un utilisateur et maintenir sa session
- Personnaliser le contenu envoyé à un client web
- Gérer un stockage de données à l'aide de SQL
- Implémenter un stockage de données sécurisé en utilisant SQL

### Installation

---

Clonez le repo : `https://github.com/karimc77/KarimCheaibi_7_28102021`

#### Pour lancer le frontend :

- Ouvrez le terminal de votre IDE et tapez : `cd frontend`
- Exécutez ensuite la commande `npm install`
- Lancez enfin la commande `npm run serve`
- L'interface client est disponible à l'URL suivante : http://localhost:8080/

#### Pour le backend suivez ces instructions :

- Ouvrez le terminal de votre IDE et tapez : `cd backend`
- Initialisez les packages via la commande `npm install`
- Lancez le backend en tapant ensuite `nodemon`
- Vérifiez bien que le backend communique via le port `:3000`

#### Mettez en place la base de données de cette manière :

- Connectez vous au serveur MySQL
- Lancez la commande suivante pour créer la base de données : `CREATE DATABASE groupomania`
- Vérifiez que vos identifiants de base de données correspondent avec ceux renseignés dans le fichier .env disponible dans le dossier Backend. Si ce n'est pas le cas, modifiez-les au sein du fichier .env
- Importez enfin le fichier .sql disponible dans le dossier DB du backend en tapant la commande suivante : `mysql -u votreidentifiant -p groupomania < dump_groupomania.sql`

#### Enfin vous pouvez accéder à l'application !

- Lancez-la via http://localhost:8080/
- Un compte admin est déjà disponible, connectez-vous avec l'identifiant `Admin`et le mot de passe `Admin12345@`
- Et voilà !
