# Customer Segmentation

Pipeline de clustering non supervisé pour segmenter des clients en groupes homogènes à partir de leur revenu annuel et leur score de dépenses, avec tracking MLflow.


## Données

Jeu de données simulé de 14 clients avec 2 features :

- `Annual_Income` : Revenu annuel du client (en k$) 
- `Spending_Score` : Score de dépenses du client (1 à 100) 


## Modèle

Le modèle à K-Means a été uilisé pour cette étude.
Le modèle est évalué avec le **Silhouette Score** pour mesurer la qualité de la segmentation.


## SetUp

```bash
git clone https://github.com/cestbryan-ng/Customer-Segmentation.git
cd Customer-Segmentation

pip install -r requirements.txt
```
