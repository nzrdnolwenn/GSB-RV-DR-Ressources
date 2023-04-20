# GSB-RV-DR-Ressources
Ressources
    
    TABLES: 	
    
    +-----------------+
	| Tables_in_gsbrv |
	+-----------------+
	| activitecompl   |
	| composant       |
	| connaitre       |
	| constituer      |
	| dosage          |
	| famille         |
	| formuler        |
	| interagir       |
	| inviter         |
	| laboratoire     |
	| medicament      |
	| motif           |
	| offrir          |
	| posseder        |
	| praticien       |
	| prescrire       |
	| presentation    |
	| rapportvisite   |
	| realiser        |
	| region          |
	| secteur         |
	| specialite      |
	| travailler      |
	| typeindividu    |
	| typepraticien   |
	| visiteur        |
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
    
    
