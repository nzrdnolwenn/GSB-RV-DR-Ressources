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
    private int numero;
    private String nom;
    private String ville;
    private double coefNotoriete;
    private LocalDate dateDerniereVisite;
    private int dernierCoefConfiance;
    private String adresse;
    private String codePostal;
    private String prenom;
    
    Visiteur
    private String matricule;
    private String nom;
    private String prenom;
    
    RapportVisite
    private int numero;
    private LocalDate dateVisite;
    private LocalDate dateRedaction;
    private String bilan;
    private String motif;
    private int coefConfiance;
    private boolean lu;
    private Visiteur leVisiteur;
    private Praticien lePraticien;
    
    
