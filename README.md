# Dataset XSS

Contient un dataset de pages inféctés via XSS qui peuvent etre utilisé pour des problémes de machine learning .

Je propose plusieurs formats qui ont tous été récupérés via ce script : [XSS Dataset Crawler](https://github.com/ukarroum/xss-dataset-crawler) .

## Fichiers *xss_dataset_n.pickle.tar.gz*

Chacun de ses fichiers contient l'url et le code HTML de 3000 pages web inféctés via XSS (récupérés sur XSSED) .
C'est un simple fichier pickle que vous pouvez lire avec python (tésté sur avec python 3 ) (aprés décompression) comme suit :

```
>> import pickle
>> web = pickle.load(open("Nom du fichier", "rb")

>> 

```

C'est une simple liste de tuples chaque tuple représantant l'url et son contenu HTML respective .



