# Travaux dirigés et travaux pratiques - semaine 2

This Java template lets you get started quickly with a simple one-page playground.

```java runnable
/*********************************TP 2.1***********************************************/

public class Etudiant {

	
	/****************** Partie attributs ****************************************/
	
	//L'attribut nom de l'étudiant
	private String nom;
	
	// Vous devez insérer ci-dessous les autres attributs (l'age et les 3 notes)
	
	
	/***************************************************************************/
	
	
	
	/********************Partie Constructeurs ***************************/
	
	//Constructeur par défaut qui ne contient aucun attribut
	public Etudiant(){
		
	}
	
	
	//Constructeur qui contient seulement l'attribut nom 
	public Etudiant(String name){
	this.nom = name;
	}
	
		
	//Vous devez ci-dessous définir le constructeur qui initialise tout sauf les notes de l'étudiant
	
	
	//Vous devez ci-dessous définir le constructeur qui initialise tout sauf l'age de l'étudiant
	
	
	//Vous devez ci-dessous définir le constructeur qui initialise tous les attributs
	
		
	
	/***********************************************************************/
	
	
	/*************************************Partie Accesseurs ***********************/
	
	/* Accesseurs de l'attribut nom : 
		getNom qui retourne la valeur du nom 
		setNom qui initialise la valeur du nom
	 */
	
	public String getNom() {
		return this.nom;
	}
	
	
	public void setNom(String name) {
		this.nom = name;
	}
	
	/* Vous devez ci-dessous créer les accesseurs pour les autres attributs : */
		
	//Accesseurs de l'age
	
	
	
	//Accesseurs des notes
	
	
	
/***********************************************************************************/
	
	
	
	
	
/****************************** Partie méthodes ***************************************/	
	
	
	/* Méthode toString() qui permet d'afficher des informations concernant un étudiant. 
	Méthode à décommenter et à modifier ci-dessous */
		
	
		/* public String toString() {
			return "";
		} */
	
	
	
	
	/* Méthode saisie qui permet à l'utilisateur de saisir les informations des étudiants et de les initialiser. 
	 Méthode à écrire intégralement en vous inspirant du TP1  */
		
	
	
	
	/* Méthode moyenne à décommenter et à remplir */
	
		/*
		 public double moyenne(){
		 	return 
		 }
		 */
	
	
	/* Méthode mention à écrire ci-dessous. 
	 Cette méthode utilise la méthode moyenne définie précédemment 
	 et retourne une chaine de caractère qui correspond à la mention de l'étudiant dont les valeurs possibles sont :
	 Ajourné, passable, AB, Bien, TB */
	
	
	
	
	/* Methode ligneResultat à écrire ci-dessous 
	 * Cette méthode utilise le résultat de moyenne et de mention
	 * et retourne une chaine de caractère précisant :
	 * le nom, la moyenne, la mention, et si l'étudiant est ajourné, la liste des modules obtenus
	 */
	
	

}

public class Main {

	public static void main(String[] args) throws IOException {
		
		 
		 /***********************Constructeurs *******************************************/
		
			//Création d'un nouvel étudiant dont le nom est paul  
			Etudiant etud1 = new Etudiant("Paul");
		
			//En vous inspirant de l'exemple, écrire ci-dessous le code pour créer les autres étudiants  
			
		
		
		/***********************************Accesseurs*****************************************/
		
		/* Affichage des informations grâce à l'accesseur get */
		
			//Affichage du nom de etud1
			System.out.println("Le nom de l'étudiant1 est: " +etud1.getNom());
			
			
			//Ecrire ci-dessous les informations des autres étudiants (toutes les informations connues par étudiant)
			
		
		
		
		/* Modification d'information grâce à l'accesseur set */
		
			// Modification du nom de etud1 
			etud1.setNom("Paul-Henri");
			
			
			// Ecrire ci-dessous le code pour modifier l'âge de Jean
			
			
			
			//Ecrire ci-dessous le code pour modifier la note de programmation de Zoe
	
			
			
			
			// Ecrire ci-dessous le code pour ajouter les notes des autres étudiants
			
		
			
			
			

		/* Verification que les modifications ont bien été prises en compte */
		
			//Pour chaque étudiant modifié, écrire ci-dessous le code permettant d'afficher les nouvelles informations, grâce à l'accesseur get
		
		
			
		
		
		/*************************** Les méthodes ************************************/
		
		
		/* Utilisation de la méthode toString  */
			
			//Utilisation de la méthode toString pour afficher l'étudiant etud1
		
			System.out.println("Informations concernant l'étudiant 1: " + etud1);
			
			//Faire la même chose pour tous les étudiants et vérifier que les données sont correctes
			
		
		
		/* Utilisation de la méthode saisie */
		
			// Créer un nouvel étudiant etud7 grace au constructeur vide
		
	
			// Ouvrir le scanner
	
		
			//Utiliser la méthode saisie définie dans la classe Etudiant sur l'étudiant etud7 (vous choisissez les valeurs)
	
		
			//Vérifier grâce à la méthode toString que les informations concernant etud7 ont bien été initialisées
		
		
			
			
		
		/* Utilisation de la méthode moyenne */
			
			// Calcul et affichage de la moyenne de Paul-Henri. A décommenter pour exemple
			
				//System.out.println("la moyenne de Paul-Henri est: " + etud1.moyenne());
			
			
			//Ecrire ci dessous le code pour calculer et afficher la moyenne des autres étudiants
			
			
			
			
			
		/* Utilisation de la méthode mention pour chaque étudiant. Code à écrire ci-dessous */	
			
			
		
		
		/* Utilisation de la méthode ligneResultat pour chaque étudiant. Code à écrire ci-dessous */
			
			
		

	}

}



```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Java template](https://tech.io/select-repo/385)
