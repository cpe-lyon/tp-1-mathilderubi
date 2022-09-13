# Compte-rendu TP
*Mathilde Rubi*

## Exercice 2 

### Manuel
1.	Which : localiser la commande
2.	Avec man –k mot clé
3.	En appuyant sur q

![img1](image/image1.png)
 
4.	 Cette section traite des jeux et petits programmes du système.

![img2](image/image2.png)
 
 
### Navigation dans l'arborescence des fichiers

1.	 ![img3](image/image3.png)
2.	 ![image4](image/image4.png)
3.	 ![img5](image/image5.png)
4.	 ![img6](image/image6.png)
5.	 ![img7](image/image7.png)
6.	 ![img8](image/image8.png)
7.	 ![img9](image/image9.png)
8.	 ![img10](image/image10.png)
9.	 ![img11](image/image11.png)
10.	 ![img12](image/image12)
11.	 ![img13](image/image13.png)
 
8.	Suppression de fichier1
9.	
 ![img14](image/image14/png)
 
Suppression de dossier1

 ![img15](image/image15.png)

9.	La commande rmdir permet de supprimer un dossier vide

10.	Ne fonctionne pas, le dossier doit être vide
11.	
 ![img16](image/image16.png)
 
11.	Il faut utiliser la commande rm –r ou Rm –rf pour forcer à tout effacer

 ![img17](image/image17.png)
 
 ![img18](image/image18.png)
 
Tout est effacé

### Commandes impoirtantes

1.	La commande date permet d’afficher l’heure

 ![img19](image/image19.png)
 
La commande time sert à visualiser les temps d’exécution des commandes

2.	 ![img20](image/image20.png)

Les fichiers commençant par un point sont des fichiers cachés

3.	Le programme ls se situe dans /usr/bin/ls

  ![img21](image/image21.png)
  
  ![img22](image/image22.png)
  
4.
![img23](image/image23.png)

Cette commande affiche les détails des fichiers

5.	 ![img24](image/image24.png)

6.	La commande ls .. affiche les dossiers du dossier parent à là où on se situe

![img25](image/image25.png)

La commande pwd

8.	Ecrit bip dans un fichier plop, l’exécuter plusieurs fois écrase et réécrit le contenu du fichier plop

9.	Ecrit bip dans un fichier plop, l’exécuter plusieurs fois ajoute le texte à la suite du fichier plop

10.	Enlève la saisie pendant 10 secondes, mets le système en pause tout en affichant le texte ‘toto’

![img26](image/image26.png)
 
11.	 ![img27](image/image27.png)

Donne le type de fichier

12.	 ![img28](image/image28.png)

13.	 ![img29](image/image29.png)

![img30](imagr/image30.png)

![img31](image/imag31.png)

![img32](image/image32.png)

Le contenu de lien_phy est le même que le fichier original

 ![img33](image/image33.png)
 
Le fichier original n’existe plus mais le contenu de lien_phy est inchangé

![img34](image/image34.png)

13.	 
Lorsqu’on change le contenu de lien_sym est le même que le contenu de lien_phy.
La même chose pour la situation inverse

![img35](image/image35.png)

Lorsqu’on supprime lien_phy, lien_sym est aussi supprimé

![img36](image/image36.png)

14.	Le raccourci ctrl+s stoppe le défilement, le raccourci ctrl+q reprend le défilement

15.	La commande head affiche les 10 premières lignes

![img37](image/image37.png)
 
 
Sinon spécifier le nb de lignes avec head –n, ici 5

![img38](image/image38.png)

Pour les 15 dernières, utiliser la commande tail -15

![img39](image/image39.png)

Pour les lignes de 10 à 20 : 

![img40](image/image40.png)

16.
17.  
![img41](image/image41.png)

![img42](image/image42.png)

18. avec la commande sort –k1

19. La commande wc -l 

![img43](image/imagfe43.png)

20. 
21. 
Find –name passwd

22.
```
 echo find –name passwd >>/list_passwd_files.txt 2>>/dev/null
 ```
 
23.
```
grep -R 'll '
```

25. 

## Exercice 3
1.
```
cp /var/log/syslog /home/User
mv syslog log.txt
nano log.txt
```

2.
```
altgr  ctrl 8
kernel noyau a replace all
```

 3.
 
4. alt U Undo
5. ctrl x enregistrer

## Exercice 4 
