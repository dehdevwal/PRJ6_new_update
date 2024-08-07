<h1>Projet de Chatbot Basé sur le Système RAG avec Spring AI et React</h1>

<h2>Objectif du projet</h2>
<p>
    Le projet vise à développer une application web full-stack qui met en œuvre un Chatbot basé sur un système de génération augmentée par récupération (RAG) utilisant les modèles de langage Llama 3 et OpenAI. L'application utilise Spring AI côté backend et React avec VAADIN côté frontend. L'objectif principal est de démontrer une intégration efficace des technologies modernes pour créer un chatbot intelligent et performant.
</p>

<h2>Description des composants</h2>

<h3>Backend (Spring AI)</h3>
<p>
    Le backend est responsable de la gestion des interactions avec les modèles de langage et le stockage des vecteurs. Les principales fonctionnalités incluent :
<img src="captures/4.png">
</p>
<ul>
    <li><strong>Gestion des requêtes de chat</strong> : Interagir avec les modèles Llama 3 et OpenAI pour générer des réponses aux questions des utilisateurs.</li>
    <li><strong>Vectorisation des documents</strong> : Utiliser un modèle d'embedding pour vectoriser des documents PDF et stocker les vecteurs dans une base de données PostgreSQL.</li>
    <li><strong>Système RAG</strong> : Intégrer le système de génération augmentée par récupération pour améliorer la pertinence et la précision des réponses du chatbot.</li>
</ul>

<h3>Frontend (React avec VAADIN)</h3>
<p>
    Le frontend offre une interface utilisateur intuitive pour interagir avec le chatbot et gérer les documents. Les principales fonctionnalités incluent :
<img src="./captures/1.png">
</p>

<ul>
    <li><strong>Interface de chat</strong> : Permettre aux utilisateurs de chatter avec le chatbot et de recevoir des réponses générées par les modèles de langage.</li>
    <li><strong>Gestion des documents</strong> : Permettre l'upload de documents PDF pour leur vectorisation et leur stockage.</li>
    <li><strong>Visualisation des réponses</strong> : Afficher les réponses générées par le système RAG de manière claire et compréhensible pour l'utilisateur.</li>
</ul>

<h2>Configuration et gestion des services</h2>

<h3>Vector Store</h3>
<ul>
    <li><strong>Simple Vector Store</strong> : Implémenter un stockage simple pour les vecteurs, permettant de vectoriser et stocker des documents PDF en utilisant un modèle d'embedding.</li>
    <li><strong>Migration vers PD Vector Store</strong> : Migrer les vecteurs existants vers un PD Vector Store pour une gestion plus efficace et évolutive des vecteurs.</li>
</ul>
<img src="captures/3.png">

<h3>Intégration des modèles de langage</h3>
<ul>
    <li><strong>OpenAI et Llama 3</strong> : Intégrer les modèles de langage pour générer des réponses aux questions des utilisateurs.</li>
    <li><strong>Système RAG</strong> : Utiliser la génération augmentée par récupération pour améliorer les réponses en se basant sur les documents vectorisés.</li>
</ul>

<h2>Interface utilisateur</h2>
<p>
    Une interface utilisateur développée avec React et VAADIN permet aux utilisateurs d'interagir facilement avec le système. Les fonctionnalités principales incluent :
</p>
<ul>
    <li><strong>Chatbot</strong> : Une interface de chat pour communiquer avec le chatbot intelligent.</li>
    <li><strong>Gestion des documents</strong> : Une interface pour uploader et gérer les documents PDF à vectoriser.</li>
    <li><strong>Visualisation des vecteurs</strong> : Afficher les vecteurs générés et les utiliser pour améliorer les réponses du chatbot.</li>
</ul>
<img src="captures/2.png">
