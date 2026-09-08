```
Agis en tant qu'expert en ingénierie pédagogique, transcripteur de haut niveau et tuteur universitaire. J'ai besoin d'une transcription fidèle, corrigée et enrichie pédagogiquement de ma source intitulée :
[NOM_DE_LA_SOURCE].

Je veux que tu traites précisément la plage suivante :
[PLAGE_DE_PAGES].

Pour chaque diapositive/page, génère un rendu structuré dans un fichier Markdown (.md) enregistré dans mon espace de travail, en respectant STRICTEMENT le cahier des charges suivant :

1. **Transcription Textuelle & Analyse des Notes Personnelles `[...]`** :
   - Transcris fidèlement tout le texte d'origine présent sur la diapositive.
   - **ATTENTION - Règle d'or pour les crochets `[...]`** : Les éléments que j'ai ajoutés entre crochets sont des notes personnelles rapides, des questions ou des hypothèses de ma part. Elles peuvent être incomplètes, scientifiquement imprécises, voire carrément fausses ou mal placées. Ton rôle est d'analyser cette note avec un œil critique de professeur :
     1. **Vérification** : Fact-checke ma note. Si elle contient une erreur ou une approximation, corrige-la gentiment.
     2. **Contextualisation** : Si ma note semble déconnectée du sujet principal de la diapo, explique sa véritable place dans le cours.
     3. **Développement pédagogique** : Développe le concept de manière ultra-claire et détaillée, comme si tu l'expliquais à un étudiant qui a des difficultés à le comprendre. Décompose les notions complexes.
   - Pour que je repère immédiatement tes corrections et explications, mets-les en gras et en italique sous cette forme :
     ***[Tuteur IA - Correction & Explication de votre note : <insère ici ta correction bienveillante, ton explication claire et ton développement détaillé>]***.

2. Description Visuelle Analytique :
   - Pour chaque image, graphique, schéma ou portrait, rédige une description visuelle détaillée.
   - Explique le lien pédagogique entre l'image et le texte de la diapositive (pourquoi cette image est là et ce qu'elle apporte à la compréhension).
   - Si aucun visuel n'est présent, indique : "Visuel : Présentation textuelle uniquement".

3. Formatage et Structure :
   - Structure diapositive par diapositive (ex: "## Diapositive X : [Titre]").
   - Sépare clairement la section "Transcription et Analyse" et la section "Description Visuelle".
   - Ne fais aucun résumé paresseux des concepts officiels du cours.

Génère ce travail directement sous la forme d'un fichier Markdown (.md) bien mis en forme dans mon Studio d'artéfacts.
```


```
Agis en tant que spécialiste des sciences cognitives et de la mémorisation active. Ton objectif est de concevoir mon kit de révision sur la base de deux documents de référence pour éviter toute hallucination :
- Ma source brute d'origine : **[NOM_DE_LA_SOURCE_BRUTE, ex: psycho_1.pdf]**
- Mon cours de référence déjà généré : **[NOM_DU_FICHIER_GÉNÉRÉ_AU_PROMPT_1, ex: cours_reference_psycho_1_diapos_1_40.md]**

En croisant rigoureusement ces deux fichiers, réalise les livrables suivants :

1. **Le Fichier d'Importation Anki (.txt)** :
   - Génère un fichier nommé `anki_[NOM_DE_LA_SOURCE].txt` au format officiel Anki (séparateur : TABULATION).
   - Conçois des flashcards (recto/verso) courtes, percutantes et ciblées sur les notions clés, définitions, dates, chercheurs et structures vus dans les deux fichiers.
   - Chaque ligne doit être structurée ainsi : [Question] -> [TABULATION] -> [Réponse].

2. **Le Schéma de Révision Muet (.png)** :
   - Identifie le schéma visuel ou anatomique le plus important de cette section (ex: le cerveau, les aires du langage, etc.).
   - Génère une version simplifiée et épurée de ce schéma où les légendes textuelles sont effacées et remplacées par des numéros (1, 2, 3...). Nomme l'image `schema_muet_[NOM_DE_LA_SOURCE].png`.

3. **Le Cahier d'Exercice & Corrigé (.pdf)** :
   - Génère un document PDF d'exercice élégant nommé `cahier_revision_[NOM_DE_LA_SOURCE].pdf`.
   - **Page 1 : L'exercice** (Le schéma muet avec des lignes blanches numérotées pour que je puisse m'auto-évaluer à l'écrit).
   - **Page 2 : Le corrigé détaillé** (Une table contenant le numéro, le nom de la structure/concept, son rôle précis dans le cours et pourquoi il est important d'après nos deux fichiers de référence).
```
