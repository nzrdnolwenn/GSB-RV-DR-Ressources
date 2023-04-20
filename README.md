# GSB-RV-DR-Ressources
Ressources
    
    TABLES: 	
    
    +-----------------+
	| Tables_in_gsbrv |
	+-----------------+
	| Activitecompl   |
	| Composant       |
	| Connaitre       |
	| Constituer      |
	| Dosage          |
	| Famille         |
	| Formuler        |
	| Interagir       |
	| Inviter         |
	| Laboratoire     |
	| Medicament      |
	| Motif           |
	| Offrir          |
	| Posseder        |
	| Praticien       |
	| Prescrire       |
	| Presentation    |
	| RapportVisite   |
	| Realiser        |
	| Region          |
	| Secteur         |
	| Specialite      |
	| Travailler      |
	| TypeIndividu    |
	| TypePraticien   |
	| Visiteur        |
	+-----------------+
    
    
    ENTITÉS : 
    
    Praticien
    private String numero;
    private String nom;
    private String prenom;
    private String ville;
    private Double coefNotoriete;
    private LocalDate dateDerniereVisite;
    private int dernierCoefConfiance;
    private String adresse;
    private String codePostal;
    
    Visiteur
    private String matricule;
    private String nom;
    private String prenom;
    
    RapportVisite
    private int numero,coefConfiance ;
    private LocalDate dateVisite, dateRedaction ;
    private String bilan, motif ;
    private boolean lu ;
    private Visiteur leVisiteur ;
    private Praticien lePraticien ;
    
    
    VUES :
    
    VueConnexion
    VueConnexionEchoue
    VueConnexionVide
    VueRapport
    VueRapportIncomplet
    
