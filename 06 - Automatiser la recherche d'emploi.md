#  **Introduction à l'exercice : Automatiser la recherche d'emploi**


- L'objectif principal de cet exercice est de montrer comment tirer parti des outils numériques pour rendre la recherche d'emploi plus efficace et mieux organisée. 
- En automatisant certaines tâches répétitives, comme la collecte d'offres d'emploi ou le suivi des candidatures, les étudiants apprendront à utiliser des outils modernes pour optimiser leur temps et leurs efforts.

Grâce à cet exercice, vous découvrirez :
1. **Comment configurer des alertes sur des plateformes d'emploi comme LinkedIn et Indeed** pour recevoir automatiquement des offres correspondant à vos critères.
2. **Comment utiliser un outil d’automatisation comme Zapier** pour enregistrer ces offres directement dans un tableau Google Sheets, sans avoir à tout copier manuellement.
3. **Comment créer et gérer un tableau de suivi des candidatures**, qui vous permettra de visualiser où vous en êtes dans vos démarches et d'adopter une approche proactive dans votre recherche d'emploi.

Cet exercice a pour but de :
- Vous apprendre à maîtriser des outils simples mais puissants pour la gestion de tâches.
- Vous initier à l'automatisation, une compétence de plus en plus recherchée dans le monde professionnel.
- Vous aider à structurer et organiser efficacement votre recherche d’emploi, tout en réduisant le stress lié à la gestion des nombreuses offres et candidatures.

En réalisant cet exercice, vous allez non seulement développer des compétences techniques pratiques, mais aussi gagner en productivité et en confiance dans vos démarches professionnelles.

# **1. Créer des alertes d’emploi sur LinkedIn et Indeed**

### **LinkedIn** (Gratuit)
1. Connectez-vous à votre compte LinkedIn (ou créez-en un [ici](https://www.linkedin.com/)).
2. Cliquez sur l’onglet **"Emplois"** dans le menu supérieur.
3. Dans la barre de recherche, entrez un mot-clé (exemple : "développeur web") et une localisation (exemple : "Paris").
4. Une fois les résultats affichés :
   - Cliquez sur le bouton **"Créer une alerte"** à côté de la barre de recherche.
   - Choisissez si vous voulez recevoir des notifications par e-mail ou directement dans l’application.
5. Répétez cette opération pour d'autres mots-clés ou localisations si nécessaire.

### **Indeed** (Gratuit)
1. Allez sur [Indeed](https://www.indeed.fr/) et connectez-vous (ou créez un compte gratuit).
2. Entrez un mot-clé (exemple : "assistant administratif") et une localisation (exemple : "Lyon").
3. Cliquez sur **"Rechercher"**.
4. En bas de la page des résultats, cliquez sur **"Recevoir des offres par e-mail"**.
5. Confirmez votre adresse e-mail pour activer l’alerte.

---

# **2. Créer un tableau de suivi dans Google Sheets**

1. Connectez-vous à votre compte Google (ou créez-en un gratuitement [ici](https://accounts.google.com/)).
2. Ouvrez **Google Sheets** en allant sur [Google Sheets](https://sheets.google.com/).
3. Cliquez sur le bouton **"+"** pour créer un nouveau tableau.
4. Ajoutez les colonnes suivantes sur la première ligne (elles serviront à organiser les offres d’emploi) :
   - **Nom de l’entreprise** (exemple : Microsoft)
   - **Titre du poste** (exemple : Analyste de données)
   - **Lien de l’offre** (le lien direct vers l’offre d’emploi)
   - **Date de publication** (exemple : 18/12/2024)
   - **Statut** (choisissez parmi : "À postuler", "Candidature envoyée", "En attente", "Accepté", "Refusé")
5. Enregistrez le fichier en cliquant sur **"Fichier" > "Renommer"** et donnez-lui un nom, par exemple : **"Suivi des candidatures"**.

---

# **3. Automatiser l’ajout des offres avec Zapier**

### Étape 1 : S'inscrire sur Zapier
1. Allez sur [Zapier](https://zapier.com/) et créez un compte gratuit.
2. Une fois connecté, cliquez sur **"Make a Zap"** pour créer une automatisation.

### Étape 2 : Configurer un déclencheur
1. Dans la barre de recherche, recherchez **"Email by Zapier"**.
2. Cliquez dessus et choisissez **"New Inbound Email"** comme déclencheur.
3. Zapier vous donnera une adresse e-mail personnalisée (par exemple : `random@zapiermail.com`).
   - **Important** : Notez cette adresse, vous en aurez besoin plus tard.
4. Cliquez sur **"Test Trigger"** pour vérifier que tout fonctionne.

### Étape 3 : Configurer une action (Google Sheets)
1. Cliquez sur **"+"** (action).
2. Recherchez **"Google Sheets"** et sélectionnez **"Create Spreadsheet Row"**.
3. Connectez votre compte Google à Zapier.
4. Choisissez le fichier Google Sheets créé précédemment (**"Suivi des candidatures"**).
5. Associez les colonnes du tableau aux informations que vous voulez importer :
   - **Nom de l’entreprise** → Rempli manuellement ou à partir de l’e-mail reçu.
   - **Titre du poste** → Rempli manuellement ou depuis l'e-mail.
   - **Lien de l’offre** → Copié depuis l’e-mail.
   - **Date de publication** → Ajoutée automatiquement.
6. Testez votre Zap pour vérifier qu’une nouvelle ligne est bien ajoutée dans votre tableau.

### Étape 4 : Finaliser et activer le Zap
1. Cliquez sur **"Turn on Zap"** pour activer l’automatisation.
2. Désormais, chaque fois que vous transférez un e-mail contenant une offre d’emploi à l’adresse Zapier, elle sera ajoutée à votre tableau Google Sheets.

---

# **4. Gérer les candidatures dans Google Sheets**

1. Ouvrez régulièrement votre tableau Google Sheets.
2. Mettez à jour la colonne **"Statut"** pour suivre vos candidatures :
   - **"Candidature envoyée"** : une fois l’offre postulée.
   - **"En attente"** : en attendant une réponse.
   - **"Accepté"** ou **"Refusé"** : selon la décision finale.
3. Utilisez des couleurs pour vous organiser (exemple : vert pour accepté, rouge pour refusé, jaune pour en attente).

---

## **Temps total pour débutants :**
- Configuration des alertes : **15 minutes**.
- Création du tableau Google Sheets : **10 minutes**.
- Automatisation avec Zapier : **30 à 45 minutes**.


# Conclusion: 
Si vous suivez ces étapes, vous aurez une solution simple et efficace pour organiser et automatiser votre recherche d’emploi ! 
