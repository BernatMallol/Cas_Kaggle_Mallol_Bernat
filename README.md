# Cas_Kaggle_Mallol_Bernat
Aquest projecte consta de 4 parts:

Part1: Analisis de dades.
  -Farem un estudi de les dades, que finalitzarà amb la selecció de 
   la variable target (a predir) i les variables independents amb les
   que treballarem.
 
Part 2: Preprocessing.
  -En aquesta part, un cop sapiguem les variables amb les que treballaré,
   faré una nateja de les dades que ens trobem, en el meu cas, al estar
   treballant amb variables de tipus text, apart de fer una neteja de caracters
   especials, entre altres, també he hagut de crear un diccionari on hi he posat
   els pesos de cada paraula y la frequencia d'aquestes.

Part 3: Entrenament de models.
 -En aquest apartat, he entrenat 2 models diferents, que em permetien
 treballar amb variables de text, aquests 2 models han estat:
 
    Part 3.1: Naive Bayes.
      -Es un classificador el qual te com a  principals caracteristiques, el fet de poder treballar amb variables
      de text, i per altre banda, no necesita un conjunt d'entrenament molt gran per a poder tenir bona precissió. 
      
    Part 3.2: SVC lineal.
      -Aquest classificador, el qual hem vist a classe, també ens permet treballar amb variables de text, però a 
      diferencia del anterior, aquest tindrà més precissió en base al nombre de mostres del conjunt d'entrenament,
      a mes mostres, més precisió, tenint en compte que aquesta precissió mai sera del 100%, de fet, en cap classificador
      ho serà
      
Part 4: Estudi de resultats i conclusions.
  -Per acabar, un cop entrenats els modelsi habent obtingut les seves respectives precisions,
  pasarem a fer un analisis dels resultats obtinguts, els quals tindrem en compte el temps i la precissió,
  i n'extreurem les conclusions d'aquests entrenaments.
