"Spam Blocking with NLP (Natural Language Processing) in Python

Ce dépôt contient un projet Python pour la création d'un script de blocage des spams dans une application de messagerie personnalisée. Le script utilise des techniques de NLP, notamment la vectorisation TF-IDF et le modèle de classification Naive Bayes, pour détecter et bloquer les messages indésirables.

Le projet comprend les étapes suivantes :
- Collecte de données étiquetées contenant des exemples de messages spam et non spam à partir de diverses applications de messagerie telles que Twilio, Lemlist, Waalaxy, Mailchimp, Brevo.
- Prétraitement des données, y compris la normalisation du texte, la suppression des caractères indésirables et des mots vides, et la lemmatisation.
- Vectorisation des données en utilisant la méthode TF-IDF pour représenter les messages sous forme de vecteurs de fonctionnalités.
- Entraînement d'un modèle de classification Naive Bayes à l'aide des données d'entraînement prétraitées et vectorisées.
- Évaluation du modèle en utilisant des données de test séparées et génération d'une matrice de confusion pour évaluer les performances de classification.

Ce dépôt contient également un script Python principal qui permet de bloquer les spams en utilisant le modèle entraîné. Il suffit de fournir un message en entrée et le script prédit si le message est un spam ou non.

Contributions, suggestions et commentaires sont les bienvenus !
