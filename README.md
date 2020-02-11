# probleme-solution-vmware12-et-sql-developeur-
probleme/solution vmware12 et sql  developeur

je tiens à partager avec vous  Les Problèmes et les solution que je trouve lors de la préparation de l'environnement " machine virtuelle : vmware workstation 12" et "sql developeur 19.4" .

-Probleme 1: au niveau d'installation  machine virtuelle vmware worksattion 12 message "non compatible with win 10 64bit" 
    *La solution - : 
installation outil adk tools --> adk tools install --> Cocher comptabilty adminstartor 64bit-->installation ;" Dans barre de recherche" taper comptability adminisatrator 64bit -->selectionner Application ---> Selectionner Vmware Workstation Pro -->bouton droit sur vmpalyer.exe et vmware.exe"Disable entry" --> fermer fenetre apres essayer de lancer vmware worstation :)

-Probleme2 :Au niveau Sql developeur pour la  creation  "New database connection"="Status : message "Failure -Test failed: IO Error: The Network Adapter could not establish the connection" 
     *La solution : 
Install oracle 11g -->au cours de l'installtion dOracle 11g inserer votre mot de passe "-->installation finish; run/ excute ---> taper services.msc--->cherche tout les services d'oracle --> bouton droit select all tasks run /toutes les taches excuters ----> Start/demarrer --> close;  Open sql developper--->create a new database connection --->username"system" +passowrd" que vous taper à l'oracle 11g" ---->enjoy :)   
