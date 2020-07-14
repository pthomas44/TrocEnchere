# TrocEnchere

*********** Contexte ***********

    - Projet réalisé dans le cadre de mon diplôme Développeur Web et Web Mobile (à l’ENI Ecole informatique)
    - équipe de 4 personnes
    - Nous avions 2 semaines pour aller le plus loin possible dans une liste de fonctionnalités à réaliser.

*********** Sujet ***********

Les utilisateurs (non inscrits) peuvent :

    - rechercher un article en vente (accueil)
        - par défaut, triés par date de parution
        - rechercher par catégorie
        - rechercher par mot clé
        - rechercher par catégorie et mot clé
    - s'inscire
    
Les utilisateurs inscrits peuvent :

    - se connecter
    - se déconecter
    - rechercher un article en vente (accueil)
        - par défaut, triés par date de parution
        - rechercher par catégorie
        - rechercher par mot clé
        - rechercher par catégorie et mot clé
    - mettre un article à vendre
    - voir le détail d'un article en vente
    - enchérir sur un article en vente
    - afficher l'adresse de retrait s'il a remporté l'enchère
    - modifier leur profil


*********** Outils ***********

    - JavaEE
    - Tomcat
    - SQL Server / SQL Server Management Studio
    - Git / Gogs

*********** Mon travail (dans trocenchere.zip) ***********

   - DAL
        - DAOFactory
        - ArticlesDAO
        - ArticlesDAOJdbcImpl (une partie)
        - ConnectionProvider
        - RetraitsDAO
        - RetraitsDAOJdbcImpl
        
   - BO
        - Articles
        - Catégories
        - Encheres
        - Retraits
        - Utilisateurs
        
   - BLL
        - GestionArticles (une partie)
        - GestionRetraits
        - VerifArticle
        - VerifRetrait
        
   - Servlets
        - Accueil (doGet) (une partie)
        - HistoriqueServlet
        - ServletTestPoolConnexion
        - VenteArticleServlet
        
   - JSP
        - Accueil (une partie)
        - Historique
        - VenteArticle
	
   - JSPF
        - Header
        - Footer
		
   - XML
        - Context
