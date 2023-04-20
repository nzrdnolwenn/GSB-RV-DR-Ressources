# GSB-RV-DR-Ressources
Ressources
    
    Tables: 
    
    Entités : 
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
