# Examen UF2

### Heu d'entregar un .zip amb tot el que heu fet, inclòs els .xcf de GIMP (un per la imatge, altre per l'animació), a més de l'enllaç al vostre repositori.
### Teniu les dues hores.

## Exercici 0. 

> ### (1 punt)

- Feu un fork d'aquest repositori. 
- Feu cada exercici en una branca diferent.
- Feu commits amb descripcions adients per cada apartat.  
- En acabar i abans d'entregar, fusioneu totes les branques a _main_, de manera que quedi tot integrat a la branca _main_.
- Pugeu al vostre repositori ***TOTES*** les branques.

> ### (0,5 punts)

- Totes les imatges finals modificades i utilitzades han d'estar a la carpeta _img_.
- El codi ha d'estar ben organitzat, amb comentaris NOMÉS si és necessari, separant el que és HTML del Javascript i del CSS.


## Exercici 1.

L'objectiu és fer el mateix que el banner de la pràctica Web amb animacions CSS, amb certes modificacions.

> ### (0,5 punts)

- Afegiu una capa a la pàgina que tindrà la imatge banner (_img/banner.jpg_). La proporció de la imatge s'ha de mantenir si la finestra es redimensiona.

> ### (1,5 punts)

Agafeu la imatge original del cotxe (_originals/car.jpg_) i editeu-la amb GIMP.

- ***IMPORTANT: Imprescindible que afegiu, com si fos una enganxina, el vostre nom al cotxe.***
- Canvieu la mida de la imatge, optimitzant-la per les necessitats. Es tindrà el compte el pes final de l'arxiu (en KB).
- Retalleu el contorn del cotxe acuradament per a que el desplaçament per la pantalla sigui realista. Si manteniu l'ombra sota del cotxe millor, que fa que sigui més realista.
- Feu que les finestres del cotxe siguin transparents, de manera que es vegi a través la imatge de fons durant el moviment. 

> ### (1 punt)

Utilitzant les imatges que teniu a la carpeta _originals_:

- Feu un GIF animat incloent al cotxe el conductor que realitzi una salutació amb un mínim de 3 posicions diferents:
    * Conductor de perfil
    * Conductor de cara amb el braç en una posició
    * Conductor de cara amb el braç en una altra posició que simuli una salutació.
- L'animació ha de durar dos segons aproximadament (un segon conduint, un segon saludant), pel que heu de variar la durada dels fotogrames.

> ### (1,5 punts)

- Afegiu la imatge (o GIF animat) que heu creat i feu que el cotxe, animat amb CSS, travessi completament el carrer de banda a banda.
    * ***IMPORTANT: L'animació ha de executar-se cada 8 segons i cada trajecte (de banda a banda) ha de durar 4 segons.***
    * La mida del cotxe ha de ser la necessària per a que s'integri de manera realista al fons. Ha d'estar a sobre la carretera, no al peu de foto del fons.
    * L'animació no pot generar scroll (barres d'scroll) a la pàgina.
    * La posició del cotxe ha de mantenir-se estable respecte al fons encara que la mida de qualsevol altra part de pàgina canvii, com per exemple, la capçalera. Comproveu que si feu més gran la lletra de la capçalera el cotxe continua transitant per l'asfalt. També si la finestra del navegador es redimensiona.


## Exercici 2.

L'objectiu és manipular els SVG i gestionar àudios i la seva reproducció. Agafeu el SVG del pallaso (_originals/pallasso.svg_) i afegiu-lo a la pàgina. Heu de:

> ### (1 punt)

- Afegiu al pallasso un altre element SVG que simuli una llàgrima (amb forma de llàgrima) de color blau (el mateix color que el del fitxer _originals/color-llagrima.png_) caient de l'ull esquerre del pallasso. El color ha de ser exacte i la posició de la llàgrima correcta.

> ### (1,5 punts)

- Trobeu i baixeu d'internet un tall d'àudio d'una risa qualsevol. Heu de comprovar que el podeu utilitzar, ja sigui per ser de domini públic o afegint els crèdits corresponents segons la seva llicència. ***Afegiu, IMPRESCINDIBLE***, al peu del pallasso:
    * en tot cas, l'enllaç d'on heu baixat l'àudio i, IMPORTANT, on heu comprovat la llicència a la que està lligat,
    * la informació relativa a la llicència: crèdits, enllaç... (només si és necessari).

> ### (1,5 punt)

- Afegiu l'àudio a la pàgina de manera que quedi ocult (no es pot veure el reproductor).
- Afegiu el codi necessari per a que al fer clic al nas del pallaso (només al nas), es reprodueixi l'àudio un cop. 

> [!NOTE] 
> Si no heu baixat cap àudio podeu utilitzar el que trobareu a la carpeta _originals_ (_originals/media/riure.mp2_). Aquest àudio però, con veureu, per escoltar-se, necessita una conversió de format.
