# UE génétique médicale examen 2018-06-14
Jérémy Sornette
URL du sujet : https://gist.github.com/Oodnadatta/fdc36ee1393b08a60361c98260a1194f

## Exercice 1

### Q1
Les trois principaux gènes liés au syndrome de Rett sont : MECP2 ; CDKL5 ; FOXG1. (https://www.inserm.fr/information-en-sante/dossiers-information/rett-syndrome)

### Q2
Ces variants se situent sur le gène MECP2 (https://www.ncbi.nlm.nih.gov/nuccore/NM_004992.3)

### Q3
Le gène MECP2 se trouve sur le chromosome X, locus 28 (https://www.omim.org/entry/312750?search=MECP2&highlight=mecp2)

### Q4
La transmission du syndrome de Rett lié à ce gène se fait sur un mode lié à l'X dominant.

### Q5
Une maladie génique liée à l'X dominante comprend un gène anormal sur le chromosome X. La présence d'un seul gène anormal est suffisante pour faire apparaître la maladie chez le garçon ET chez la fille (le deuxième chromosome ne compense pas).

### Q6
Le gène anormal est transmis soit par le père soit par la mère. Le parent qui transmet le gène est obligatoirement malade car le gène est dominant.

### Q7
La notation protéique de ces variants au format HGVS est :
NM_004992.3:c.502C>T  donne NM_004992.3(MECP2_i001):p.(Arg168*)
NM_004992.3:c.1335G>A donne NM_004992.3(MECP2_i001):p.(=)

### Q8
La signification de cette notation est :
**NM** : mRNA
**004992** : numéro du transcrit
**3** : version du transcrit
**(MECP2_i001)** : nom du gène et numéro d'isoforme 
**p.** signifie qu'on est au niveau de la séquence protéique
**(Arg168*)** : substitution d'une Arginine par un codon stop en position 168 ; (=) : non analysé mais aucun changement majeur attendu
(https://www.hgvs.org/mutnomen/recs.html)

### Q9
Le premier variant a subit une variation non-sens.
Le second variant est analysé comme variant synonyme.

### Q10
**c.502C>T**	nombres de cas : 363 ;	fréquence : 7.66. Il est dit dans la plupart des cas que la mutation est présente chez les patientes atteintes. La mutation donne une **protéine tronquée**, les patientes présentent le syndrome de Rett.
**c.1335G>A**	nombres de cas : 10	;   fréquence : 0.21. Il est dit dans la plupart des cas que la mutation est présente mais que les patients ne présentent pas le syndrome de Rett. Il est dit que c'est un **polymorphisme siliencieux**.

Ainsi, il est beaucoup plus probable que la mutation **c.502C>T** soit responsable du syndrome de Rett chez cette patiente. 

(http://mecp2.chw.edu.au/cgi-bin/mecp2/views/basic.cgi?form=mut-freq-rev)
(http://mecp2.chw.edu.au/cgi-bin/mecp2/search/process-search.cgi)

### Q11
**NM_004992.3:c.502C>T** donne **NC_000023.10:g.153296777G>A**.
**NM_004992.3:c.1335G>A** donne **NC_000023.10:g.153295944C>T**.

### Q12
La signification de cette notation est :
**NC** : complete genomic molécules (génome *théoriquement* complet)
**000023** : chromosome 23 correspondant au chromosome X
**10** version 10 du chromosome X
**g.** : notation génomique
**153296777G>A** : position du remplacement de la base G par une A ; **153295944C>T** : position du remplacement de la base C par une T

### Q13
**NC_000023.10:g.153296777G>A** n'est visiblement pas présent sur gnomAD.
http://gnomad.broadinstitute.org/variant/X-153296777-G-A
**NC_000023.10:g.153295944C>T** est présent sur gnomAD.
http://gnomad.broadinstitute.org/variant/X-153295944-C-T

### Q14
**NC_000023.10:g.153295944C>T** est a donc une fréquence de **0.001394** dans la population générale.
http://gnomad.broadinstitute.org/variant/X-153295944-C-T

## Exercice 2

### Q1
a) OMIM database est une base de donnée qui dresse un catalogue de toutes les maladies connues en lien avec une composante génétique.
b) DDG2P *(Developmental Disorders Genotype-Phenotype Database)* gene list est une liste de gènes reporté pour être associés avec des troubles du développement, compilés par des cliniciens.

### Q2

### Q3
a) **NM_001190274.1** : NM signifie que l'on est dans un format en lien avec un mRNA ; **001190274** est le numéro du transcrit concerné ; **1.** signifie que l'on s'intéresse à la version 1 du transcrit.
b) **HGVS** signifie Sequence Variant Nomenclature from the Human Genome Variation Society soit nomenclature des variantes de séquences de la Société de variation du génome humain
c) **GRCh37/hg19 human genome assembly** : GRCh37 est la séquence de référence du génome humain version 37 (Genome Reference Consortium Human Build 37). hg19 en est un synonyme. On se base sur cette séquence de réference du génome humain pour comparer les séquences des autres patients. Cette séquence de référence est statistiquement la séquence "normale". Elle est régulièrement mise à jour. On utilise ici la version 37.

### Q4
La méthode utilisée pour l'exploration des patients 1 et 2 est le **Whole Exom Sequencing (WES)**. 

Partant du principe que les séquences codantes ne représentent qu'une faible partie du génome mais concentrent 85% des mutations potentiellement responsables des maladies, des méthodes permettant de "capturer" l'ensemble des séquences codantes ("Whole Exome") et d'en déterminer la séquence ("Whole Exome Sequencing") ont été développées. Ces méthodes de "Whole Exome Sequencing" (WES) permettent d'identifier en théorie la quasi totalité des variations de séquences qui existent au niveau des séquences codantes entre des sujets atteints de la maladie multifactorielle et des sujets indemnes. On voit que cette approche WES est bien adaptée à la caractérisation des variants rares.

### Q5
Un séquençage de Sanger a été réalisé chez les patients concernés et chez leurs parents pour confirmer la présence d'un variant sur FBX011 ainsi que pour confirmer l'absence du variant chez les parents, permettant ainsi d'affirmer qu'il s'agit d'une mutation *de novo*.

### Q6
Les critères qui ont permis de classer les variants des patiens 1 et 2 comme délétères sont :
- des parents sains, non consanguins, sans particularité notable.
- naissance spontannée à terme
Ces deux premiers critères permettent d'incriminer le variant et pas des causes autres liés aux parents.

- taille et poids dans la limite basse
- microcephaly
- problème du développement osseux
- retard de développement intellectuel
- Investigation incluant EEG, test auditif, visuel etc.. normaux
- examen biologique normal
- atrophie cérébrale et hypertension intra-cranienne
- anomalies de croissance 

### Q7
Le gène FBXO11 est un bon candidat pour la déficience intellectuelle car d'autres publications liant de gène FBXO11 et la déficience mentale ont été publiés, rapportant des mutaions faux-sens, d'épissage, et de frameshifts.
De plus, FBXO11 est un gène lié aux protéines de la famille F-box, importante au niveau de la catalyse de l'ubiquitinylation dépendante de phosphorylation. Ainsi des mutations à ce niveau ont d'importantes conséquences.
Des variants sur ce gène ont également présenté des anomalies types otite chronique, perte d'ouïe chez l'enfant etc...

